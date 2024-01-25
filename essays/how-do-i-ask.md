---
layout: essay
type: essay
title: "How Do I Ask?: An overview of smart questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Smart questions
  - Online forums
  - Stack Overflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/sips-of-java.jpg">

# The Problem of Questions

An experience that is far too common in classrooms today is that of the vacuum-like silence that immediately fills the space after the teacher says "Any questions?" I have been on both ends of this, and it is not fun, especially when you can very clearly the confusion and uncertainty painted on the students' faces. There are so many questions that are waiting to be asked! Yet, students hold off on asking, usually because most of those questions are nascent, barely conceptualized feelings of confusion, but also because students may perceive their questions to be too "stupid." Now, in a classroom environment, I hold the belief that these "stupid" questions should be asked. After all, in person, such questions can be really funny! Subsequently, even if the answer is quite obvious or plain, it can encite further discussion and encourage those with "smart" questions to formalize their question's wording and actually ask.

This does not carry over to online forums for software engineering. Online, questions are often viewed in a vacuum and do not inspire a continuing discussion like they would in a classroom environment. Furthermore, the marketplace of questions is teeming with dumb questions that can either be solved with a good search on Google or are so incoherent or vague that it would take a miracle for an online stranger to be able to find out what is being asked. In effect, a question must be sold and packaged as a "smart" question in order to attract the interest of "consumers," or online experts, so that they can give you help. So how do we phrase our questions to be "smart?" What qualifies as a "stupid" question?

# The Dumb

The following example of a stupid question comes from [this Stack Overflow question](https://stackoverflow.com/questions/77882598/error-the-name-gridview1-does-not-exist-in-the-current-context). The question goes as follows:

```
I am learning how to retrieve data from mysql database using c# webforms

this is default.aspx.cs

using System;
using System.Collections.Generic;
using System.Data.SqlClient;
using System.Web.UI.WebControls;


    public partial class _Default : System.Web.UI.Page
{


        protected void Page_Load(object sender, EventArgs e)
    {
        if (!IsPostBack)
        {
            BindData();
        }
    }

private void BindData()
{
    List<Student> students = new List<Student>();

    string connectionString = System.Configuration.ConfigurationManager.ConnectionStrings["MyDbConnection"].ConnectionString;

    using (SqlConnection connection = new SqlConnection(connectionString))
    {
        string query = "SELECT Id, FirstName, LastName, Age, Course FROM AllStudents";
        using (SqlCommand command = new SqlCommand(query, connection))
        {
            connection.Open();
            using (SqlDataReader reader = command.ExecuteReader())
            {
                while (reader.Read())
                {
                    Student student = new Student
                    {
                        Id = Convert.ToInt32(reader["Id"]),
                        FirstName = reader["FirstName"].ToString(),
                        LastName = reader["LastName"].ToString(),
                        Age = Convert.ToInt32(reader["Age"]),
                        Course = reader["Course"].ToString()
                    };
                    students.Add(student);
                }
            }
        }
    }

    GridView1.DataSource = students;
    GridView1.DataBind();
}
}


public class Student
{
    public int Id { get; set; }
    public string FirstName { get; set; }
    public string LastName { get; set; }
    public int Age { get; set; }
    public string Course { get; set; }
}

and default.aspx file:

<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Default.aspx.cs" Inherits="_Default" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title>Student Data</title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:GridView ID="GridView1" runat="server" AutoGenerateColumns="False">
                <Columns>
                    <asp:BoundField DataField="Id" HeaderText="ID" />
                    <asp:BoundField DataField="FirstName" HeaderText="FirstName" />
                    <asp:BoundField DataField="LastName" HeaderText="LastName" />
                    <asp:BoundField DataField="Age" HeaderText="Age" />
                    <asp:BoundField DataField="Course" HeaderText="Course" />
                </Columns>
            </asp:GridView>
        </div>
    </form>
</body>
</html>

How to solve the error 'The name 'GridView1' does not exist in the current context'?

unfortunately after providing full detail I still cant post the question due to 'It looks like your post is mostly code; please add some more details.' so excuse me for including this paragraph
```

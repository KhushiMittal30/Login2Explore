# Project Management Form

A web-based **Project Management Form** built with `HTML`, `CSS`, `Bootstrap`, and `JsonPowerDB`. This form allows users to manage project details efficiently by performing CRUD (Create, Read, Update, Delete) operations on a `PROJECT-TABLE` relation within the `COLLEGE-DB` database. The system ensures data integrity by using **Project ID** as the primary key.

---

## Table of Contents
1. [Project Description](#project-description)
2. [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Scope of Functionalities](#scope-of-functionalities)
4. [Examples of Use](#examples-of-use)
5. [Screenshots](#screenshots)
6. [Project Status](#project-status)
7. [Release History](#release-history)
8. [Sources](#sources)
9. [Other Information](#other-information)

---

## Project Description

This **Project Management Form** is a lightweight web application that:
- Stores and retrieves project details in the `PROJECT-TABLE` relation of the `COLLEGE-DB` database.
- Ensures unique identification of projects using **Project ID** as the primary key.
- Enables CRUD operations with a user-friendly interface and form validation.
- Integrates with JsonPowerDB for fast and efficient database interactions.

### Input Fields:
- **Project ID** (Primary Key)
- **Project Name**
- **Assigned To**
- **Assignment Date**
- **Deadline**

---

### Benefits of using JsonPowerDB

- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.
---

## Scope of Functionalities

1. **Add a New Project**: Save a new project record in the database.
2. **Fetch Existing Data**: Retrieve and auto-fill project details based on the **Project ID**.
3. **Update Project Details**: Modify existing project records using the unique **Project ID**.
4. **Reset Form**: Clear all fields to allow a new input.
5. **Form Validation**: Ensures required fields are properly filled before submission.

---

## Examples of Use

- **Adding a New Project**:
  Enter the details for a new project, including `Project ID`, and click **Save**.
  
- **Updating a Project**:
  Retrieve an existing record by entering the `Project ID`, make changes, and click **Change**.

- **Resetting the Form**:
  Click the **Reset** button to clear the form fields for a new entry.

---

### Screenshots:

![Dashboard](/Assets/Dashboard.png)

![Visualize](/Assets/Interface.png)

![Visualize](/Assets/Interface2.png)

---

## Project Status

The project is **complete** and fully functional. Further enhancements may include:
- Adding role-based access control.
- Exporting project data to a file format like Excel or PDF.
- Accessing the previous and next project to the current project.

---

## Release History

- **v1.0.0**: Initial release with basic CRUD functionalities.

---

## Sources

- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)

---


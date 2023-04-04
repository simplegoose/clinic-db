# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Create database](#create-database)
- [Database Schema Diagram] (#Database-Schema-Diagram)
- [👥 Author](#author)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 Clinic Database <a name="about-project"></a>

**Clinic Database** is a project to create the schema structure for a clinic using a relational database based on a diagram. It implements PostgreSQL.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- Create a schema to clinic database
- Insert some data into table, and query it

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

### Prerequisites

In order to run this project you need:

- [PostgreSQL server](https://www.postgresql.org/download/) installed and running
- [psql](https://www.postgresql.org/docs/current/app-psql.html) installed

### Setup

Clone this repository to your desired folder:

```
git clone https://github.com/simplegoose/clinic-db.git
cd clinic-db
```

### Create database

1. Connect to your PostgreSQL server with `psql`
```
> psql
postgres=#
```

2. Create the database `clinic_db`
```
postgres=# CREATE DATABASE clinic_db;
CREATE DATABASE
```

3. Connect to your database clinic_db. Inside your current session do:
```
postgres=# \c clinic_db
You are now connected to database "clinic_db" as user "postgres".
clinic_db=#
```

That's it! Congratulations, you have created your database and connected to it. Next, we will add a table.

- Use [schema_based_on_diagram.sql](./schema.sql) to create all tables.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Database Schema Diagram
![Schema Diagram soom](./img/schema.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Author <a name="authors"></a>

👤 **Vanessa Oliveros Padron**

- GitHub: [@vvoo21](https://github.com/vvoo21)
- Twitter: [@vaneoliverosp](https://twitter.com/vaneoliverosp)
- LinkedIn: [vaneoliverosp](https://www.linkedin.com/in/vaneoliverosp/)

👤 **Timothy Njoroge**

- GitHub: [@simplegoose](https://github.com/simplegoose)
- LinkedIn: [Timothy Njoroge](https://www.linkedin.com/in/timothy-njoroge-mwangi/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- Insert new data
- Update existence data
- Delete existence data

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give a start if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- I would like to thank the Microverse program!
- I would like to thank anyone whose code was used!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
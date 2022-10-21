# Chapter 01: What is Data Engineering

## What data engineer do
`Data engineering` is part of the big data ecosystem and is closely linked to data science. Data engineers work in the background and do not get the same level of attention as data scientist, but they are critical to the process of data science.
The roles and responsibilities of a data engineer vary depending on an organization's level of data maturity and staffing levels. At the lowest level, data engineering involves the movement of data from one system or format to another system or format.

### Required skills and knowledge to be a data engineer
Data engineers need to know several languages used to perform many different tasks, such as SQL and Python.
During the transformation phase of the data pipeline, data engineers need to be familiar with data modeling and structures. They will also need to understand the business and what knowledge and insight they are hoping to extract from the data.
Data engineers will need to know the basics of data warehouse design, as well as the types of databases used in their construction.
Data engineers will need to know how to manage entire infrastructure that the data pipeline runs on.

## Data engineering versus data science
Data engineering is what makes data science possible. Again, depending on the maturity of an organization, data scientists may be expected to clean and move the data required for analysis. This is not the best use of a data scientist's time. Data scientists and data engineers use similar tools (Python, for instance), but they specialize in different areas. Data engineers need to understand data formats, models, and structures to efficiently transport data, whereas data scientists utilize them for building statistical models and mathematical computation.
Data scientists will connect to the data warehouses built by data engineers. From there, they can extract the data required for machine learning models and analysis. Data scientists may have their models incorporated into a data engineering pipeline. A close relationship should exist between data engineers and data scientists. Understanding what
data scientists need in the data will only serve to help the data engineers deliver a better product.

## Data engineering tools
Data engineering is part of the overall big data ecosystem and has to account for the three Vs of big data:
* <b>Volume</b>: The volume of data has grown substantially. Moving a thousand records from a database requires different tools and techniques than moving millions of rows or handling millions of transactions a minute.
* <b>Variaty</b>: Data engineers need tools that handle a variety of data formats in different locations (databases, APIs, files)
* <b>Velocity</b>: The velocity of data is always incresing. Tracking the activity of millions of users on a social network or the purchases of users all over the world requires data engineers to operate often in near real time.

### Programming languages
- The lingua franca of data engineering is SQL.
- A large number of open source data engineering tools use Java and Scala (Apache projects)

### Databases
- Relational databases: `Oracle`, `Microsoft SQL Server`, `MySQL`, `PostgreSQL`
- Common databases used in data warehousing are `Amazon Redshift`, `Google BigQuery`, `Apache Cassandra`, and other NoSQL databases, such as `Elasticsearch`.

### Data processing engines
Data processing engines allow data engineers to transform data whether it is in batches or streams. These engines allow the parallel execution of transformation tasks. The most popular engine is `Apache Spark`. `Apache Spark` allows data engineers to write transformations in Python, Java, and Scala.
### Data pipelines
Combining a transactional database, a programming language, a processing engine, and a data warehouse results in a pipeline/
Data pipelines need a scheduler to allow them to run at specified intervals. The simplest way to accomplish this is by using `crontab`.
As your pipelines become more advanced, you will quickly outgrow crontab and will need a better framework.

## Summary
# Hey there !!
Here are some of the basic code snippets for starters.

## Python

### Virtual Environments
Think of it as new OS (or a new machine) for your python installation. And NOT a new python environment for your OS.

**How to setup?**
```markdown
"C:\Program Files\Python38\Python.exe" -m venv virtenv
```
- Full path for python.exe is required in case the **PATH** variable doesn't include it.
- m signifies module. **venv** is a tool (the module) to create virtual environment for python3. It is included in the standard python3 installation. In Python2, virtualenv did the similar job.
- virtenv is the **name** of virtual environment to be created. A folder named virtenv will get created with certain subfolders and files.

**Activate virtual environment**
```markdown
"virtenv/Scripts/activate.bat"
```

**Jupyter**
Jupyter is the most popular IDE for python (and few other languages like Julia, R etc). 

```markdown
pip install jupyterlab
```

**Jupyter notebooks** A jupyter server is started, and a browser window talks to server in a secured manner over REST API.
```markdown
jupyter notebook
jupyter lab
```

**Deactivate virtual environment**
```
"virtenv/Scripts/deactivate.bat"
```

### Apache Spark

### Apache Airflow

### Advanced SQL

1. DDL/DML statements
2. Index
3. Partitions
4. Triggers
5. Analytics function
6. Joins
7. Group by
8. Having
9. Order by
10. Columnar databases

**Bold** and _Italic_ and `Code` text

### Tableau / Qlikview

Tableau and Qlik are 2 most popular proprietary BI tools. Few observations:

1. In general, there are 2 different licensed products. One is a desktop, which is used to for developing the dashboard. 2nd product is Server, which is used for hosting the dashboard on a powerful machine where it can be shared among users.
2. The Desktop product have 2 kind of licenses: personal and professional. Personal edition is usually free, it is meant for users to be able to test and develop and evaluate. However, to be able to host the dashboard on server, a professional edition is required which is NOT free.
3. Deployment models: On premise vs Cloud. Self managed (Tableau Server) vs Tableau managed service (Tableau Online) 
4. Subscription vs permanent licenses: With increased drift towards cloud, vendors are not inclined to sell permanent license. Their licensing models are mostly based on annual pricing.

[Link](url) and ![Image](src)



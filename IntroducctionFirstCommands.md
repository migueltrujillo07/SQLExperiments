We will see some simple how to use SQL to perfome some simple operations.

we should use the database that we create before called mydb.

  
```sh
psql mydb
```

# Create a Table

To create a table we can use the next code, don't worry if after the fist "(" psql will recognize that the command it's no terminated until the semicolon

```sh
`CREATE TABLE weather (
city varchar(80),
temp_lo int, -- low temperature
temp_hi int, -- high temperature
prcp real, -- precipitation
date date
);
```

As you can notice we use "--" when we can to comment some par of the code, remember that a comment is not run, it just indicate something in the code for others developers.

Let's create another table called teachers, this example is taken from the book Practical SQL.

```sh
CREATE TABLE teachers(
id bigserial,
first_name varchar(25),
last_name varchar(50),
school varchar(50),
hire_date date,
salar numeric
);
```

The sintax of PostgreSQL allows you to use your own psychedelic style of Uppercase, lowecase, and random indentations.
However this is not the best when we are working with other, for that we're gonna use the next conventions.

- Uppercase SQL keywords, such as SELEC. Some SQL coders also uppercase the name of data types, such as TEXT and INTEGER.
- Avoid camel case and instead use lowercase_and_underscore for object names, such as tables and column names.
- Indent clauses and code blocks for readablity using either two or four spaces. Some coders prefer tabs to spaces.

There area others rules but as we learn more we will see them.

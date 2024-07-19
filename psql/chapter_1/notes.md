# Some basic commands before
Once you open your terminal make sure you start PostgreSQL by using the command

sudo -u postgres psql

You will be user "postgres". Now, we are ready to perform some actions with this. Use "help", \? and \h if you need help.
Every command starts with a back slach \. If I want to quit PostgreSQL mode, I can type \q.

Command \l gives you a list of the existing databases on your computer: name, owner, encoding, collate, ctype and access privilege. You will notice you have 4 databases which are created by default.

name: Name of the database. This is a unique name within a postgresql instance.
owner: The Postgresql user who owns the database. The owner has full control over the database.
encoding: Encoding determines how text data is stored and retrieved. Common encodings include UTF-8, which supports a wide range of characters from different languages.
collate: It defines how string comparison is performed, including sorting and case sensitivity. For example, a collation setting can affect how "a" and "A" are treated in comparisons or sorting operations.
ctype: This stands for "character classification" and determines how characters are classified and compared, such as in regard to upper and lower case. It affects the behavior of functions like isalpha() and isdigit().
access privilege: This lists the permissions granted to different users for the database. It shows who can connect to the database, as well as any additional permissions such as the ability to create tables or perform other actions.
With en_US.UTF-8, the database uses the same English (United States) rules and UTF-8 (Unicode Transformation Format – 8-bit.) encoding to determine whether characters are alphabetic, numeric, or belong to other categories.

# How to create your own database
Use the sql query:

CREATE DATABASE [name];

Two things here: First, notice how I use uppercase for sql language: this is a good practice since it allows you to understand if it's sql language or not. Second, you need to replace the "[name]" entirely, with square brackets.
List the databases in your computer once more to see if it worked

\l

# How to connect to a database
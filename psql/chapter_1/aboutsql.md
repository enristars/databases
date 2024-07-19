# Introduction to PostgreSQL
## What is PostgreSQL?
According to PostgreSQL.org, PostgreSQL is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads.
What's cool about PostgreSQL is that it can handle really complex data and queries, like if you needed to find specific details from a huge pile of information or combine different data sources. It’s flexible, supports advanced features, and is known for being reliable and secure. Plus, because it's open-source, lots of people can contribute to making it even better!
## Why use PostgreSQL?
PostgreSQL is a powerful and flexible database system that excels at handling complex data and advanced queries. It supports features like JSON data types, custom functions, and full-text search, making it ideal for sophisticated data management. Known for its reliability and performance, PostgreSQL can handle large data loads efficiently. Being open-source, it’s free and constantly updated by a global community. Its adherence to SQL standards simplifies usage, and its extensibility allows for custom enhancements. Overall, PostgreSQL offers a robust solution for both small and large-scale data needs.
## How to get started
You can find a detailed download guide in their website here: https://www.postgresql.org/download/
Ubuntu Linux includes PostgreSQL already, so just type in

apt install postgresql

in your terminal to install it.
There's a detailed breakdown of its installation here: https://www.cherryservers.com/blog/how-to-install-and-setup-postgresql-server-on-ubuntu-20-04

Make sure to follow the fourth step every time you want to use PostgreSQL in your terminal because it initializes the postgresql command line. It is:

sudo -u postgres psql

After this, you can use the "psql" prompt to continue using it.
You can skip the step 5 onwards, as this repo will continue its detailed explanation of it (excluding PostgreSQL server for now).

You're all set now! Time to use it
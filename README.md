# Phamtastic Autos (SQL)
by Tommy Truong

## Purpose:
This project was created to help me familiarize myself with SQL and understanding data distribution.
The server was used to create a distributed data warehouse that handles subscriptions and publications between
3 different warehouses (live, report and product), which ensures that data won't be lost if any system fails.

## Files:
This repo contains the stored SQL procedures to scrape the automobile dataset and insert it into Microsoft SQL Server 2008 R2's database.
The relational model is established within the server.

The dataset contains 95 entries regarding automobile metadata and the services that were performed on them.

# retail


I downloaded a dataset named "orders.csv" from Kaggle using the Kaggle API, extracted it from a ZIP file, and then read it into a Pandas DataFrame. After handling null values and making some transformations, I converted the DataFrame to lowercase column names, and calculated additional columns for discount, sale price, and profit. Finally, I used SQLAlchemy to establish a connection to a PostgreSQL database named "retail" and uploaded the DataFrame as a table named "info" into the database.
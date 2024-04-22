Created mysql server database using aws rds.
Created replication instance of dms and then created source endpoint(mysql) and destionation endpoint(s3 bucket).
Created a s3 bucket where the full load and data change capture files are uploaded.
Uploaded tables in the database and queryed. These changes of full load were replicated and updated as a file in s3 bucket.
Later made few insertions, updations and deletions in the database so the same was replicated in the s3 as a file .

# django_blog
👩‍💻 🚧 Work In Progress

# Create database and user  psql :


      Commands

      - list database
      \l
      

      - Create database 
      create database blog;

      - Create user
      CREATE USER blogadmin WITH ENCRYPTED PASSWORD 'passwrd';
      ALTER ROLE blogadmin SET default_transaction_isolation = 'read committed';

      - asign privileges 
      GRANT ALL PRIVILEGES ON DATABASE blog TO blogadmin;

      -Sortir du schell
      \q

![psql](https://github.com/WissalManseri/django_blog/assets/135167709/108b2e48-afe6-473a-b1d4-255a846bece4)



# java-everything-bagel

## installation 

### Postgres
    brew install postgresql@16

running postgresSql
    
    brew services start postgresql@16
    # to create the databse
    createdb everything-bagel
    # To log in to the database 
    psql everything-bagel
    # to findout your user
    everything-bagel-# \du
    # this seems to be your computer user name by default with the password postgres by deafault
    # This can then be conected in intelliJ with the defult port settings 
    
gradle build
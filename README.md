# freecodecamp-Periodic-Table-Database

The Periodic Table has been stored in a database that can be accessed using a bash script.
<br>
<br>
To start running the script, set up the database using the following command in a bash terminal:
```
psql -U postgres < periodic_table.sql
```
<br>
<br>
After that you have to give the script executable permissions by running this code in a bash terminal:
```
chmod +x element.sh
```
<br>
<br>
Finally, run the elements script by passing in arguments (the element you want to view) after the command:
```
./element.sh 1 
#or
./element.sh H
#or
./element.sh Hydrogen
```
If no argument is passed in, the script simply outputs an error message without crashing.

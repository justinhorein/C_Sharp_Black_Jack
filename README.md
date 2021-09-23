# C_Sharp_Black_Jack

A basic console app game of 21 Black Jack, built in Visual Studio w/ C#.  

### If you want to test it out:
1. Update the connection strings:
- In Program.cs on lines 87 and 112 update: Data Source = !YourServerHere!
2. Create a database on your server named 'TwentyOneGame'.
3. In the database 'TwentyOneGame' create a table named 'Exceptions'.
4. In the table 'Exceptions' create 3 columns:
- ExceptionType: varchar(50)
- ExceptionMessage: varchar(1000)
- TimeStamp: datetime
5. Now you can run the game!

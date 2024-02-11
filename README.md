RestaurantAPI Setup Instructions

Follow these steps to set up and run the RestaurantAPI:

1. Clone the Repository

2. Configure SQL Server Connection Add your SQL Server database connection details in the appsettings.json file: 
"AllowedHosts": "*",
"ConnectionStrings": 
{ 
"DevConnection": "Server=CYDEX ;Database=RestaurantDB ;Trusted_Connection=True ;MultipleActiveResultSets=True;" 
} 
Replace YOUR_SERVER_NAME, YOUR_USERNAME, and YOUR_PASSWORD with your SQL Server details.

3. Code-First Migration Open the Package Manager Console and run the following command to create an initial migration: : Add-Migration InitialCreate

4. Update Database Apply the migration to update the SQL Server database: Update-Database

5. Input some customer names and food items to the data bases using quire codes

6. Run the Application Start the application to ensure everything is set up correctly.

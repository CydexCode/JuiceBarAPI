RestaurantAPI Setup Instructions

Follow these steps to set up and run the RestaurantAPI:

Clone the Repository

Configure SQL Server Connection Add your SQL Server database connection details in the appsettings.json file: "AllowedHosts": "*", "ConnectionStrings": { "DevConnection": "Server=CYDEX ;Database=RestaurantDB ;Trusted_Connection=True ;MultipleActiveResultSets=True;" } Replace YOUR_SERVER_NAME, YOUR_USERNAME, and YOUR_PASSWORD with your SQL Server details.

Code-First Migration Open the Package Manager Console and run the following command to create an initial migration: : Add-Migration InitialCreate

Update Database Apply the migration to update the SQL Server database: Update-Database

Run the Application Start the application to ensure everything is set up correctly.

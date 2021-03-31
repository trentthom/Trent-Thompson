## Total Time Spent
75 minutes
## Question 1

Hi Bob,

I am sorry to hear of your processing delays.
Fortunately, it can be resolved quite quickly in the following ways:

1 - If this is an urgent issue we can have one of our techs complete a version upgrade straight away.
NOTE - This will require a small outage to complete.

2 - We leave it as is and the issue will be automatically fixed when we deploy the next upgrade next Sunday.

Please advise so we can assist asap.

Regards,

Trent

## Question 2

SELECT Orders.OrderDate, Customers.Country, OrderDetails.Quantity
FROM ((Orders
INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID)
INNER JOIN OrderDetails ON Orders.OrderID = OrderDetails.OrderID)
GROUP BY CustomerName, Country
ORDER BY Country

## Question 3

InstanceName: ABC
TranDb: ONETran$ (InstanceName)
StagingDb: ONEStaging$ (InstanceName)
ArchiveDb: ONEArchive$ (instanceName)
InstallFeatures:
	- Database
	- Application
	- Services
Settings:
ExplicitUPNMappingEnabled: 1
HostingType: 2
UserCultureDefault: en-US
UserCulturesAvailable: “en-AU,en-US”
SendNotificationEmails: 1
SlicerGenerationMode: 3
SysCurrency: USD

## Question 4

It appears as though the last line of the CSV file is incomplete, which would be enough to throw an error.

I tested this out on https://www.w3schools.com/sql/sql_insert.asp using this data:

INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal','Tom B. Erichsen','Skagen 21','Stavanger','4006');

As the Country VALUE isn't present it threw an error.

# sqlCheckpoint

For Submission:
Complete each of the following challenges, and take a screenshot of each query in your command line and the returned data, and add the screenshot to your repo README.md under a corresponding challenge label.

To Begin:
[/] Create a database called vacations
[/] Create a table called destinations and populate it with each location's id, name, average_temp, has_beaches, has_mountains, and cost_of_flight.
[] Create a table called airlines and populate it with each airline's name and id.

Challenges:

[/] All of the vacation destinations.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139325296-648b932f-0f81-4fb9-92dc-c3f48d237b82.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[/] All destinations where you can swim at the beach.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139326142-91018322-d714-4fc8-b793-1ac4fd02ec10.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[/] All destinations where the average temperature is over 60 degrees.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139326807-38956183-28e6-4fea-b5ae-e168de140e53.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[/] All destinations where you can swim at the beach AND go to the mountains.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139327197-13ff4849-e716-40c4-b391-6d9d645ed4b8.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[/] All destinations where flights cost less than $500 and you can hike in the mountains.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139327599-1dce935e-5aaa-498c-a5ca-3a873bd8175f.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[/] Add an entry for The Bahamas, where the average temperature is 78, it has beaches but no mountains, and the flights cost $345.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139327903-3583d68b-40dd-4a93-bd1a-69af512f0c1d.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[] Turns out, the cost of flights to New Zealand has increased! Update New Zealand's entry for flight cost to $1000.

Query and Result:

![image](https://user-images.githubusercontent.com/27661560/139328345-f185579f-1d76-4564-aeea-51948e4394f3.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------

[] Turns out, Minnesota isn't a vacation destination. Please delete it from the database.

Query and Result:



-------------------------------------------------------------------------------------------------------------------------------------------------------

[] When the data set was written, the author mistakently wrote "England" when they actually meant "Scotland". Please update that entry in the database.

Query and Result:



-------------------------------------------------------------------------------------------------------------------------------------------------------

[] Create a join table that joins the airlines and the destinations tables by correlating which airlines fly to which destinations.

Query and Result:



-------------------------------------------------------------------------------------------------------------------------------------------------------

[] All airlines that fly to New Zealand.

Query and Result:



-------------------------------------------------------------------------------------------------------------------------------------------------------

[] All airlines that do NOT fly to Scotland.

Query and Result:



-------------------------------------------------------------------------------------------------------------------------------------------------------

[] All of the data for all vacation destinations.

Query and Result:




-------------------------------------------------------------------------------------------------------------------------------------------------------

Vacation Destination Data:

[
    {
        name: "Thailand",
        average_temp: 82,
        cost_of_flight: 765,
        has_beach: true,
        has_mountains: true
    },
    {
        name: "Minnesota",
        average_temp: 41,
        cost_of_flight: 235,
        has_beach: false,
        has_mountains: false
    },
    {
        name: "New Zealand",
        average_temp: 66,
        cost_of_flight: 433,
        has_beach: true,
        has_mountains: true
    },
    {
        name: "England",
        average_temp: 45,
        cost_of_flight: 290,
        has_beach: false,
        has_mountains: false
    },
    {
        name: "Tristan da Cunha",
        average_temp: 59,
        cost_of_flight: 1304,
        has_beach: true,
        has_mountains: true,
    }
]
Airline Data:

[
  {
    name: "Spirit",
    destinations_flown_to: ["New Zealand", "Scotland"]
  },
  {
    name: "Lufthansa",
    destinations_flown_to: ["Tristan da Cunha", "Scotland", "Thailand"]
  },
  {
    name: "Delta",
    destinations_flown_to: ["Thailand", "Minnesota", "England", "Scotland"]
  },
  {
    name: "Southwest"
    destinations_flown_to: ["New Zealeand", "Tristan de Cunha", "Minnesota"]
  }
]

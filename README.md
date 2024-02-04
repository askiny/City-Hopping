# City-Hopping

For this project I used Open Flight Data provided by openflights.org. I worked on finding the shortest route between two places and creating dynamic network maps.

# Subjects

- I pulled airport and route data and combined these two data sets so that there was no data loss.

- Found the flight routes with the minimal number of stops for the following source and target cities. For example, a route that has the minimal number of connections/stops from Antalya to Deer Lake (Canada) is Antalya, London, Halifax, Deer Lake.

From Adana (Turkey) to Auckland (New Zealand)
From Ankara (Turkey) to Kona (Hawaii, USA)
From Sydney (Australia) to Churchhill (Canada)

- Using the networkx's implementation of the Page Rank Algorithm find the top 10 cities that are important for the global flight network.

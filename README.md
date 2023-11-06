# Dijkstra-Bus-Travel-Optimizer

This Java program utilizes Dijkstra's algorithm to help you find the minimum amount of time needed to reach each bus station in a location. With multiple buses and stations, the program optimizes your travel by identifying the most efficient routes.


## Introduction

There are N bus stations and M buses provide service in Ankara Kızılay. Each bus s has a
schedule consisting of t stations. At the beginning, each bus at their first station and each minute
it travels to the next station. When it reaches the end, it goes back to the beginning and starts again.
At the beginning, you are at station 1. If at any moment you and a bus are at the same station, you
can get on it and travel with it. You can get off the bus at any station. The same station can appear
multiple times in the itinerary of the bus, but not adjacent to each other (in particular the last station is adjacent to the first one). You are interested in finding the minimum amount of time you need
to reach to each station, or state that it is impossible.

## Features

- Dijkstra's algorithm for finding the minimum travel time to each bus station.
- Support for multiple buses, stations, and schedules.
- Effortless travel optimization by selecting the most efficient bus routes.
- Clear and extensible Java codebase.

## Getting Started

1. Clone this repository to your local machine.

2. Compile and run the Java program using your preferred Java development environment.

3. Follow the prompts to input the necessary parameters and calculate the minimum travel time.

## Usage

To use the Dijkstra-Bus-Travel-Optimizer, follow these steps:

1. Run the Java program.

2. Input the number of stations (N) and buses (M).

3. Define the schedules for each bus, specifying the number of stations they visit.

4. The program will calculate and display the minimum travel time to reach each bus station.

## Input Format

In the input, the first line contains 2 space separated integers, N, M. N denotes the number
of stations, M denotes the number of buses respectively. Each of the next M lines contain an integer
t followed by t integers which demonstrate the schedule of each bus.
In the given sample input, it is given that we have 8 stations, and 4 buses work between
them in the first line. The next lines give the schedule of each bus with the number of stations it
visits and which stations it visits. For example, the second bus has 3 stations 6, 1 and 2. Buses visit
the stations according to the given order, so the second bus is in the 6th station at the beginning,
then it goes to the 1st station and then 2nd station and returns to the 6th station. And, traveling
between each station takes 1 minute, so it takes 2 minute for the second bus to go from 6th station
to 2nd station.


<img width="955" alt="Screenshot 2023-11-06 at 20 15 06" src="https://github.com/sarparslan/Dijkstra-Bus-Travel-Optimizer/assets/96438389/3866a8de-441f-4703-9b06-ab4c64befa18">



## Output Format

In the output, program is printing N-1 space separated integers denoting the minimum amount of time
needed to reach each station except the 1st station since we are at the first station at the
beginning. If any of the stations is not reachable with the given schedule of the buses, program is printing
 -1 for that station. Also program prints the output in numerical order.

<img width="955" alt="Screenshot 2023-11-06 at 20 15 16" src="https://github.com/sarparslan/Dijkstra-Bus-Travel-Optimizer/assets/96438389/d1481a26-5463-44cf-983d-be60441b4f49">


# BetaCrew Client

BetCrew client is a C# console application capable of requesting and receiving stock ticker data from the BetaCrew exchange server.

## Features of the Client
- Makes a TCP request to the BetaCrew exchange server to get stock ticker data.
- Handles any missing data that is lost during the transmission

## Requirements
- Node JS (16.17.0 or higher)
- Visual Studio 2022 or any C# compiler

## Steps to run the Client on local machine
- Clone the repository and navigate to BetaCrewFinal folder
- Download and install Node JS and make sure the path is added to the system environment.
- Download and install Visual Studio 2022 or C# compiler.
- Run the command "node main.js" in a terminal. The BetaCrew Exchange Server is now running.
- Open the project in Visual Studio code and Run. An alternative is to compile and run the Program.cs file using a C# compiler.

## Output generated by the Client
- The "output.json" file is generated after executing the program successfully consisting of an array of objects, where each object represents a packet of data with increasing sequences.
- Cross verify the content of "output.json" file with that of "sample.json" file (sample output generated).

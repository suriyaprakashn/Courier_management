# Courier Management System - FastTrack

## Project Overview
This project is a Courier Management System for 'FastTrack' courier company, designed to manage shipment and client information efficiently. The system stores data in dictionary structures and provides various functionalities to query and analyze shipment details.

## Data Structures

### 1. Shipment Dictionary
The system uses a dictionary where:
- Key: Shipment ID
- Value: List of attributes including:
  - Sender (client ID)
  - Receiver (client ID)
  - Start date
  - Delivery date
  - Sender location
  - Receiver location
  - Delivery status
  - Shipping cost

### 2. Client Dictionary
The system maintains a client dictionary where:
- Key: Client ID
- Value: Client name

## Functionality

### Create Shipment Dictionary
A dictionary of lists to store shipment information with shipment ID as key and attributes as values.

### Create Client Dictionary
A dictionary to store client information with client ID as key and client name as value.

### Replace Client IDs with Names
Code to replace client IDs with their respective names in the shipment dictionary using loops and dictionary comprehension.

### Shipments Sent by Phillip
Functionality to print all shipment details sent by a specific client (Phillip).

### Shipments Received by Ramya
Functionality to print all shipment details received by a specific client (Ramya).

### In-Transit Shipments
Functionality to print all shipments with 'In-Transit' status.

### Fast Deliveries (Within 7 Days)
Functionality to print all shipments delivered within 7 days of the courier start date.

### Delayed or Undelivered Shipments
Functionality to print all shipments delivered after 15 days of the start date or not yet delivered.

### Find All Possible Routes
Implementation of a function `find_all_routes()` to display all possible routes from sender's location to receiver's location using graph traversal algorithms.

## Graph Representation
The system uses a matrix representation to model the network of pickup and delivery nodes:
- 1 represents a direct route between two nodes
- 0 represents no direct route between nodes

The graph is bidirectional, meaning if there's a route from node A to node B, there's also a route from node B to node A.

## Implementation Details
The system will:
1. Initialize the shipment and client dictionaries with sample data
2. Implement all query functionalities
3. Implement graph traversal algorithms to find all possible routes
4. Provide clear output for each query

## Usage
To use this system:
1. Initialize the dictionaries with your data
2. Call the appropriate functions to get the desired information
3. Use the route finding function to determine all possible paths between locations

## Example Output
The system will provide formatted output for each query, showing relevant shipment details or possible routes between locations.

## Dependencies
This project requires only Python standard libraries, with no external dependencies.

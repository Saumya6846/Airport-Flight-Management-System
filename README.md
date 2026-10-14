AeroFlow ATOS — Airport Flight Management System

AeroFlow ATOS (Airport Traffic & Operations Simulator) is a web-based educational project that demonstrates how Data Structures and Algorithms (DSA) can be applied to airport and flight-management workflows. It brings together simulated flight operations, flight search and booking, passenger records, airport connections, and interactive DSA demonstrations in one interface.

Academic project notice: AeroFlow ATOS is a learning simulation. It uses sample data and does not connect to real airline or airport systems, issue real tickets, or process actual payments.

Features

Operations Overview — a dashboard for viewing available operational summaries.

Flight Management — view, search, filter, sort, and manage flight records.

Flight Booking — search sample flights, enter passenger details, select seats, view simulated fares, and manage bookings.

Booking Cancellation — cancel eligible simulated bookings and update associated booking/seat records according to the app's implemented rules.

Passenger Manifest — view and organize passenger information associated with flights or bookings.

Gate and Runway Control — demonstrate resource allocation and scheduling-conflict checks.

Departure Queue — demonstrate FIFO processing and priority-based handling.

Airport Network — represent airport connections as a graph and explore routes.

DSA Laboratory — demonstrate selected data structures, searching, sorting, and graph algorithms.

Local Persistence — supported records can be saved in the browser using localStorage.

The available features depend on the current implementation. Remove or edit any item above that is not present in your submitted version.

Data Structures and Algorithms

The project is designed to demonstrate the following concepts where implemented:

Concept

Example use in the project

Arrays

Store and display flight or booking records

Stacks

Demonstrate last-in, first-out operations

Queues

Simulate departure processing using FIFO order

Linked lists

Demonstrate sequential data organization

Trees / BST / AVL trees

Demonstrate hierarchical organization and tree operations

Heaps / Priority queues

Simulate priority-based processing

Hash tables

Demonstrate key-based lookup

Graphs

Represent connections between airports

BFS and DFS

Traverse an airport network

Dijkstra's algorithm

Find a shortest route in a weighted airport graph

Searching and sorting

Retrieve and organize records

Only claim algorithms in your project report if they have actually been implemented and tested in the application.

Technology Stack

Frontend: React, TypeScript, HTML, CSS

Development and build tool: Vite

Package manager: npm

Version control: Git and GitHub

Browser storage: localStorage for supported records

Testing: Vitest, if configured in the project

Getting Started

Prerequisites

Install the following on your computer:

Node.js (includes npm)

Git (optional, for cloning the repository)

A modern web browser

Installation

Clone this repository:

git clone <YOUR_GITHUB_REPOSITORY_URL>

Move into the project folder:

cd <YOUR_PROJECT_FOLDER>

Install dependencies:

npm install

Start the local development server:

npm run dev

Open the local URL printed in your terminal (Vite commonly uses http://localhost:5173).

Build for Production

npm run build

To preview the production build locally, run:

npm run preview

If the scripts differ in your project, check the scripts section of package.json and use the commands listed there.

Screenshots

Add screenshots of your actual running application here. For example:

Operations dashboard

Flight search results

Flight booking and seat selection

My Bookings / cancellation

Airport network or DSA Laboratory

You can place images in a folder such as screenshots/ and display one using Markdown:

![Operations Dashboard](screenshots/dashboard.png)

Project Structure

The exact structure may differ depending on your implementation. A typical Vite project includes files such as:

project-folder/
├── public/
├── src/
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md

Limitations

Flight schedules, routes, passenger records, and fares are simulated sample data.

The project does not connect to live airline data or operational airport systems.

Browser localStorage is local to the browser and is not a shared multi-user database.

No real payment gateway or real ticket issuance is provided.

Future Enhancements

Integrate a database and secure backend API.

Add authentication and role-based access control.

Add richer reports and operational analytics.

Improve input validation and automated test coverage.

Integrate an external flight-data source only if suitable access and permissions are available.

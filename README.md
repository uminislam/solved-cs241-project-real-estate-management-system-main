Download Link: https://assignmentchef.com/product/solved-cs241-project-real-estate-management-system-main
<br>
<h1></h1>

<ul>

 <li>Read the entire description before you begin your work.</li>

 <li>The specifications given are from end-users, so they may not be precise and complete. State all your assumptions in your deliverables.</li>

</ul>

<h1>2         PROJECT DESCRIPTION</h1>

A DBMS needs to be implemented for a real estate office, that sells houses and apartments within a city. The office needs to store a lot of data, specifically:

<ul>

 <li>agents: An agent is responsible for interacting with buyers and sellers, to show properties to them and facilitate sales or giving on rent.</li>

 <li>details of homes/apartments: The address, selling price, rent, details of the house (example: size: 1500 sq. ft, number of bedrooms: 2)</li>

</ul>

3       DATA GENERATION

You can see magicbricks.com, 99acres.com, makaan.com etc. for good examples of data.

<h1>4        PROJECT REQUIREMENTS</h1>

(1) E-R Model

<ul>

 <li>Construct an E-R diagram representing the conceptual design of the database.</li>

 <li>Be sure to identify primary keys, relationship cardinalities, etc.</li>

</ul>

(2) Relational Model

<ul>

 <li>After creating an initial relational design from your E-R design, refine it based on the principles of relational design.</li>

 <li>Create the relations in MySQL.</li>

 <li>Create indices (indices will be taught later) and constraints as appropriate.</li>

 <li>If, as you refine your design, you discover flaws in the E-R design, go back and change it (even if the earlier design passed the checkpoint.) Your final E-R design must be consistent with your relational design.</li>

</ul>

(3) Populate Relations

(a) Include enough data to make answers to your queries interesting and nontrivial for test purposes.

(4) Queries: Run enough queries to ensure that your database is populated the way you intended it to be. Given below are the queries that you must demonstrate. You may be asked to demonstrate additional queries.

<ul>

 <li>Find addresses of homes in your city (for example Guwahati) with rent between Rs.20,000 and Rs. 40,000 per month.</li>

 <li>Find details of homes for rent in G.S.Road (you can use the name of another locality if your city is different) with at least 2 bedrooms and costing less than Rs.10,000 per month. Show the contact number(s) of agents who can show you these properties.</li>

</ul>




<ul>

 <li>Find the name of the agent who has sold the most property in the year 2021 by total amount in rupees.</li>

 <li>Find the addresses of homes in your city that are available for sale and that has at least 2 bed rooms. List the asking price and the number of bedrooms, with other details that may be necessary.</li>

 <li>List the details of the most expensive houses and the houses with the highest rent, in the database.</li>

</ul>

(5) Interfaces: There are two types of users who access the database. Each may need a different interface:

<ul>

 <li>The database administrator (you) may use SQL via the command line.</li>

 <li>The real estage agent’s office, to get 1) sales reports for each agent, consisting of the sale dates, property details and selling price and 2) how many properties have been given on rent by each agent for what amount, in which area, when.</li>

 <li>Agents, to update the database when a property is rented or sold.</li>

</ul>

These interfaces can be built as 1) Web applications using Java applets or a scripting language. 2) A standalone

Java application using Swing to create a GUI 3) A standalone Java application with a command line interface 4) Any other GUI tool you may know

(6) Concurrency: The database must support more than one agent accessing the database at a time along with someone from the real estate office. Make sure that the required guarantees are provided.

<h1>                5       DELIVERABLES</h1>

For each deliverable, the contribution of each team member must be stated. If a person’s contribution is not stated, it will be assumed that that person has not contributed.

The last date for each item is as given below:

<ul>

 <li>ER diagram, with assumptions, in a document – March 25, 2021 (maximum two pages)</li>

 <li>Relational design, user interfaces and their features, in a document – April 1, 2021 (Provide the SQL tables and their primary and foreign keys)</li>

 <li>Interface for the database administrator with all the queries working, as demo – April 8, 2021.</li>

 <li>Interface for real estate office and agents, as demo – April 15, 2021.</li>

</ul>

For items 3 and 4 above, students may be randomly chosen and asked to send their working data and code so that TAs can install and evaluate the solutions. You may also be asked to create videos of less than 10 minutes to assist in evaluating your work.
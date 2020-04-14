# Database Normalization
  - Database normalization is a process used to organize a database into tables and columns.  
  - The main idea with this is that a table should be about a specific topic and only supporting topics included. 

### where the data contains salespeople and customers serving several purposes:
  - Identify salespeople in your organization
  - List all customers your company calls upon to sell a product
  - Identify which salespeople call on specific customers.


## The first thing to notice is this table serves many purposes including:

  - 1. Identifying the organization’s salespeople
  - 2. Listing the sales offices and phone numbers
  - 3. Associating a salesperson with an sales office
  - 4. Showing each salesperson’s customers


## Duplicated information presents two problems:
  - 1. It increases storage and decrease performance.
  - 2. It becomes more difficult to maintain data changes.

# Definition of Database Normalization
   - **let’s summarize the various forms:**
      - First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
      - Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
      - Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key
# Project: Database Analysis and Assessment Output

## Description
This project focuses on analyzing an SQLite database using Python, generating insights, and answering specific queries based on provided instructions. The project includes both SQL and Pandas-based approaches for each query, providing flexibility and demonstrating analytical capabilities.

## Structure
```
project/
├── assets/
│   ├── ERD.png             # Entity Relationship Diagram
│   ├── Interview Challenge.pdf  # Challenge instructions
├── analysis.ipynb          # Jupyter Notebook for interactive analysis
├── database.db             # SQLite database file
├── README.md               # Project documentation (this file)
```

## Requirements
The project requires the following libraries:
- Python 3.x
- pandas
- sqlite3 (standard library)
- tabulate

To install the required libraries:
```bash
pip install pandas tabulate
```

## Features
### Key Functionalities:
1. **Analyze Database**: Lists all tables, schemas, and record counts in the SQLite database.
2. **Answer Specific Queries**:
   - Determine if the database is a Snowflake schema or a Star Schema.
   - Identify the number of distinct customers.
   - Find the genre with the shortest average track length.
   - Identify the artist appearing most in playlists.
   - Count customers who spent more than $40.
   - Find the most frequently used key.

## Instructions
### Running the Notebook
1. Open the `analysis.ipynb` file in Jupyter Notebook.
2. Execute the cells interactively to view results and explore the database.

### Output Format
All outputs are displayed as formatted tables for clarity.

## GitHub Submission
1. Push the project to a public GitHub repository.
2. Create a pull request with **'ericcoker'** as a reviewer for feedback.

## Example Outputs
### Table Analysis Example:
```
+----------------+---------------+-------------------------------------------+
| Table Name     | Record Count  | Schema                                    |
+----------------+---------------+-------------------------------------------+
| customers      | 59            | [('CustomerId', 'INTEGER'), ... ]        |
| invoices       | 412           | [('InvoiceId', 'INTEGER'), ... ]         |
+----------------+---------------+-------------------------------------------+
```

### Query Results Example:
**Genre with Shortest Average Track Length**
```
+----------+----------------------+
| Genre    | Avg Length (Minutes) |
+----------+----------------------+
| Rock     | 3.45                 |
+----------+----------------------+
```

## Author
Prepared by Gladys Isabel Umayam, as part of the assessment task.

For any questions, feel free to reach out via GitHub Issues in the repository.
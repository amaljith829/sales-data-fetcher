# Sales Data Fetcher

This script fetches sales data from an API and stores it in an SQLite database.

## Requirements
- Node.js installed
- SQLite installed 
- Git installed

## Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/sales-data-fetcher.git
   cd sales-data-fetcher

2.Install dependencies:
npm install

3.Create a .env file in the root directory and add:
API_URL=your_api_url_here

4.Run the script:
node script.js

5.To view stored data in SQLite:
sqlite3 sales_data.db "SELECT * FROM sales_data;"

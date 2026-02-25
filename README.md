📡 API Test Project (Postman + Newman)

This project contains API tests exported from Postman and executed via Newman.

📁 Project Structure
.
├── paylocity_testing.postman_collection.json
├── environment.json 
├── package.json
├── README.md
└── reports/                     # generated test reports


📦 Requirements

Node.js (v16 or higher recommended)
npm


🚀 Installation

Install project dependencies:

npm install


▶️ Running Tests

Run the Postman collection:

npm run api-test


📊 Generating HTML Report

Run tests with HTML report:

npm run api-test:report

After execution, open the report:

reports/report.html
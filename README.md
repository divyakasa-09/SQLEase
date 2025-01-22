# SQLEase

## Project Overview
SQLEase is a user-friendly, Text-to-SQL application designed to enable restaurant managers to query relational databases using natural language. This application leverages GPT-powered Large Language Models (LLMs) and integrates with advanced cloud data platforms such as Databricks and Snowflake to provide efficient and reliable query generation, optimization, and execution. 

## Key Features
- **Natural Language to SQL Translation**: Converts user input into optimized SQL queries, simplifying access to restaurant information.
- **Dynamic ERD Diagram Generation**: Generates interactive Entity Relationship Diagrams (ERDs) for schema exploration.
- **Error Handling and Feedback Loops**: Implements robust mechanisms to validate and self-correct SQL queries.
- **Streamlined Deployment**: Secure deployment on AWS EC2 with HTTPS.
- **Interactive UI**: Built using Streamlit for an intuitive user experience with features like Quick Analysis, Deep Dive Analysis, and Favorites.

## Technologies Used
- **Programming Language**: Python 3.10
- **Frameworks**: Streamlit, LangChain
- **Cloud Platforms**: AWS (EC2), Databricks, Snowflake
- **LLMs**: OpenAI GPT-4
- **Other Tools**: YAML, dotenv, Mermaid.js

## Data Description
The database used in this project supports a comprehensive food delivery application, capturing detailed information about users, restaurants, menu items, orders, payments, and reviews. This structured dataset enables restaurant managers to analyze operations and optimize business performance.

### Dataset Details
- **Users**: Information about users of the food delivery service.
- **Restaurants**: Data on listed restaurants, including their details and cuisine types.
- **Menu Items**: Details of menu items offered by restaurants.
- **Orders**: Records of orders placed by users, including their status and details.
- **Order Details**: Specifics about items in each order.
- **Payments**: Information on payments, including methods and statuses.
- **Reviews**: User reviews and ratings for restaurants and orders.

## Why Databricks and Snowflake?
- **Databricks**: Provides scalable query execution and schema management, ideal for handling complex datasets with high performance.
- **Snowflake**: Offers efficient, cloud-based data storage and retrieval, ensuring reliability and scalability for analytical workloads.


## Deployment Instructions
1. **Virtual Environment Setup**:
   - Create and activate a Python virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # For macOS/Linux
     .\venv\Scripts\activate  # For Windows
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
2. **Run the Application**:
   ```bash
   streamlit run SQLEase.py
   ```
   - Access the app at the provided URL (e.g., `http://localhost:8501`).

3. **Secure Deployment on AWS EC2**:
   - Configure EC2 instance with HTTPS and deploy the application for scalable, secure access.

## Takeaways
- Learned to integrate LLMs with databases for natural language processing.
- Developed expertise in using Databricks and Snowflake for scalable data management.
- Implemented dynamic visualizations, user authentication, and robust error handling.
- Deployed a secure, scalable application leveraging AWS cloud infrastructure.


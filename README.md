# YouTube-Data-Harvesting-and-Warehousing-using-SQL-and-Streamlit
YouTube-Data-Harvesting-and-Warehousing-using-SQL-and-Streamlit

This project involves creating a tool that fetches data from YouTube using various technologies, primarily Python, Google API, SQL, and Streamlit.  Here's a breakdown of the main components and how they work together:

1. **Data Fetching:**
   - The tool uses Python and the Google API to fetch data from YouTube.
   - You'll need to set up the Google API client in your Python environment to access YouTube data.

2. **Data Warehousing:**
   - The fetched data is stored in a SQL database for efficient querying and analysis.
   - To populate the database, you enter YouTube channel IDs in the data warehousing section of the tool. 

3. **Streamlit Application:**
   - Streamlit is used to create a user-friendly interface for the tool.
   - The application is launched through the command prompt. For example:
     ```
     streamlit run your_app_name.py
     ```

4. **Query Section:**
   - Once data is populated in the database, the query section automatically displays results.
   - The tool includes predefined queries (typically around 10) that users can select from. 
   - These queries use SQL join operations to combine data from different tables and provide comprehensive results. 

5. **Data Processing:**
   - The tool processes the entered channel IDs, removing any extra spaces to ensure accurate data fetching and storage.
   - It can handle multiple channel IDs, allowing you to populate the database with data from various YouTube channels.

To implement this project, you'll need to:

1. Set up a Python environment with necessary libraries (Streamlit, Google API client, SQL database connector).
2. Create a Streamlit application that serves as the user interface.
3. Implement functions to fetch data from YouTube using the Google API.
4. Set up a SQL database and write functions to store and retrieve data.
5. Create SQL queries to analyze the stored data.
6. Use Streamlit components to display query results and allow user interaction.

Remember to handle API rate limits, error cases, and data validation to ensure your tool runs smoothly and efficiently.

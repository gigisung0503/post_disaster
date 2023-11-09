# Post Disaster
GIS tool for post disaster interventions

Our plan:
-Streamlining the process by leveraging the Streamlit package for frontend development

Here's are the steps to follow. We will cross off as we complete each task:

### A. Planning Phase

1. **Define Application Scope:**
   - Narrow down the most essential features given the time constraints.
   - Focus on the minimum viable product (MVP) that provides value.

2. **Requirements Analysis:**
   - List down the must-have features and deprioritize nice-to-haves.
   - Identify the satellite imagery data sources and their access protocols.

3. **Research:**
   - Select the best tools for raster data analysis compatible with Streamlit and Python.
   - Explore how to use Streamlit for displaying satellite images and results.

4. **Database Design:**
   - Finalize a simple yet effective database schema.
   - Choose PostgreSQL with PostGIS extension for handling spatial data.

5. **Technology Stack Selection:**
   - Decide on backend technology (likely Python to synergize with Streamlit).
   - Select additional libraries for data handling and computation (e.g., Pandas, NumPy, GDAL).

### B. Development Setup

6. **Environment Setup:**
   - Prepare your development environment with Python, Streamlit, database, and other tools.
   - Initialize a Git repository for version control.

7. **Database Setup:**
   - Install PostgreSQL and PostGIS.
   - Apply the initial database schema and test connections.

8. **Backend Development:**
   - Create a Python environment for your backend logic.
   - Implement core backend functionalities including the API to fetch and process imagery.

### C. Development Phase

9. **Streamlit Frontend Development:**
   - Use Streamlit to build out the user interface.
   - Implement the necessary inputs, outputs, and data displays for your application.

10. **Integration with Satellite Imagery:**
    - Integrate the APIs to pull satellite imagery from external sources.
    - Establish a caching mechanism if needed to optimize performance.

11. **Raster Data Analysis:**
    - Utilize Python libraries to analyze satellite imagery.
    - Develop and integrate analysis algorithms or models within the Streamlit app.

12. **Local Testing:**
    - Test the functionalities of your app locally.
    - Ensure the Streamlit app communicates effectively with the backend and database.


-By following this adjusted process, we should be able to create our MVP within the two-month timeframe. 
-Remember to build in small increments, test frequently, and iterate based on the results. 

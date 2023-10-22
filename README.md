#### Summary
This code demonstrates how to build an interactive Python dashboard application using Streamlit and Plotly. The application allows users to upload and filter data, view different charts and plots, perform time series analysis.

#### Highlights
- Demonstrates how to import the necessary libraries, including Streamlit and Plotly
- Sets the title and icon for the dashboard application using `st.set_page_config()`
- Allows users to upload a dataset using `st.file_uploader()`
- Creates a date picker for selecting a specific period of data
- Implements side filter panes for filtering data based on reason, state, and city
- Creates a column chart to visualize category-wise sales
- Visualizes data using a treemap based on reason, category, and subcategory
- Generates pie charts to display sales by segment and category
- Presents time series analysis using a line chart
- Displays data in a table format using `st.dataframe()`
- Allows users to download data as CSV files using `st.download_button()`
- Provides an expandable view of the data using `st.expander()`
- Creates scatter plots to show the relationship between sales and profit
- Implements dark mode theme using `st.set_theme()`

**Technical Details**
- Libraries used: Streamlit, Plotly, Pandas, OS
- Key functions used: `st.set_page_config()`, `st.file_uploader()`, `st.date_input()`, `st.sidebar.multiselect()`, `pd.read_csv()`, `st.markdown()`, `st.download_button()`, `st.expander()`, `px.bar()`, `px.pie()`, `px.scatter()`, `ff.create_table()`, `st.dataframe()`
- Techniques used: Data filtering, data visualization, time series analysis, data manipulation, table creation.

##### Author:
- Jazay Ahmad

# YouTube Data Harvesting and Warehousing Project

The YouTube Data Harvesting and Warehousing Project is an interactive dashboard designed to empower users to explore and analyze data from multiple YouTube channels effortlessly. Whether users are content creators, marketers, or analysts, this tool provides valuable insights to inform their decisions and strategies.

## Check it out now ! youtubedatawarhouse.streamlit.app

## Features

- **Retrieve Channel Data:** Users can enter a YouTube channel ID to access essential metrics such as channel name, subscriber count, total video count, playlist ID, video ID, likes, dislikes, and comments for each video.
- **Store Data in MongoDB:** Seamlessly store channel data in a MongoDB data lake, ensuring efficient management of unstructured and semi-structured data.
- **Intuitive Data Visualization:** Utilize Streamlit's data visualization capabilities to create interactive charts and graphs, enabling easy interpretation and analysis of the retrieved data.

## Get Started

1. Clone the repository:

   ```bash
   git clone https://github.com/selshiyaxavier/YouTube_data_analaysis.git   
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:

   ```bash
   streamlit run Youtube.py
   ```

4. Navigate through the menu options to explore the various functionalities of the dashboard:
   - **Fetch and Export Data:** Retrieve channel data using unique channel IDs or YouTube links. Store the data in MongoDB and migrate it to a SQL database.
   - **Channel Analysis:** Explore YouTube channel trends and compare channel details stored in the database.
   - **Video Analysis:** Analyze video statistics stored in the database and compare video performances.

## About the Project

The project leverages Streamlit, Google API, MongoDB, and SQL databases to deliver a seamless and intuitive user experience for YouTube data analysis. Designed with simplicity and functionality in mind, the dashboard empowers users to make informed decisions based on comprehensive channel insights.

## Contributions

Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

## Credits

- This project uses Streamlit for the interactive web application.
- Data retrieval is facilitated by the YouTube Data API.
- Data storage is managed using MongoDB database.
- Data analysis and visualization are performed using Pandas and Matplotlib.

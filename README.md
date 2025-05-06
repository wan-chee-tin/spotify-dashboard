## 📖 Project Overview
The Spotify Dashboard is an interactive data visualization tool created using Power BI to analyze user engagement and streaming behavior on Spotify. This dashboard aims to provide valuable insights into listening habits, popular tracks, albums, and artists, helping users better understand trends and patterns over time. By visualizing metrics like total albums played, most-streamed tracks, user preferences across platforms (desktop, mobile, smart speakers), and listening habits on weekdays vs weekends, the dashboard enables users to identify shifts in engagement and optimize content strategies. This project makes use of Spotify streaming data, sourced from a Kaggle dataset, to track listening behavior on an individual and aggregated level. The goal is to demonstrate how data visualization can provide actionable insights into music consumption, improving decisions related to marketing campaigns, content creation, and user experience.

🚀 How to Run
Before using the dashboard, ensure that you have the following tools and software installed:
1. Power BI Desktop: The primary tool for viewing and interacting with the dashboard. You can download it from the official Power BI website.
2. Microsoft Excel: Used to read the Spotify data.

To get this project up and running on your local machine, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Raxeira/spotify-dashboard.git
   cd spotify-dashboard
2. The `Spotify History.csv` dataset is already included in the `Data/` folder for convenience, so you can download and use it straightaway. If you encounter any issues with the included file, you can manually download and replace the dataset from [Spotify Streaming History](https://www.kaggle.com/datasets/sgoutami/spotify-streaming-history/data).
3. Launch the Spotify Dashboard (.pbix) file and explore further.

🔄 Process Flow
The Spotify Dashboard provides a variety of insights based on user engagement with Spotify’s music catalog. Here’s how the process works:
1. Data Ingestion: Spotify listening data is loaded from an Excel file.
2. Data Cleaning & Transformation: Data is cleaned and transformed using Power Query in Power BI to ensure accuracy and consistency.
3. Visualizations: The data is visualized in the form of charts, heat maps, and scatter plots to provide insights into user behavior.
4. User Interaction: Users can filter data by artist, album, time period, or platform to explore specific trends.
5. Insights Generation: Key insights, such as peak listening times, top albums, and year-over-year growth, are displayed in the dashboard.

🛠️ Technologies Used
1. Power BI: The primary tool used to build and visualize the Spotify Dashboard.
2. Excel: Used for storing the Spotify listening data.
3. Power Query: Used to clean and transform the raw data.
4. DAX: Data Analysis Expressions used for creating calculated columns and measures.
5. Kaggle Dataset: Data sourced from Kaggle for analyzing Spotify listening trends.

💡 Key Features
1. Interactive Visualizations: Explore listening trends and key metrics such as albums played, track frequency, and peak listening times.
2. Monthly & Yearly Analysis: Compare user engagement across different time periods (e.g., year-over-year growth).
3. Drill-Down & Drill-Through: Dive deeper into specific data points for more detailed insights.
4. Platform Usage: Identify how users consume music on different devices (desktop, mobile, smart speaker).
5. Peak Listening Times: Visualize when users are most likely to listen to music, using heat maps.

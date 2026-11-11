# 🎵 Music Streaming Analytics Dashboard

## 📌 Project Overview

Music Streaming Analytics is a Power BI dashboard project developed to analyze music tracks and identify patterns in music popularity, genres, artists, and audio features.

The dashboard provides interactive visualizations that help users explore music data and understand different trends through charts and key performance indicators (KPIs).

## 🎯 Objectives

- Analyze music track popularity.
- Identify popular music genres and artists.
- Compare audio features such as Energy, Danceability, and Valence.
- Understand track duration distribution.
- Present insights through an interactive dashboard.

## 🛠️ Technologies Used

- **Power BI** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Calculations and measures.
- **CSV** – Dataset format.

## 📂 Dataset

- **Dataset:** Spotify Tracks Dataset
- **Records:** Approximately 114,000 tracks.
- **Format:** CSV

### Important Columns

- `track_name` – Name of the music track.
- `artists` – Artist name.
- `track_genre` – Music genre.
- `popularity` – Track popularity score.
- `danceability` – Danceability score.
- `energy` – Energy level.
- `valence` – Musical positivity.
- `tempo` – Track tempo.
- `duration_ms` – Track duration in milliseconds.

## ⚙️ Project Workflow

1. **Data Collection:** Imported the music dataset in CSV format into Power BI.
2. **Data Cleaning:** Handled missing values and removed unnecessary columns using Power Query.
3. **Data Transformation:** Converted track duration from milliseconds into minutes and created popularity categories.
4. **DAX Calculations:** Created measures to calculate total tracks, average popularity, total genres, total artists, and average audio features.
5. **Dashboard Development:** Designed an interactive dashboard using KPI cards, charts, and slicers.
6. **Data Analysis:** Analyzed genre popularity, artist contributions, audio features, and track duration patterns.

## 📊 Dashboard Features

- Total Tracks
- Average Popularity
- Total Genres
- Total Artists
- Top Genres Analysis
- Top 5 Artists
- Tracks by Genre
- Audio Features Comparison
- Track Duration Distribution
- Popularity Category Distribution
- Interactive filters for Genre, Artist, and Popularity Category

## 💡 Key Insights

The dashboard helps explore:

- Which genres have higher average popularity.
- Which artists have more tracks in the dataset.
- How audio features vary across music genres.
- How tracks are distributed across duration ranges.
- How tracks are classified by popularity.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` dashboard file.
4. If required, update the CSV dataset file path.
5. Refresh the data.
6. Explore the interactive dashboard using slicers and charts.

## 📁 Project Structure

```text
Music-Streaming-Analytics/
│
├── Dataset/
│   └── dataset.csv
│
├── Dashboard/
│   └── Music_Streaming_Analytics.pbix
│
└── README.md
```
## 👩‍💻 Developed By

**K. Geetha**

Project: Music Streaming Analytics  
Tool: Microsoft Power BI

---

*Turning music data into meaningful insights through interactive visualizations.* 🎶

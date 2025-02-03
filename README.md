# Spotify Listening Analysis Dashboard 🎵📊

## 📌 Introduction
A comprehensive Tableau dashboard analyzing Spotify listening patterns using real user data, providing insights into music consumption, artist preferences, and platform usage.

## ❓ Problem Statement
- What are users' listening patterns across different platforms?
- Which tracks and artists are most popular?
- How do users interact with tracks (skip, shuffle, etc.)?
- What causes users to start or end tracks?

## 📂 Dataset Structure
Single table containing:
- `spotify_track_uri`: Unique identifier for tracks
- `ts`: Timestamp of the activity
- `platform`: Listening platform (web player, android, iOS, etc.)
- `ms_played`: Duration played in milliseconds
- `track_name`: Name of the track
- `artist_name`: Name of the artist
- `album_name`: Name of the album
- `reason_start`: Why the track started
- `reason_end`: Why the track ended
- `shuffle`: Shuffle state
- `skipped`: Skip state

## 📊 Dashboard Components

### 1. Key Metrics Display
- Total Albums: 7.95K
- Total Artists: 4.11K
- Total Tracks: 13.84K
- Net Hours: 320.49M

### 2. Platform Analysis
- Android: 93.30%
- Cast to device: 2.60%
- iOS: 2.03%
- Mac: 0.78%
- Web player: 0.15%
- Windows: 1.13%

### 3. Track Analysis
- Top 3 Tracks visualization
- 5 Most Skipped Songs
- 5 Most Shuffled Songs

### 4. Artist Analysis
- Top 4 Artists chart
- Artist distribution by market share
- Top 10 Artists by album count

### 5. User Behavior Analysis
- Start Reason Analysis
- End Reason Analysis
- Platform usage patterns

## 🛠️ Implementation Details

### Data Preprocessing Requirements
- Timestamp formatting
- Duration conversion to hours
- Platform categorization
- Track and artist name standardization

### Visualization Types Used
- Bubble charts for track popularity
- Bar charts for reason analysis
- Pie charts for artist distribution
- Time series for listening patterns

### 📌 **Dashboard Preview**
![Spotify Dashboard](https://github.com/kouatcheu1/Spotify-Dashboard/blob/main/Spotify%20Dashboard.png)


## 🎯 Key Insights Available
- Platform preference trends
- Track interaction patterns
- Artist popularity metrics
- User engagement analysis
- Content consumption patterns


## 🚀 Usage Guidelines
1. Use filters to segment data by:
   - Time period
   - Platform
   - Artist
   - Track type
2. Interact with visualizations for detailed views
3. Export reports as needed

🚀 **View the interactive dashboard here:** [Spotify Dashboard](https://public.tableau.com/app/profile/samuel.kouatcheu/viz/SpotifyAnalysisDashboard_17385946484040/SpotifyDash)

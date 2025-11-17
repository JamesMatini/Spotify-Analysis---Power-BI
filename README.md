# Spotify-Analysis---Power-BI
Comprehensive analysis of Spotify streaming data tracking user behavior, engagement patterns, and listening habits. Analyzes play duration, skip rates, platform usage, and artist/track performance. Provides insights into user preferences, session patterns, and content engagement metrics for data-driven music recommendations and  optimization.

# 🎵 Spotify Listening Analysis

A comprehensive data analysis project exploring Spotify streaming behavior, listening patterns, and user engagement metrics through interactive dashboards and detailed analytics.

## 📊 Project Overview
## Overview Dashboard 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/662f732c-c486-4a3a-bd71-c43b940bbb0a" />

## Listening Patterns 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/35ac802a-25f6-46bf-9bb2-25a7bb86e061" />

## Details 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/290e7e19-f746-4572-9bbd-924365fa4c34" />




This project analyzes Spotify streaming data to uncover insights about listening habits, track performance, and user behavior. The dashboard provides year-over-year comparisons, top performer rankings, and detailed engagement metrics across albums, artists, and tracks.

## 🎯 Key Metrics & Insights

### Library Overview
- **Albums Played**: 7,383 (-23.1% YoY)
- **Artists Played**: 3,835 (-24.6% YoY) 
- **Tracks Played**: 12,724 (+13.0% YoY)

### Performance Trends
- **Year-over-Year Analysis**: Compare current vs previous year listening patterns
- **Engagement Metrics**: Track play counts, skip rates, and completion rates
- **Platform Usage**: Analyze listening behavior across different devices

## 📈 Top Performers Analysis

### Top Albums by Play Count
1. **The Beatles** - 1,987 plays
2. **Past Masters** - 1,407 plays  
3. **Abbey Road** - 1,300 plays
4. **The Wall** - 1,333 plays
5. **Revolver** - 1,881 plays

### Top Artists by Play Count
1. **The Beatles** - 1,846 plays
2. **The Men** - 426 plays
3. **John Mayer** - 424 plays
4. **Bob Dylan** - 345 plays
5. **Paul McCartney** - 246 plays

### Top Tracks by Play Count
- "One to Three..." - 108 plays
- "In the Blood" - 108 plays
- "Dying Hood" - 104 plays
- "19 Days / 20s..." - 106 plays
- "Concerning Us..." - 108 plays

## 🔧 Data Schema & Fields

### Core Track Information
- **spotify_track_uri**: Unique track identifier
- **track_name**: Song title
- **artist_name**: Performing artist
- **album_name**: Source album

### Listening Session Data
- **ts**: Timestamp when track stopped (UTC)
- **ms_played**: Milliseconds played
- **platform**: Streaming platform (desktop, mobile, web, smart_speaker)
- **skipped**: Whether track was skipped
- **shuffle**: Shuffle mode status

### User Behavior Tracking
- **reason_start**: How playback began (clickrow, autoplay, fwdbtn, etc.)
- **reason_end**: Why playback stopped (trackdone, fwdbtn, logout, etc.)

## 🛠️ Technical Implementation

### Tools & Technologies
- **Data Visualization**: Power BI / Tableau
- **Data Processing**: Python (Pandas, NumPy)
- **Analysis**: Statistical analysis and trend identification
- **Dashboard**: Interactive filtering and drill-down capabilities

### Key Analyses
1. **Engagement Analysis**: Play duration and completion rates
2. **Behavior Patterns**: Skip rates and shuffle usage
3. **Temporal Trends**: Listening patterns over time
4. **Platform Comparison**: Device-specific usage patterns
5. **Content Performance**: Track, artist, and album rankings

## 📁 Project Structure
<img width="751" height="605" alt="image" src="https://github.com/user-attachments/assets/719e6504-f8cd-4e0b-b585-8beb2b1c859b" />

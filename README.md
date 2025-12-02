# Spotify Analytics Dashboard

A comprehensive data analytics project leveraging Power BI and a Spotify dataset to visualize and analyze music streaming patterns, artist performance, and audio characteristics.

![Dashboard Preview](https://ibb.co/KzXxySyk)

### Overview

The Spotify Analytics Dashboard transforms raw Spotify data into actionable insights through interactive visualizations and comprehensive data modeling. This project demonstrates advanced data analysis techniques, DAX calculations, and dashboard design principles to create a production-ready analytics solution.

### Key Features

**📊 Interactive Visualizations**
- Real-time filtering across multiple dimensions (Artist, Album, Genre)
- Energy vs Danceability scatter plot with genre-based color coding
- Track duration distribution analysis
- Top artists ranking with track counts

**📈 Key Metrics Dashboard**
- **Total Tracks**: 47K tracks analyzed
- **Total Duration**: 3,016 hours of music
- **Average Duration**: 3.9 minutes per track
- **Unique Artists**: 25K artists represented

**🎵 Audio Feature Analysis**
- Acousticness, Instrumentalness, Liveness levels
- Valence (musical positivity) measurements
- Tempo and Time Signature distributions
- Energy and Danceability correlations
- Speechiness and Loudness metrics

**🎨 Genre Intelligence**
- Multi-genre classification system
- Genre-based performance metrics
- Cross-genre comparison capabilities

### Dataset Structure

The project utilizes a comprehensive Spotify dataset with the following attributes:

| Column | Description | Data Type |
|--------|-------------|-----------|
| Artist | Track artist name | Text |
| Album | Album name | Text |
| Track Name | Song title | Text |
| Popularity | Track popularity score (0-100) | Integer |
| Duration (ms) | Track length in milliseconds | Integer |
| Explicit | Explicit content flag | Boolean |
| Danceability | Danceability score (0-1) | Decimal |
| Energy | Energy level (0-1) | Decimal |
| Key | Musical key | Integer |
| Loudness | Average loudness in dB | Decimal |
| Mode | Musical mode (major/minor) | Integer |
| Speechiness | Speech presence (0-1) | Decimal |
| Acousticness | Acoustic quality (0-1) | Decimal |
| Instrumentalness | Instrumental content (0-1) | Decimal |
| Liveness | Live recording indicator (0-1) | Decimal |
| Valence | Musical positivity (0-1) | Decimal |
| Tempo | Track tempo in BPM | Decimal |
| Time Signature | Time signature (beats per measure) | Integer |
| Genre | Track genre classification | Text |

### Technical Implementation

**Power BI Features Used:**
- Data modeling and relationship management
- DAX (Data Analysis Expressions) for calculated measures
- Custom visualizations and formatting
- Interactive filtering and cross-filtering
- Dynamic measures and KPIs

**Data Processing:**
- Data cleaning and transformation
- Duration conversions (ms to minutes)
- Categorical binning for duration distribution
- Top N filtering for artist rankings

### Dashboard Components

1. **Summary Cards**: High-level metrics showing total tracks, duration, averages, and unique artists
2. **Top Artists Bar Chart**: Horizontal bar chart displaying the most prolific artists by track count
3. **Duration Distribution**: Histogram showing track length patterns across different time ranges
4. **Energy vs Danceability Scatter**: Multi-dimensional analysis correlating energy and danceability by genre
5. **Filter Panel**: Dynamic slicers for Artist, Album, and Genre filtering

### Use Cases

- **Music Industry Analysis**: Identify trends in track characteristics and artist performance
- **Playlist Optimization**: Understand audio features for targeted playlist creation
- **A&R Intelligence**: Discover emerging artists and genre trends
- **Academic Research**: Study correlations between audio features and popularity
- **Personal Listening Habits**: Analyze music preferences and characteristics

### Insights Generated

The dashboard enables users to discover:
- Which artists dominate the catalog
- How energy and danceability correlate across genres
- Distribution patterns in track durations
- Genre-specific audio characteristic profiles
- Relationships between tempo, energy, and other audio features

## Technologies Used

- **Power BI Desktop**: Primary analytics and visualization platform
- **DAX**: Data modeling and calculated measures
- **Power Query**: Data transformation and cleaning
- **Excel/CSV**: Data source management

## Getting Started

### Prerequisites

- Power BI Desktop (latest version)
- Spotify dataset (114,000+ tracks)
- Minimum 4GB RAM recommended

### Installation

1. Clone this repository:
```bash
git clone https://github.com/Dannywhilz001/spotify-analytics-dashboard.git
```

2. Open Power BI Desktop

3. Open the `.pbix` file from the repository

4. Ensure data connections are properly configured

5. Refresh the data model if needed

### Usage

1. Use the **Artist**, **Album**, and **Genre** filters to focus on specific segments
2. Hover over visualizations for detailed tooltips
3. Click on data points to cross-filter the entire dashboard
4. Export specific visuals or the entire report as needed

## Project Structure

```
spotify-analytics-dashboard/
│
├── data/
│   ├── spotify_dataset.csv          # Raw Spotify data
│   └── data_dictionary.md           # Data field descriptions
│
├── reports/
│   └── Spotify_Analytics_Dashboard.pbix  # Power BI report file
│
├── assets/
│   └── dashboard-preview.png        # Dashboard screenshots
│
├── docs/
│   ├── data_model.md               # Data model documentation
│   └── dax_measures.md             # DAX calculations reference
│
└── README.md                        # This file
```

## Key Insights from Analysis

- **Duration Sweet Spot**: Most tracks fall between 3-4 minutes, with 17K tracks in this range
- **Top Artists**: Vybz Kartel leads with 73 tracks, followed by Sujatha with 71
- **Genre Diversity**: Multiple genres represented including acoustic, afrobeat, alternative, and alt-rock
- **Audio Patterns**: Clear clusters emerge in the energy vs danceability scatter, indicating genre-specific characteristics

## Future Enhancements

- [ ] Add time-series analysis for release trends
- [ ] Implement popularity prediction models
- [ ] Include market/regional analysis
- [ ] Add playlist recommendation engine
- [ ] Integrate real-time Spotify API data
- [ ] Create mobile-optimized dashboard views

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Spotify for providing rich audio feature data
- Power BI community for visualization inspiration
- Contributors and users who provide feedback

## Author

Oladotun Olawale

## Contact

[LinkdIn](http://www.linkedin.com/in/oladotun-olawale)

Project Link: [https://github.com/Dannywhilz001/spotify-analytics-dashboard](https://github.com/Dannywhilz001/spotify-analytics-dashboard)

---

⭐ If you found this project helpful, please consider giving it a star!

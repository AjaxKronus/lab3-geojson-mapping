# Lab 3: Asynchronous GeoJSON Data Loading and Visualization

**Author:** [Your Name]  
**Course:** GEOG XXX  
**Date:** October 30, 2025

## Project Description
This project demonstrates asynchronous loading and visualization of GeoJSON data using Mapbox GL JS. It includes two web applications:

1. **earthquake.html** - Displays recent earthquakes near Japan with sortable table
2. **index.html** - Shows major US cities with population data and state boundaries

## Features
- Asynchronous GeoJSON data loading using Fetch API
- Interactive Mapbox GL JS maps with custom styling
- Sortable HTML tables for data exploration
- Responsive design (sidebar hides below 1024px)
- Interactive popups on map features
- Two different map styles and color schemes

## Data Sources
- Earthquakes: USGS Earthquake API
- Japan boundaries: DataOfJapan GitHub repository
- US Cities: Custom GeoJSON dataset
- US States: PublicaMundi GitHub repository

## Technologies Used
- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (ES6+)
- Mapbox GL JS v3.0.0
- Fetch API for asynchronous data loading

## Setup Instructions
1. Clone this repository
2. Get a free Mapbox access token from https://account.mapbox.com
3. Replace `YOUR_MAPBOX_ACCESS_TOKEN` in both HTML files
4. Enable GitHub Pages in repository settings
5. Access your site at `https://[username].github.io/[repo-name]/`

## File Structure

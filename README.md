# Olympic Medal Analysis Program

> This is a first semester project for the IPC144 (Introduction to Programming Using C) course at Seneca College.

## Overview
This program analyzes Olympic medal data from historical records, providing insights into medal distributions across different countries for specific years and seasons.

## Features
- Read and process Olympic medal data from CSV files
- Find countries with the highest number of silver medals
- Generate top 10 medal-winning countries ranking
- Display medal statistics with visual histogram
- Special handling for 1956 Equestrian Olympics data

## Technical Details
- Language: C
- Input: CSV file containing Olympic medal records
- Output: Console-based text and histogram visualization

## Functions
- `UsrInput`: Handles user input for year and season selection
- `ReadMedalFile`: Processes CSV file and loads medal data
- `Topsilver`: Identifies countries with most silver medals
- `Top10Medal`: Determines top 10 countries by total medals
- `PrintSummary`: Displays formatted results and histogram

## Usage
1. Run the program
2. Enter the desired year when prompted
3. Select season (1 for Summer, 2 for Winter)
4. View the analysis results including:
   - Total records processed
   - Countries with most silver medals
   - Top 10 countries with medal distribution histogram

## Data Handling
- Supports both Summer and Winter Olympics
- Special case handling for 1956 Equestrian Olympics
- Buffer overflow protection
- Error handling for file operations

## Author
- Name: Yicheng Wang
- Student ID: 150868206
- Course: IPC-NDD

## Problems Solved
- Topsilver (A2, easy)
- Top10Medal (C3, hard)

## Notes
- Input validation for year and season
- Proper memory management
- Error handling for file operations
- Visual representation of medal counts 
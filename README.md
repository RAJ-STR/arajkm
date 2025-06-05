Python-Project-Submission
Book Suggestion Bot (Open Library API)
A Python-based command-line application that fetches books from the Open Library API. It allows users to filter based on genre, edition count, and publication year, and provides random book suggestions. The app supports saving and loading book data using CSV files.

Features
Fetch books by search term (e.g., "fiction", "science", "fantasy") from the Open Library API
Save fetched results to a CSV file for reuse
Filter books by:
Genre
Edition count
Publication year (minimum and maximum)
Get random book suggestions from filtered results
Input validation and retry functionality
Data display using pandas for easy inspection
Technologies Used
Python 3.x
requests – for making API calls
pandas – for data handling and filtering

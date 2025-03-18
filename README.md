
# Flutter API Integration & Data Fetching Assignment

## Project Overview

This Flutter application fetches and displays data from a public API, focusing on seamless API integration, data handling, and user experience. The app retrieves posts from the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/posts) and displays them in a scrollable list.

## Features

- **API Integration**: Fetches data from `jsonplaceholder.typicode.com/posts`.
- **ListView**: Displays the post titles in a scrollable list.
- **Loading Indicator**: Shows a circular loading spinner while the data is being fetched.
- **Error Handling**: Displays a user-friendly error message if the API request fails.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/warxmachine/PROJECT-X.git
   ```
2. **Install dependencies**:
   ```bash
   flutter pub get
   ```
4. **Run the app**:
   ```bash
   flutter run
   ```

## Assumptions

- The app only displays the post titles for simplicity.
- Any network failure will result in a simple error message being shown to the user.

## Additional Enhancements

- The app handles potential failures gracefully by showing a message instead of crashing.
- Clean and structured code with adequate comments for better understanding.

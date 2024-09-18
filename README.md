# LeetMetric

LeetMetric is a web-based application that helps you track and visualize your LeetCode progress. It fetches real-time user data from the LeetCode API using GraphQL queries and presents the data in an interactive and intuitive manner. With a clean and responsive UI, it enables users to easily monitor their problem-solving progress across different difficulty levels—Easy, Medium, and Hard.

## Features

- **User Progress Visualization**: Displays your progress in solving LeetCode problems at different levels of difficulty (Easy, Medium, and Hard) with interactive progress circles.
- **Real-Time Data Fetching**: Uses the LeetCode GraphQL API to fetch up-to-date user statistics, including the number of problems solved and total submissions.
- **Submission Statistics**: Provides detailed statistics, including total submissions and a breakdown of problem difficulties.
- **Clean and Responsive UI**: Optimized for both desktop and mobile devices with a focus on usability and simplicity.
- **Interactive Elements**: Hover effects and smooth transitions enhance the user experience.

## Technologies Used

- **Frontend**: 
  - HTML
  - CSS (for styling and responsiveness)
  - JavaScript (for interactivity and data fetching)
- **API**: 
  - LeetCode GraphQL API for fetching real-time user data
- **Design**:
  - Flexbox for layout structure
  - Mobile-first design for responsiveness

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Abhigyan-Srivastava/LeetMetric.git
    ```
2. Navigate to the project directory:
    ```bash
    cd LeetMetric
    ```
3. Open `index.html` in your browser to view the app.

## Usage

1. Enter your LeetCode username in the input field.
2. Click the "Search" button.
3. View your LeetCode progress, including the number of problems solved across different difficulty levels, and your submission statistics.

## How It Works

- **Data Fetching**: LeetMetric uses a GraphQL query to fetch user statistics from LeetCode.
- **User Input**: The user enters their LeetCode username, and the app fetches and displays their submission stats.
- **Visualization**: The progress for Easy, Medium, and Hard problems is displayed using progress circles, while total submission statistics are shown in cards.

## Future Enhancements

- Add more detailed statistics, such as streaks or comparison with other users.
- Implement a backend to handle data caching and reduce API request limits.
- Add a feature to track user performance over time.

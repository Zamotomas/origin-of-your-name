# Name Popularity Checker

This is a simple web application that allows users to check the popularity of their first name around the world. The app uses the **Nationalize API** to fetch the countries where the name is most common. It displays a list of countries where the name appears the most, based on data from the API.

## Features

- Enter your first name (without accents) to get the results.
- The app will display the countries where your name is most popular.
- It caches previous results to avoid making repeated API requests for the same name.
- If there is an error with the API, the app will show a friendly error message.

## How to Use

1. Enter your first name into the input field.
2. Click the "Check" button or press **Enter** to submit.
3. The app will display a list of countries where your name is most common.

## Installation

To use this program, you can clone this repository and open the HTML file in your browser. No server-side setup is required.

### Prerequisites

- A modern web browser (Chrome, Firefox, etc.).
- An internet connection to fetch data from the **Nationalize API**.

### API URL

The app uses the **Nationalize API** to retrieve name popularity data. The base URL for the API is:

```javascript
const apiUrl = "https://api.nationalize.io?name=";
```

# Stock Data Fetcher

Stock Data Fetcher is a simple web application that allows users to fetch stock data for a given symbol and date. The application is built using React for the frontend and Node.js with Express for the backend. It uses the Polygon API to fetch stock data.

## Prerequisites

Before running the project, ensure you have the following installed:

- Node.js (https://nodejs.org/)
- npm (Node Package Manager, comes with Node.js)

## Getting Started

1. Clone the repository:
2. Install dependencies for both frontend and backend:
3. Set up environment variables:

   - Rename `.env.example` file in the `backend` directory to `.env`.
   - Obtain a Polygon API key and replace `YOUR_POLYGON_API_KEY` in the `.env` file with your actual API key.

4. Run the application:

   - Start the backend server (in the `backend` directory):
   - Start the frontend development server (in the `frontend` directory):
   - The frontend will run on `http://localhost:3000`, and the backend will run on `http://localhost:5000`.

5. Access the application in your web browser:

Open your web browser and go to `http://localhost:3000`. You should see the Stock Data Fetcher web application.

## Usage

1. Enter the stock symbol (e.g., AAPL) and the date for which you want to fetch the stock data.
2. Click the "Fetch Stock Data" button.
3. The stock data (Open, High, Low, Close, and Volume) for the specified symbol and date will be displayed.

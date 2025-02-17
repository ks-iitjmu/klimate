# Klimate

Klimate is a simple web application that provides weather information for different locations. It uses the OpenWeatherMap API to fetch current weather data.

## Features

- Search for weather by city name
- Display current temperature, humidity, and weather conditions
- Responsive design for mobile and desktop

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Klimate.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Klimate
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

1. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Create a `.env` file in the root directory and add your API key:
    ```
    REACT_APP_WEATHER_API_KEY=your_api_key_here
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
- [React](https://reactjs.org/) for the front-end framework.

## Deployment

To deploy this project using Vercel:

1. Install the Vercel CLI:
    ```bash
    npm install -g vercel
    ```
2. Run the following command to deploy:
    ```bash
    vercel
    ```
3. Follow the prompts to link your project to a Vercel account and deploy.

For more details, refer to the [Vercel documentation](https://vercel.com/docs).
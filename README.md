
# Car Stock Dashboard

This Streamlit application provides an interactive dashboard to explore and analyze car stock data.

## Features

- **Filter by Manufacturer:** Select specific car manufacturers to view their stock data.
- **Filter by Automation Type:** Choose between different automation types (e.g., manual or automatic).
- **Filter by Use Category:** Distinguish between foreign used and locally used cars.
- **Visualizations:** Interactive visualizations using Plotly to provide insights into the car stock data.

## Installation

To run this application, you'll need Python installed on your system. Follow the steps below to set up and run the app.

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/car-stock-dashboard.git
   cd car-stock-dashboard
   ```

2. **Install the required packages:**

   It's recommended to use a virtual environment to manage dependencies. You can create one and install the packages using the following commands:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scriptsctivate`
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app:**

   ```bash
   streamlit run app.py
   ```

## Usage

Once the app is running, open your web browser and go to `http://localhost:8501` to view the dashboard. Use the sidebar to filter data according to your preferences.

## Data

The app reads data from a CSV file located at `./data/cars.csv`. Make sure this file is present in the specified directory before running the app. The CSV file should contain columns like:

- `manufacturer`
- `Automation`
- `Foreign_Local_Used`
- (additional relevant columns)

## File Structure

```plaintext
.
├── data
│   └── cars.csv
├── app.py
├── helper.ipynb
├── requirements.txt
└── README.md
```

## Contributing

If you wish to contribute to the project, feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

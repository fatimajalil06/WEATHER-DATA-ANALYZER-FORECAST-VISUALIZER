# WEATHER-DATA-ANALYZER-FORECAST-VISUALIZER
I built the Weather Data Analyzer, a Python desktop app using Tkinter, Pandas, and Matplotlib. It fetches real-time OpenWeatherMap API data, calculates max/min/avg stats in Pandas, and embeds interactive 24h forecast charts using FigureCanvasTkAgg. Features include a dual-tabbed GUI (ttk.Notebook), responsive scaling, and CSV data export.
#  Weather Data Analyzer & Forecast Visualizer

A responsive Python desktop application designed to fetch real-time weather metrics and 24-hour forecast data via the OpenWeatherMap REST API. The app processes data using Pandas, computes key statistical metrics, and visualizes trends using embedded Matplotlib plots within a tabbed Tkinter interface.

## Key Features

 **Real-Time API Integration:** Fetches live temperature, humidity, wind speed, and weather conditions via OpenWeatherMap HTTP GET requests.
**Pandas Analytics:** Automatically calculates maximum/minimum temperatures and average humidity across a 24-hour forecast window.
 **Embedded Visualization:** Renders interactive 24-hour temperature trend graphs directly inside the GUI using Matplotlib's Object-Oriented interface (`FigureCanvasTkAgg`).
**Dual-Tabbed Interface:** Employs `ttk.Notebook` to separate visual trend charts from structured `ttk.Treeview` data tables.
 **CSV Data Export:** Allows users to export structured forecast datasets to local `.csv` files for persistence and offline analysis.
 **Responsive UX:** Includes dynamic background wallpaper scaling on window resize events (`<Configure>` binding) with a single-click reset option.

---

## Future Improvements

* Extended 7-Day and 14-Day Forecast Analysis
* Historical Weather Data Storage
* Advanced Data Visualization
* Weather Alerts and Notifications
* Automatic Data Refresh
* Location-Based Weather Detection
* Enhanced Weather Analytics
* Improved API Error Handling
* Customizable Dashboard
* Cloud Data Synchronization
* Machine Learning-Based Weather Prediction


##  Tech Stack & Architecture

| Component | Library / Framework | Purpose |

| **GUI Framework** | `tkinter`, `ttk` | Window layout, tabbed navigation, and data table view |
| **Data Processing** | `pandas` | Parsing JSON payloads, data structuring, and statistical calculations |
| **Data Visualization** | `matplotlib` | Time-series line plotting using Object-Oriented (`fig, ax`) approach |
| **GUI Integration** | `FigureCanvasTkAgg` | Embedding Matplotlib canvas objects into Tkinter frames |
| **API & Networking** | `requests` | Fetching live weather data from OpenWeatherMap REST API |
| **Image Processing** | `Pillow` (`PIL`) | Dynamic background image loading and resizing |



## Repository Structure

├── background.png        # Background wallpaper image
├── weather_analyzer.py   # Main Python application script
├── README.md             # Project documentation
├── .gitignore            # Git ignore rules
└── LICENSE               # Open-source license (MIT)

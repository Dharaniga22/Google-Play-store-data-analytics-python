# Google Play Store Data Analytics with Python

## Overviw
This project explores Google Play Store app data to reveal trends in app ratings, installs, user engagement, and category performance.It combines powerful Python libraries with dynamic web visualization techniques to create an intuitive, time-controlled analytics dashboard.

## Features
- **Data Preprocessing:** Clean and filter apps based on category, app name, reviews, and ratings.
- **Interactive Visualizations:** Built with Plotly and Seaborn for a smooth, engaging experience.
- **Time-Based Chart Visibility:** Certain charts (like the Violin plot) appear only during specific time slots (IST).
- **Fully Dynamic HTML Dashboard:** Responsive and stylish layout with embedded insights.

## Tech Stack
- **Python:** Data wrangling and visualization
- **Pandas & Numpy:** Data manipulation
- **Plotly & Seaborn:** Beautiful, interactive charts
- **Matplotlib:** Plot customization
- **HTML + CSS:** Dashboard styling
- **Pytz & Datetime:** Timezone and timing controls

## Key Visualizations
- **Heatmap:** Shows correlations between installs, reviews, and ratings.
- **Violin Plot:** Displays rating distributions across categories (filtered smartly).
- **Dual-Axis Charts (Reference):** Compare installs and revenue between free vs paid apps.

## How to Run
1. **Clone the repository:**
    ```bash
    git clone <repo-link>
    cd <repo-folder>
    ```
2. **Install dependencies:**
    ```bash
    pip install pandas matplotlib seaborn plotly pytz
    ```
3. **Place the dataset** in the `Data/` folder.
4. **Run the scripts** to generate charts.
5. **Open** `dashboard.html` in your browser and enjoy the insights!

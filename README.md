
# FreedomCorp Sales Dashboard

This project is a data visualization dashboard for FreedomCorp Ltd, a large distribution conglomerate in the US. The dashboard allows users to monitor and analyze the performance of different sales teams across various regions.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The FreedomCorp Sales Dashboard visualizes sales data to help executives keep tabs on their different sales teams. The company sells wholesale goods such as electronics, household appliances, construction materials, and furniture to small businesses across the country.

The sales force is divided into four teams, each controlling distribution in their region:
- North-East
- West
- South
- Midwest

Every day, each team makes phone calls to businesses in their region to sell products. The dashboard visualizes metrics such as revenue, call duration, and units sold, broken down by teams and categories.

## Features

- **Stacked Area Chart**: Displays metrics for revenue, call duration, and units sold, broken down by different teams.
- **Timeline**: Allows users to brush over a bar chart to filter data by a specific time range.
- **Donut Chart**: Summarizes data by company size within the selected time range.
- **Bar Charts**: Show summary data for revenue, call duration, and units sold within the selected time range.

## Technologies Used

- HTML
- CSS
- JavaScript
- D3.js
- Bootstrap

## Setup and Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/freedomcorp-sales-dashboard.git
   cd freedomcorp-sales-dashboard
   ```

2. **Open the project**:
   Open `index.html` in your preferred web browser to view the dashboard.

## Usage

1. **Date Range Selection**:
   - Use the timeline brush to select a specific date range.
   - The charts will update automatically to reflect the selected date range.

2. **Metric Selection**:
   - Use the dropdown menu to switch between different metrics (Revenue, Call Time, Units Sold).
   - The stacked area chart and other visualizations will update based on the selected metric.

## File Structure

```
freedomcorp-sales-dashboard/
├── css/
│   └── style.css
├── data/
│   └── calls.json
├── js/
│   ├── barChart.js
│   ├── donutChart.js
│   ├── main.js
│   ├── stackedAreaChart.js
│   └── timeline.js
├── img/
│   └── logo.png
├── index.html
└── README.md
```

- `css/style.css`: Styles for the dashboard.
- `data/calls.json`: Sample data for the dashboard.
- `js/barChart.js`: Logic for rendering bar charts.
- `js/donutChart.js`: Logic for rendering the donut chart.
- `js/main.js`: Main JavaScript file for initializing the dashboard.
- `js/stackedAreaChart.js`: Logic for rendering the stacked area chart.
- `js/timeline.js`: Logic for rendering the timeline.
- `img/logo.png`: Logo image for the dashboard.
- `index.html`: Main HTML file for the dashboard.
- `README.md`: Documentation for the project.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

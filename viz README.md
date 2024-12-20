# Interactive Data Visualization Using D3.js

## Project Overview
This project demonstrates the creation of interactive data visualizations using **D3.js**. The application provides a comprehensive view of revenue by age groups across countries and revenue distribution by product categories. The visualizations include:

1. **Stacked Bar Chart**: Displays revenue distribution by age groups across countries.
2. **Pie Chart**: Represents revenue by product categories for a selected country.
3. **Dynamic Subcategory Bar Chart**: Visualizes revenue by subcategories when a product category is selected.

## Features
- Interactive stacked bar chart showing age group revenues across countries.
- Pie chart with hover and click functionalities to explore revenue by product categories.
- Subcategory bar chart dynamically generated based on interactions with the pie chart.
- Tooltips for detailed insights on hover.
- Dynamic updates based on user interactions.

## Files Included
- **index.html**: The main HTML file containing the structure and styles.
- **scripts.js**: Contains JavaScript code to process data and generate the visualizations using D3.js.
- **data.csv**: Dataset used for visualizations.

## Project Setup

### Prerequisites
- **D3.js (v6)**: Ensure the D3.js library is loaded.
- **PapaParse**: Used for parsing CSV data.

### Steps to Run
1. Clone the repository or download the project files.
2. Place all files (HTML, JavaScript, and CSV) in the same directory.
3. Open `index.html` in a modern web browser.

## Visualizations

### 1. Stacked Bar Chart
- **Purpose**: Displays revenue by age group for different countries.
- **Interactions**:
  - Hover: Shows detailed information about the revenue of each age group.
  - Click: Updates the pie chart to reflect the selected country's data.

### 2. Pie Chart
- **Purpose**: Represents revenue by product categories for a specific country.
- **Interactions**:
  - Hover: Shows category details and revenue percentage.
  - Click: Displays a subcategory bar chart for the selected category.

### 3. Subcategory Bar Chart
- **Purpose**: Visualizes revenue distribution within subcategories of a selected product category.
- **Interactions**:
  - Hover: Highlights the bar for clearer visibility.

## Code Highlights

### Data Processing
- CSV data is parsed using **PapaParse** for efficient processing.
- Data is grouped and aggregated using D3.js.

### Stacked Bar Chart
- Data is stacked using `d3.stack()` for grouped visualization.
- Dynamic scales (`d3.scaleLinear` and `d3.scaleBand`) are used for proper alignment.

### Pie Chart
- A `d3.pie()` generator is used to create slices.
- Tooltip and hover interactions provide dynamic details.

### Subcategory Bar Chart
- Filters data based on selected product category.
- Dynamically updates the chart area.

## Technologies Used
- **HTML**: Structure and layout.
- **CSS**: Styling and design.
- **D3.js**: Core library for visualizations.
- **PapaParse**: CSV parsing.

## Usage Instructions
1. Open `index.html` in a browser.
2. Interact with the bar chart to filter data by country.
3. Explore the pie chart for product category revenue.
4. Click on a pie slice to reveal subcategory details.

## Future Enhancements
- Add functionality to upload custom datasets dynamically.
- Include more chart types (e.g., line charts, heatmaps).
- Enhance accessibility for broader usability.

## Author
Nandini Krishna

## License
This project is licensed under the MIT License.

## Contact
For queries or contributions, please contact nandinikrishna.jps@gmail.com.


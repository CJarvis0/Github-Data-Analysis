# GroupProj
**Data Visualization surrounding data scraped from GitHub**  

### Steps to Install

1. **Clone the repository**
   ```bash
   git clone https://github.com/CJarvis0/Github-Data-Analysis.git
   ```
2. **Install 'Live Server' on VSCode Extenstions**
    ```bash
    click 'Go Live' in the bottom right corner
    ```

### Using the dashboard

Double click on items within a visualization, it will be selected across the entire dashboard.

Reset using the top left 'Reset' button. This is dashboard wide.

When using the Radial Visualization (bottom right), note that each key statistic is weighted based on the value of that statistic that each individual repository holds. If a repo has more forks, the data point of that repo will be pulled closer to the `forks_count` quadrant. Select or Deselect which languages you'd like to observe by clicking the language name in the visual key (all languages are selected by default). Click the `Reset Filters` button to reset the RadViz. 

When using the Bubble Chart (bottom left), you can find data for a language by using the search bar to the left. The bubbles with that language will then have a red ring around them.

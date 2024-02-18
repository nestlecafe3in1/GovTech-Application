## Introduction for Task 1

This project analyzes restaurant data from Zomato to inspire a travel food series. It processes and analyzes restaurant ratings, events, and other relevant data to identify top-rated restaurants and interesting past events.

## How to Run the Code Locally

### Application Notebook

- `Application.ipynb` contains the main code. To run it:
  1. Open the notebook in Jupyter Notebook.
  2. Press **Run All** to execute the full code.
  3. The notebook is organized into classes representing different segments of Task 1:
     - `Class RestaurantDataProcessor` for part 1.
     - `Class EventDataProcessor` for part 2
     - `Class RatingStatisticsProcessor` for part 3
  4. The final cell contains the main function that executes all classes.
  5. Data files (`restaurant_data.json`, `Country-Code.csv`) should be in the same directory as the notebooks.

### Unit Tests

- `unittest.ipynb` contains the unit tests. To run the tests:
  1. Open the notebook in Jupyter Notebook.
  2. Press **Run All**.
  3. Test results are displayed in the bottom cell, indicating if all tests ran smoothly.

## Required Installation

Before running the application, ensure you have the following installed:
- Python 3.8 or higher.
- Jupyter Lab or Jupyter Notebook, to open `.ipynb` files.

After cloning the repository and navigating to the project directory, install the required Python packages using `pip`:

```bash
pip install numpy pandas requests nbimporter
```
### Assumptions and interpretations
- I have assumed that the field "restaurant.location.country_id" in the JSON file given corresponds to the field "Country Code" in Country-Code.csv
- In part 3 of Task 1 I have interpreted the the threshold for the different rating text based on the minimum and maximum value of each User Rating. (It is pasted below)

### Threshold to Part 3 Task 1
| User Rating  | Min | Max |
|--------------|-----|-----|
| Poor         | 2.2 | 2.2 |
| Average      | 2.5 | 3.4 |
| Good         | 3.5 | 3.9 |
| Very Good    | 4.0 | 4.4 |
| Excellent    | 4.5 | 4.9 |

### How to run the code locally
Application.ipynb contains the main code and unittest.ipynb is the file containing the code for unit tests.<br />

To run Application.ipynb, press run all to retrieve the full code. Each segment of Task 1 is represented as classes in chronological order (Class RestaurantDataProcessor refers to part 1, Class EventDataProcessor refers to part 2, etc.). The final cell will then contain the main function to run all classes.

unittest.ipynb works the same way, just that final test results are shown on the bottom cell, where it checks if all tests have been run smoothly

### Required installation
After cloning the repository and navigating to the project directory, install the required Python packages using `pip`:

```bash
pip install numpy pandas requests nbimporter
```
### Assumptions
- I have assumed that the field "restaurant.location.country_id" in the JSON file given corresponds to the field "Country Code" in Country-Code.csv

### Threshold to Part 3 Task 1
| User Rating  | Min | Max |
|--------------|-----|-----|
| Poor         | 2.2 | 2.2 |
| Average      | 2.5 | 3.4 |
| Good         | 3.5 | 3.9 |
| Very Good    | 4.0 | 4.4 |
| Excellent    | 4.5 | 4.9 |

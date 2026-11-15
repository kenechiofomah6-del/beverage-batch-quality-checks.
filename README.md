# Beverage Batch Quality Checks

## Project overview

I used Python to check six fictional beverage batches against example pH and Brix ranges. This project was inspired by my experience measuring pH, Brix, and acidity during beverage quality checks at Viju Foods.

## How the checks work

I used pandas to check whether each batch fell within the example ranges of 3.2–3.6 for pH and 11.0–11.8 °Bx for Brix. Both ranges include their endpoints. I flagged a batch for review if either measurement fell outside its range, then used Matplotlib to chart the results.

## Results

- B01 and B04 met both criteria.
- B02, B05, and B06 fell outside the Brix range.
- B03 had a pH of 3.9, above the example upper limit of 3.6.

## How to run the project

1. Open the `.ipynb` file in Jupyter Notebook.
2. Make sure pandas and Matplotlib are installed.
3. Run all cells from top to bottom.

The notebook creates the fictional data in Python, so no separate dataset download is needed.


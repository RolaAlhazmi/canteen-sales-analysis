# Canteen Sales Analysis (Sample Data)

A beginner data-analysis project: which canteen products make the most
profit, and how much money is lost to unsold items.

**Important:** the data in `canteen_sales.csv` is synthetic (made-up) sample
data for practice. Prices, costs and quantities are assumptions, so the
findings illustrate the method, not real results.

## Questions
- Which products earn the most profit?
- Which products have the highest leftover rate?
- How much is the waste worth in SAR?

## Method
Python (pandas, matplotlib) in Google Colab: group by product, compute
profit, leftover % and waste cost (Leftover x Cost).

## Example finding (sample data)
Chips has the highest leftover percentage, but Sandwich causes the highest
waste cost in SAR.

## How to run
Open the notebook in Google Colab, run the upload cell and choose
`canteen_sales.csv`, then run all cells. The CSV uses `;` as separator.

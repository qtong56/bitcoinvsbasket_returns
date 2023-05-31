## Crypto Returns Modelling
This repository contains Python code for analysing and modelling crypto returns data. The code reads in data from a downloaded CSV file, processes and cleans the data, and performs various calculations and analyses.

#### Prerequisites
- Python 3.x
- Libraries: requests, numpy, pandas, matplotlib, dateutil

#### Usage
1. Import the required libraries.
2. Read in the bitcoin data from a downloaded CSV file.
3. Modify the indexes to remove the timezone format and reindex to the given values in the CSV.
4. Resample the data to the last day of each month.
5. Delete the original index reference column and create a returns column.
6. Display the data.
7. Define the list of coins to analyse.
8. Remove stablecoins and select a shorter list of coins (CoinDesk 20).
9. Create a function to calculate the returns for each coin.
10. Create a function to calculate the average monthly returns.
11. Create a function to calculate the cumulative returns for each coin.
12. Create a function to create a portfolio of the top-performing coins each month.
12. Create a function to calculate the Compound Annual Growth Rate (CAGR) of the returns.
13. Set the dataframes for the crypto data.
14. Write the crypto data to a CSV file.
15. Read in the data from the saved CSV file.
16. Perform the required calculations and create the necessary dataframes.
17. Write the results to a CSV file.

#### Examples
Examples of how to use the code can be found in the code comments and the output displayed in the console.

#### License
This project is licensed under the MIT License - see the LICENSE file for details.

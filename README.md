# TOPSIS Assignment

## Objective
This assignment implements the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)**
method using Python.

The goal of TOPSIS is to rank multiple alternatives based on different criteria and their importance.

---

## What is TOPSIS?
TOPSIS is a multi-criteria decision-making method.
It selects the best alternative by comparing the distance of each option from:
- An **ideal best solution**
- An **ideal worst solution**

The alternative closest to the ideal best and farthest from the ideal worst gets the highest rank.

---

## Methodology (Steps)

1. Read the input data from a CSV file  
2. Assign weights to each criterion  
3. Define impact of each criterion (`+` for benefit, `-` for cost)  
4. Normalize the data  
5. Multiply normalized values with weights  
6. Determine ideal best and ideal worst values  
7. Calculate distance from ideal best and worst  
8. Compute TOPSIS score  
9. Rank alternatives based on the score  

---

## Input File
- First column: Alternative names
- Remaining columns: Numerical criteria values

---

## Output File
The output CSV file contains:
- **Topsis Score** – performance score of each alternative
- **Rank** – ranking based on the TOPSIS score

Higher score means better rank.

---

## Result Table
The result table shows all alternatives along with their TOPSIS score and rank.

This helps in selecting the best alternative easily.

---

## Result Graph
A bar graph is used to visualize the TOPSIS scores of all alternatives.
This provides a clear comparison between different options.

---

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

---

## Conclusion
TOPSIS is an effective and simple method for ranking alternatives using multiple criteria.
This implementation successfully demonstrates the working of TOPSIS using Python.

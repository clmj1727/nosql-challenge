<h1  align="center">NoSQL Challenge: Eat Safe, Love – UK Food Hygiene Analysis</h1>
<a name="readme-top"></a>

This project uses NoSQL (MongoDB) and Python (via Jupyter Notebooks) to analyze food hygiene data from the UK Food Standards Agency. This work was done in response to a data request by the food magazine *Eat Safe, Love*, which aims to help its editorial team make informed decisions about where to feature or avoid establishments across the UK.

## 📁 Repository Overview

This repository includes:

- **NoSQL_setup_starter.ipynb**: Sets up the MongoDB database, imports data, performs updates, and cleans fields.
- **NoSQL_analysis_starter.ipynb**: Performs exploratory data analysis to answer key editorial questions.
- **Resources/establishments.json**: Contains the original food hygiene data from the UK Food Standards Agency.

---

## Technologies Used

- Python
- Jupyter Notebook
- MongoDB
- PyMongo
- Pandas
- Pretty Print (pprint)

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/clmj1727/nosql-challenge.git
cd nosql-challenge
```

### 2. Load the JSON Data into MongoDB
In your terminal, use the following command to import the establishments data:
```bash
mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json
```

### 3. Open the Jupyter Notebooks
Launch Jupyter Notebook and open the following files:

- `NoSQL_setup_starter.ipynb`
- `NoSQL_analysis_starter.ipynb`

---
# Acknowledgements:

Special thanks to Dr. Carl Arrington for guidance during the NoSQL Databases Module. Some snippets and logic were developed following in-class tutorial support and discussions on the following topics: 
- Introduction to NoSQL and MongoDB
- PyMongo and Advanced Queries
- Aggregation, Analysis, and Integration with MongoDB
<p  align="center">(<a  href="#readme-top">back to top</a>)</p>

# Data Integration and Cleaning with Python

## 📖 Overview
This repository documents my learning on how to:
- Read serialized **JSON** and **CSV** data into Python objects
- Extract information from nested data structures
- Perform data cleaning tasks (filtering, normalizing, type conversion)
- Combine multiple sources into a single dataset for analysis

---

## 🛠 Steps Practiced

### 1. Reading Data
```python
import pandas as pd
import json

# Read CSV
csv_data = pd.read_csv("data.csv")

# Read JSON
with open("data.json", "r") as f:
    json_data = json.load(f)

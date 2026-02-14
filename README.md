Python Basics: Data Reading & Cleaning (Pandas)

This project is part of the **Data Analyst Internship Program**.

The objective of this task is to perform basic data cleaning and preprocessing using Python libraries such as Pandas and NumPy.

---

## 📂 Dataset Used
Titanic Dataset

The dataset contains passenger details such as:

- Age
- Gender
- Passenger Class
- Fare
- Survival Status

---

## 🛠 Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy

---

## 🔎 Steps Performed

### 1️⃣ Data Loading
- Imported dataset using `pd.read_csv()`
- Displayed first rows using `.head()`
- Checked structure using `.info()`

### 2️⃣ Missing Value Identification
- Used `.isnull().sum()` to detect null values.

### 3️⃣ Missing Value Treatment
- Filled numeric columns with **mean**.
- Filled categorical columns with **mode**.
- Dropped irrelevant columns with excessive nulls.

### 4️⃣ Duplicate Removal
- Detected duplicates using `.duplicated()`.
- Removed duplicates using `.drop_duplicates()`.

### 5️⃣ Datatype Conversion
- Converted columns into proper datatypes for accurate analysis.

### 6️⃣ Feature Engineering
Created new columns such as:
- Age Group
- Fare Category

### 7️⃣ Data Export
- Saved cleaned dataset using `.to_csv()`.

---

## 📊 Output Files

- `Task5_Cleaning.ipynb` → Jupyter/Colab Notebook
- `cleaned_data.csv` → Cleaned Dataset

---

## 🧠 Key Learnings

- Reading datasets using Pandas
- Handling missing values
- Removing duplicates
- Datatype conversion
- Feature creation
- Exporting processed data

---

## 🚀 Final Outcome

This task demonstrates how Python can automate and simplify large-scale data cleaning compared to manual Excel processing.

---

## 📁 Repository Structure

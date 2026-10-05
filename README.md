# 🧶 Yarn Count Calculator

A simple and professional **Yarn Count Calculator** built with **Python and Streamlit**.

The application calculates yarn count using:

- Weight in **pounds (lbs)**
- Length in **yards**
- Number of **hanks**
- English Cotton Count (**Ne**)
- Yards per pound
- Weight in grams

## 📌 Calculation Method

This calculator uses the English Cotton Count (Ne) system.

One hank is:

**1 hank = 840 yards**

The formula is:

```text
Hanks = Yards ÷ 840
```

```text
Ne = Hanks ÷ Weight in pounds
```

Therefore:

```text
Ne = Yards ÷ (840 × Pounds)
```

### Example

If:

```text
Weight = 1 lb
Length = 840 yards
```

Then:

```text
Hanks = 840 ÷ 840 = 1
Ne = 1 ÷ 1 = 1.00
```

## 📁 Project Files

```text
yarn-count-calculator/
│
├── app.py
├── README.md
└── requirements.txt
```

## 💻 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/yarn-count-calculator.git
```

### 2. Open the project folder

```bash
cd yarn-count-calculator
```

### 3. Install requirements

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit app

```bash
streamlit run app.py
```

The application will open in your browser.

## ☁️ Deploy on Streamlit Community Cloud

1. Upload `app.py`, `README.md`, and `requirements.txt` to a GitHub repository.
2. Open Streamlit Community Cloud.
3. Connect your GitHub account.
4. Select your repository.
5. Select `app.py` as the main file.
6. Click **Deploy**.

Your calculator will then be available as a web application.

## 🧮 Features

- Simple input fields for pounds and yards
- Automatic hank calculation
- Automatic English yarn count (Ne)
- Yards-per-pound calculation
- Weight conversion from pounds to grams
- Clean Streamlit interface
- GitHub-ready
- Easy to deploy

## 🛠️ Technologies

- Python
- Streamlit

## 👤 Author

**Muhammad Uzair Ansari**

Yarn Count Calculator Project

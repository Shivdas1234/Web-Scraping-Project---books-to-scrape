

# 📚 Web Scraping: Books to Scrape

## Overview
This project demonstrates how to use Python for web scraping to extract data from the "Books to Scrape" website. It covers the entire process of navigating HTML structure, extracting specific information, and saving the data in a CSV format.

---

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Project Goals](#project-goals)
3. [Technologies Used](#technologies-used)
4. [Workflow](#workflow)
5. [How to Run the Project](#how-to-run-the-project)
6. [Results](#results)

---

## 📖 Introduction
The "Books to Scrape" website is a mock e-commerce site designed for learning web scraping techniques. This project fetches data such as book titles, prices, ratings, and categories.

---

## 🎯 Project Goals
- Scrape and save information about books from all categories.
- Convert the extracted data into a structured CSV format.
- Utilize reusable Python functions for scalability.

---

## 💻 Technologies Used
- **Python**: Core language for scraping and data manipulation.
- **BeautifulSoup**: For parsing HTML and extracting information.
- **Pandas**: For organizing and saving data.
- **Jupyter Notebook**: For developing and documenting the project.

---

## 🚀 Workflow
1. Fetch HTML content of the website.
2. Extract category names and URLs.
3. Iterate through each category and fetch book details:
    - Title
    - Price
    - Star rating
4. Save the data in a structured CSV file.

---

## 🛠️ How to Run the Project
1. Clone this repository.
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook to execute the code step-by-step.
4. The extracted data will be saved as `data/scraped_books.csv`.

---

## 📊 Results
- Extracted details of all books available on the website.
- Saved the information in a user-friendly CSV format for further analysis.

---

## 🙏 Thank You!
This project is a great starting point for mastering web scraping. Feel free to contribute or use it as a reference for similar tasks.

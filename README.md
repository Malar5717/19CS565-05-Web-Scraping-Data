# EXP 05: WEB SCRAPING DATA

### AIM

The goal of this project is to:

1.  Extract **Title** and **Price** for all books on the target website: http://books.toscrape.com/.
2.  Automatically handle pagination (clicking the "Next" link).
3.  Export the complete dataset to a local CSV file.

---

### PROCEDURE

The workflow uses the following key steps:

1.  **Use Application/Browser:** Opens and attaches to the target website.
2.  **Extract Table Data:** Runs the scraping wizard to define the data fields and the **Next Link** for pagination. Data is saved to the `ScrapedBooksData` DataTable variable.
3.  **Write CSV (Classic):** Takes the `ScrapedBooksData` variable and writes the full dataset (100 rows) to a file named `ScrapedBooksData.csv`.

---

### OUTPUT

The automation generates one output file:

* **Attached File:** `ScrapedBooksData.csv`

---

### RESULT

The automation successfully extracts all available book data from the multi-page website is completed successfully.

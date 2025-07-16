# Anime Data Extraction and Analysis

## 📖 Description
This project focuses on the data cleaning and exploratory analysis of a ranked anime dataset. The core of the project involves parsing and extracting structured information—such as episode counts and airing dates—from a single, combined text column to enable meaningful analysis.

---

## 📊 Key Analyses Performed
* **Data Extraction:**
    * Engineered a function to parse the `Title` column and create a new `Episodes` column.
    * Extracted the airing `Time Period` (start and end dates) from the same `Title` column.
* **Feature Engineering:**
    * Calculated the total runtime duration in `Months` based on the extracted `Time Period`.
* **Top-Performer Analysis:**
    * Identified the anime with the highest viewer `Score`.
    * Determined which anime has the highest number of episodes.
    * Found the longest-running anime based on its total runtime in months.

---

## 💻 Technologies Used
* **Python 3**
* **Pandas:** For data manipulation, cleaning, and analysis.
* **NumPy:** For numerical operations.
* **Jupyter Notebook:** As the environment for interactive analysis.

---

## 🚀 Setup and Installation

To run this project on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Heet-Jamariya/Anime-Project.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Anime-Project
    ```
3.  **Create and activate a virtual environment:**
    ```bash
    # Create the virtual environment
    py -m venv .venv

    # Activate the virtual environment (Windows)
    .\.venv\Scripts\activate
    ```
    *Note: For macOS/Linux, the activation command is `source .venv/bin/activate`.*

4.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

5.  **Run the notebook:**
    Open the `Anime_Project.ipynb` file in your preferred environment (like VS Code or Jupyter) to view and execute the analysis.

---
## 📈 Data Source
The dataset used for this analysis is `anime.csv`, which is included in this repository.

# AccuKnox AI/ML Trainee Assessment

This repository contains my work for the AccuKnox AI/ML Trainee assessment. It covers Python programming, API integration, database operations, data processing, and related technical tasks.

## Repository Contents

### Problem Statement 1: Python and Database Tasks

- **P1_1.ipynb - API Data Retrieval and Storage**  
  Retrieves book information from an external REST API, processes the JSON response, stores book records in SQLite, and displays the stored data.

- **P1_2.ipynb - Student Score Analysis and Visualization**  
  Retrieves student score data, calculates the average score, and visualizes individual scores using a bar chart.

- **P1_3.ipynb - CSV Data Import into SQLite**  
  Reads user information from a CSV file and inserts the records into a SQLite database.

- **P1_4.ipynb - Python Project Reference**  
  Contains the Python project reference and supporting details for the assessment.

## Technologies Used

- Python 3
- Jupyter Notebook
- REST APIs and JSON
- SQLite and SQL
- CSV
- Matplotlib
- Requests

## Getting Started

### Prerequisites

- Python 3
- Jupyter Notebook
- Internet connection for API-based tasks

### Installation

Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

Create a virtual environment:

**Windows PowerShell**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Linux/macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the required packages:

```bash
python -m pip install -r requirements.txt
```

If Jupyter Notebook is not already installed, install it using:

```bash
python -m pip install notebook
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, open the `.ipynb` files directly in VS Code with the Python and Jupyter extensions installed.

## Running the Notebooks

Open the required notebook and execute its cells in order.

1. Run `P1_1.ipynb` to execute the books API and SQLite workflow.
2. Run `P1_2.ipynb` to process student scores and generate the visualization.
3. Run `P1_3.ipynb` to import CSV records into SQLite.
4. Review `P1_4.ipynb` for the Python project reference.

Ensure that any required input files are available and that the necessary dependencies are installed before execution.

## Database and Data Handling

SQLite is used for local database operations. Database files may be generated during execution and can be recreated by running the relevant notebook.

API responses and outputs may vary depending on the available data and external service availability.

## Assumptions and Limitations

- External APIs require an internet connection and may return changing data.
- Input files and dependencies must be available before running the notebooks.
- Data validation and error handling depend on each implementation.
- The solutions demonstrate the programming and database concepts relevant to the assessment.

## Author

**Amsha Hegde**  
AI/ML Engineering

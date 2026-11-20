# Loan Repayment Analysis

Jupyter notebook and dataset for loan repayment analysis.

## Project Files

```text
5024CMD-Data-Science/
├── analysis.ipynb      # Main analysis notebook
├── data/
│   └── loan_data.csv   # Input dataset
├── figures/            # Exported charts
└── requirements.txt    # Python dependencies
```

## Requirements

- Python 3.12 (with SQLite >= 3.37.0)

## How to Run

1. Clone the repository and enter the project folder:

   ```bash
   git clone https://github.com/nightboon/5024CMD-Data-Science.git
   cd 5024CMD-Data-Science
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   ```

   - **Windows (PowerShell):**
     ```powershell
     .venv\Scripts\Activate.ps1
     ```
   - **macOS / Linux:**
     ```bash
     source .venv/bin/activate
     ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter and open `analysis.ipynb`:

   ```bash
   jupyter notebook analysis.ipynb
   ```

5. Run all cells from top to bottom. Running the notebook automatically generates `loan_project.db`, `model_selection.json`, and the figures in `figures/`.

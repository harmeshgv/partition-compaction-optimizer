# partition-compaction-optimizer
An optimization algorithm for large-scale data platforms that selects high-impact partitions for compaction based on file size, delete overhead, and query frequency, while staying under a strict compute budget.

## Run Locally

Create and activate a virtual environment

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# or
source venv/bin/activate  # For Linux/macOS
```

Update Pip

```bash
python -m pip install --upgrade pip
```

Install dependencies

```bash
pip install -r requirements.txt
```
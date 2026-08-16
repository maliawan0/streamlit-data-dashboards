# Streamlit Data Dashboards

A set of small Streamlit apps for exploring and visualising data in the browser — each one runnable on its own with a single command.

## The apps

| File | What it does |
|---|---|
| [`project1.py`](project1.py) | **CSV explorer** — upload any CSV, inspect the dataset, filter interactively, and visualise the result |
| [`charts.py`](charts.py) | Chart-type walkthrough — line, bar, area and map rendering in Streamlit |
| [`lhr.py`](lhr.py) | Lahore-focused dataset dashboard |
| [`ytvid.py`](ytvid.py) | YouTube video embedding and media handling |
| [`practice.py`](practice.py) | Widget scratchpad — sliders, selectboxes, layout containers, caching |

## The main app

`project1.py` is the substantial one. It takes an arbitrary uploaded CSV and gives you:

- Dataset preview with shape, dtypes and summary statistics
- Interactive column filters that narrow the working set
- Charts generated from whatever columns you select

Nothing is hardcoded to a particular dataset — it adapts to the file you upload.

## Running them

```bash
pip install streamlit pandas
streamlit run project1.py
```

Swap the filename for any other app in the table. Streamlit opens `http://localhost:8501` automatically.

## Stack

Streamlit · pandas · Python

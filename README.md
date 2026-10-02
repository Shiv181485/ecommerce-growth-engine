# Streamlit Deployment

Main file: `app.py`

Required runtime dependencies are declared in the root `requirements.txt`. The app uses `data/` relative to `app.py`, so it works on Streamlit Cloud.

Deploy with:
- Branch: `main`
- Main file: `app.py`

# Ecommerce Growth Analytics Dashboard

Streamlit dashboard for ecommerce growth analysis using **Pandas + Plotly + Streamlit**.

## Streamlit Cloud deployment

1. Upload/push this project to a GitHub repository.
2. Open Streamlit Community Cloud.
3. Select the repository and branch.
4. Set **Main file path** to:
   `app.py`
5. Deploy.

The app already includes:
- `app.py` — Streamlit entry point
- `dashboard.py` — dashboard source
- `visualization.py` — Plotly chart functions
- `data/` — all required CSV files
- `requirements.txt` — Python dependencies
- `.streamlit/config.toml` — Streamlit configuration
- `runtime.txt` — Python version hint

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Project modules

- Marketing Channel & Efficiency
- Conversion Funnel & UX Optimization
- Product Performance & Refund Analysis
- Customer Lifecycle & Repeat Behaviour

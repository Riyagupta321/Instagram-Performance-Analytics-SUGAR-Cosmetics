# Sugar Cosmetics · Instagram Performance Analytics (Streamlit)

Interactive dashboard: KPIs, trends, content/timing analysis, engagement funnel, hashtags,
audience & growth, top posts, auto-insights, optional AI Q&A.

## Run locally
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## Deploy (Streamlit Community Cloud)
1. Push this folder to a public GitHub repo (`app.py`, `requirements.txt`, `data/`, `.streamlit/config.toml`).
2. Go to share.streamlit.io → **Create app** → pick repo, branch `main`, main file `app.py`.
3. (Optional AI tab) Advanced settings → Secrets: `ANTHROPIC_API_KEY = "sk-ant-..."`
4. Deploy → copy the public URL into your resume / LinkedIn / README.

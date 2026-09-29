### Anshika Patel — Backend, Data & AI

Final-year B.Tech Computer Science student (graduating July 2027). I build backend and data systems end to end — ingest, store, transform, serve — and I care about the parts that break in production: schema design, query safety, and pipelines that don't create duplicate rows.

`Python` `SQL` `PostgreSQL` `JavaScript` `Node.js` `React.js` `Docker` `AWS` `Scrapy` `Prefect` `Streamlit`

**890 contributions in the last year.** · 📄 [1-page CV](ADD_LINK) · 🌐 [Portfolio](https://anshika-patel.netlify.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/anshika-patel-60ad)

---

## 🧠 AI SQL Analytics Assistant
Ask a PostgreSQL database questions in plain English; get back a safe, executed, visualised answer.

**Six-stage pipeline:** read live schema → generate one query with an LLM → validate SELECT-only → execute with LIMIT injection + 15s timeout → auto-select chart → explain result.

The LLM is treated as **untrusted input**: a dedicated validation layer blocks stacked statements and DDL/DML keywords before anything reaches the database.

`Python` · `Streamlit` · `PostgreSQL` · `Plotly`
**→ [Repository](https://github.com/its-anshikapatel/AI-SQL-Assistant)** · **Live demo:** ADD_STREAMLIT_URL · **Result:** on a [N]-question test set, answers in ~[B]s vs ~[A]min by hand

---

## 📊 Eurozone Investment Affordability Index
End-to-end data pipeline turning scraped listings + live Eurostat macroeconomics into a comparable investment score across **19 countries**.

- **Scrape** — custom Scrapy spider, validation + JSON audit trail, upsert into PostgreSQL
- **Fetch** — live Eurostat API: median household income + House Price Index
- **Score** — custom 0–100 affordability score per listing (price-to-income, HPI position, price per m²)
- **Orchestrate** — Prefect: two concurrent branches, automatic retries
- **Serve** — Streamlit dashboard: KPIs, filters, Plotly charts, colour-coded Folium map

`Python` · `Scrapy` · `Prefect` · `PostgreSQL` · `SQLAlchemy` · `Streamlit` · `Folium`
**→ [Repository](https://github.com/its-anshikapatel/Eurozone)** · **Dashboard:** ADD_URL

---

## 💰 FinTech — Smart Finance Management
Full-stack finance platform: expense tracking, budgets and spending-pattern insights.

`React` · `Next.js` · `Node.js` · `Express` · `MongoDB` · `Tailwind CSS` · `JWT`
**→ [Repository](https://github.com/its-anshikapatel/FinTech)** · **Live demo:** ADD_VERCEL_URL

---

📩 anshikapatel383@gmail.com · 📄 [CV](ADD_LINK) · 🌐 [Portfolio](https://anshika-patel.netlify.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/anshika-patel-60ad)

# Eye-O — Product Idea Oracle

**Live Demo:** [https://eyeo.app](https://eyeo.app)

Eye-O turns rough product ideas into investor-ready briefs in 60 seconds. 
Get a viability score, brand kit, risk map, competitor scan, domains, and a launch plan — instantly.

---

## ✨ Features
- Structured JSON analysis via OpenAI
- Names, tagline, color palette, mood keywords
- Risks → counter-moves, opportunities, similar products
- Domain/handle checks
- Export results (PDF, copy/share ready)

---

## 🛠️ Tech Stack
- FastAPI, Python 3.11+
- Jinja2 Templates
- OpenAI API
- HTML / CSS (static assets)

---

<img width="1884" height="1388" alt="SS1a" src="https://github.com/user-attachments/assets/5ec711cb-f2a8-4731-88ec-4537cd488872" />

<img width="2254" height="1704" alt="SS2a" src="https://github.com/user-attachments/assets/32c55fac-e322-41af-973b-bf5238dd2125" />

<img width="2324" height="1602" alt="SS3a" src="https://github.com/user-attachments/assets/ca86b1b9-66af-4faf-8a79-ed80ffce119c" />

<img width="2332" height="1646" alt="SS4a" src="https://github.com/user-attachments/assets/97bd74bc-5eb2-416e-876f-7e9aa6131aac" />

<img width="2422" height="1180" alt="SS5a" src="https://github.com/user-attachments/assets/7872b176-3976-4011-bea4-4ccfadd8a012" />

## 🚀 Local Development
```bash
git clone https://github.com/moody-creative/eye-o.git
cd eye-o

python -m venv venv
source venv/bin/activate   # or .\venv\Scripts\activate on Windows

pip install -r requirements.txt
cp .env.example .env       # Add your own OPENAI_API_KEY=sk-xxxx
uvicorn main:app --reload

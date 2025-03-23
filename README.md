# PubMed Fetcher CLI  

A Python CLI tool to fetch and filter research papers from PubMed, identifying authors affiliated with pharmaceutical/biotech companies.  

## 📌 Features  
- Fetches research papers using the PubMed API  
- Filters out academic institutions  
- Identifies pharma/biotech-affiliated authors  
- Saves results as CSV  

## 🚀 Installation  
```sh
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
poetry install


poetry run get-papers-list "cancer research" -f results.csv

🔹 **Commit & Push README:**  
```powershell
git add README.md
git commit -m "Added README documentation"
git push origin main

 Run Full Tests & Verify Code
poetry run pytest

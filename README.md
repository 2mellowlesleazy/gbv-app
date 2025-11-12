# GBV Countdown — Botswana Crime Statistics

An interactive **Streamlit app** that demonstrates how data can be used to raise awareness about gender-based violence (GBV) in Botswana.  
It estimates the average time between reported sexual offence cases (based on 2020 data) and shows a live countdown to the next estimated reported case.

![Screenshot of app](assets/screenshot.png)  <!-- optional image -->

---

## 📊 Data Sources
- **Crime Statistics Report 2020** — Statistics Botswana (Sexual offences = 9.0% of 7,386 total offences).  
- **Afrobarometer Dispatch 594** — Botswana sees GBV as a top priority for government and societal action (2023).

---

## 🧮 How the countdown works
- Reported sexual offences in 2020: **665** decided cases.  
- Assuming uniform distribution across the year, average time between reported cases ≈ **13 hours**.  
- The app uses this interval to simulate a countdown timer for awareness and demonstration.  
- For demo purposes, the app can run in accelerated mode (×10 or ×60 speed).

---

## ⚙️ Run locally
```bash
pip install -r requirements.txt
streamlit run gbv_countdown_app.py

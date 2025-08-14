# 📸 CamSnare

*CamSnare* is a lightweight Python tool that detects surveillance cameras in your vicinity using image input and metadata analysis. Designed for privacy-conscious users, civic tech advocates, and developers exploring ethical AI, CamSnare helps you reclaim awareness in monitored spaces.

---

## 🚀 Features

- 🔍 *Camera Detection*: Identify visible surveillance cameras in uploaded images  
- 🧠 *Metadata Analysis*: Extract GPS and timestamp data to map surveillance zones  
- 📊 *Dashboard-ready Output*: Structured results for integration with Streamlit or Power BI  
- 🛠️ *Modular Design*: Easily extendable for civic audits, smart city mapping, or AR overlays

---

## 📦 Use Cases

| Scenario           | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| 🏙️ Urban Mapping  | Audit surveillance density in public spaces for transparency reports        |
| 🧳 Travel Safety  | Check hotel rooms or rentals for hidden cameras                             |
| 🛡️ Civic Advocacy | Empower communities to visualize and challenge over-surveillance            |
| 🧪 Dev Sandbox    | Experiment with computer vision and ethical AI applications                 |

---

## 🧭 Vision & Impact

CamSnare is more than a tool — it's a step toward *empowering individuals with surveillance awareness* in an increasingly monitored world. Whether you're a privacy-conscious traveler, a civic tech advocate, or a developer exploring ethical AI, CamSnare offers:

- 🛡️ *Transparency*: Know when and where you're being watched  
- 🧠 *Autonomy*: Make informed decisions about your environment  
- 🌍 *Social Impact*: Enable communities to audit surveillance density and advocate for responsible tech use

This project is designed to evolve into a *scalable, deployable system* that can serve both personal and public interest — from smart cities to grassroots privacy movements.

---

## 🧰 Tech Stack

- Python (OpenCV, PIL, ExifRead)  
- Streamlit (optional dashboard integration)  
- Power BI (for civic data visualization)  
- GitHub Actions (CI/CD ready)

---

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/camsnare.git
cd camsnare
pip install -r requirements.txt
python camsnare.py --image path/to/image.jpg

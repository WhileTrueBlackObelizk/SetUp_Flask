# SetUp_Flask
# 🚀 Flask Project Template

Dieses Repository ist ein **Standard-Template für Flask-Projekte**.  
Es bietet eine sofort einsatzbereite Struktur, um neue Projekte schneller und sauberer zu starten.  
Ideal für API-Projekte, kleine Webapps oder MVPs.

---
Grund-Projektstruktur vorhanden!

---

## 🛠️ Installation & Setup

1. Repository klonen oder über **„Use this template“** ein neues Repo erstellen:
   ```bash
   git clone https://github.com/WhileTrueBlackObelizk/SetUp_Flask.git
   cd SetUp_Flask

python3 -m venv venv

macOS/Linux: source --> venv/bin/activate  
Windows PowerShell --> venv\Scripts\activate    

Abhängigkeiten installieren:
pip install -r requirements.txt
cp .env.example .env

---

▶️ Starten der Flask-App
Entwicklungsmodus (Debug)
---> python run.py

oder via Flask CLI:

macOS/Linux---> export FLASK_APP=run.py       
Windows---> set FLASK_APP=run.py        

--> flask run --debug

App läuft dann unter http://127.0.0.1:5000/.

---

🧪 Tests ausführen
-->pytest<-- falls pytest installiert ist
>oder<
-->python -m unittest<--

---

📦 Docker (optional)

Falls ein Dockerfile vorhanden ist:

docker build -t flask-template .
docker run -p 5000:5000 flask-template



---

Wofür dieses Template dient

Schneller Start für neue Flask-Projekte

Einheitliche Struktur, Tests & Konfiguration

Best Practices (App Factory Pattern, Blueprints, .env, Logging)

---

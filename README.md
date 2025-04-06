# 🌸 Portfolio Marina – Fullstack React + FastAPI

Projet personnel pour expérimenter le développement fullstack avec ETL, affichage de données, API et frontend dynamique avec Tailwind.

---

## ⚙️ Initialisation du projet

### 🐍 Backend (FastAPI)
```bash
python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
pip install fastapi uvicorn
```
Créer ensuite le fichier main.py avec ton API FastAPI.



### ⚛️ Frontend (React + Vite + Tailwind) :
npm create vite@latest frontend -- --template react
cd frontend
npm install
npm install -D tailwindcss postcss autoprefixer
npm install tailwindcss @tailwindcss/vite
npm install react react-dom



### 🚀 Lancer le projet
Backend :
uvicorn main:app --reload
Accès : http://localhost:8000

Frontend : 
npm run dev



### 📁 Structure prévue
- frontend/ – App React (Vite + TailwindCSS + AG-Grid)
- backend/ – API FastAPI (ETL, traitement CSV, mapping)



### 💡 Objectif du projet
Construire une application web qui :
- Extrait, transforme et affiche des données d’un fichier CSV
- Permet à l’utilisateur de mapper/valider ces données
- Stocke le tout en base de données


Développé avec ❤️ par Marina
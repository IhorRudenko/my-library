📚 Bibliothek App – Testaufgabe

Dieses Projekt wurde im Rahmen der technischen Einstellungsaufgabe für die Stelle Fachinformatiker für Anwendungsentwicklung  erstellt.


### 🚀 Funktionen

📖 Liste aller Bücher anzeigen
➕ Neues Buch hinzufügen
🔍 Bücher suchen und filtern nach Titel oder Autor
❌ Buch löschen
📌 Bücher zur Leseliste hinzufügen und entfernen
✅ Status der gelesenen Bücher verwalten
🌓 Hell- und Dunkelmodus
🖥️ Wechsel zwischen Listen- und Rasteransicht
📱 Responsive und adaptive Benutzeroberfläche
💾 Speicherung der Bücher in einer lokalen Datei books.json (Backend)
🛠 Technologien


### 🔹 Backend

Node.js
Express
TypeScript
Datenspeicherung in JSON (books.json)


### 🔹 Frontend

React
TypeScript
Axios (für HTTP-Anfragen)
SCSS


### 📦 Lokale Ausführung

🔧 Backend starten

cd backend
npm install
npx ts-node server.ts

🌐 Frontend starten

cd frontend
npm install
npm start


### 🧭 Projektstruktur

my-library/
├── backend/
│   ├── books.json           # Lokale \"Datenbank\" für Bücher
│   ├── server.ts            # Express-Server
│   ├── package.json         # Abhängigkeiten
│   └── tsconfig.json        # TypeScript-Konfiguration
│
├── frontend/
│   ├── src/
│   │   ├── App.tsx
│   │   ├── components/
│   │   │   ├── AddBook.tsx
│   │   │   ├── BookList.tsx
│   │   │   ├── ReadingList.tsx
│   │   │   ├── Tabs.tsx
│   │   │   ├── ViewToggle.tsx
│   │   │   └── SearchBar.tsx
│   ├── public/
│   ├── package.json
│   └── tsconfig.json
│
├── .gitignore
├── README.md


### 🌐 Deployment

- **Frontend** [Vercel](https://vercel.com):  
  🔗 https://vercel.com/ihor-rudenkos-projects/library-app

- **Backend** [Render](https://render.com):  
  🔗 https://dashboard.render.com/web/srv-cvilvlhr0fns73cqkgu0

- **Database** [MongoDB](https://cloud.mongodb.com/v2/67e48e3f1277ab205688d46a#/clusters)


### 🌐 Live-Demo

Dieses Projekt ist online verfügbar unter:
https://library-app-git-library-debug-ihor-rudenkos-projects.vercel.app/


### 📝 Zukünftige Verbesserungen

✏️ Bücher bearbeiten (nicht nur löschen)
🔐 Benutzer-Login-System
💽 Umstieg von books.json auf echte Datenbank (z. B. MongoDB, SQLite)
...


### 📧 Kontakt

Autor: Ihor Rudenko📬 
E-Mail: i.rudenko108@gmail.com🌐 
GitHub: github.com/IhorRudenko




🛠 Dieses Projekt befindet sich noch in der Entwicklung. Feedback ist willkommen!


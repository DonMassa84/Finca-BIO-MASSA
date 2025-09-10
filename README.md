# README - Finca BIO MASSA Bauernregistrierung

## 🌱 Projektübersicht

Finca BIO MASSA ist eine Webanwendung zur Registrierung von Bio-Bauern für eine Kakao-Kooperative. Die Anwendung ermöglicht es Landwirten, sich online zu registrieren und verwaltet die Daten in einer MongoDB-Datenbank.

## ✨ Funktionen

- **Mehrsprachige Unterstützung**: Französisch, Spanisch und Deutsch
- **Responsive Design**: Optimiert für PC, Tablet und Smartphone
- **Datenpersistenz**: Speicherung der Registrierungen in MongoDB
- **Benutzerfreundliche Oberfläche**: Intuitive Formulare und Bestätigungen
- **Kontaktinformationen**: Vollständige Kontaktdaten der Projektverantwortlichen

## 🚀 Installation und Einrichtung

### Voraussetzungen
- Node.js und npm
- MongoDB-Datenbank (lokal oder gehostet)
- Git

### Schritte zur Installation

1. Repository klonen:
```bash
git clone https://github.com/DonMassa84/Finca-BIO-MASSA.git
cd Finca-BIO-MASSA
```

2. Abhängigkeiten installieren:
```bash
npm install
```

3. Umgebungsvariablen konfigurieren:
Erstellen Sie eine `.env` Datei im Hauptverzeichnis:
```
MONGODB_URI=Ihre_MongoDB_Verbindungszeichenfolge
PORT=3000
API_URL=http://localhost:3000
```

4. Anwendung starten:
```bash
npm start
```

5. Im Browser öffnen:
Öffnen Sie `http://localhost:3000` in Ihrem Browser.

## 📦 Projektstruktur

```
Finca-BIO-MASSA/
├── public/
│   ├── index.html          # Haupt-HTML-Datei
│   ├── style.css           # Styling
│   └── script.js           # Client-seitige Skripte
├── server/
│   ├── server.js           # Express-Server
│   ├── routes.js           API-Routen
│   └── database.js         # Datenbankverbindung
├── package.json
└── README.md
```

## 🌐 Deployment auf Railway

1. Erstellen Sie ein Konto auf [Railway](https://railway.app)
2. Verbinden Sie Ihr GitHub-Repository mit Railway
3. Fügen Sie Ihre Umgebungsvariablen in Railway hinzu
4. Deployment wird automatisch durchgeführt bei jedem Push zum Main-Branch

## 📋 API-Endpunkte

- `GET /api/farmers` - Abrufen aller registrierten Bauern
- `POST /api/farmers` - Speichern eines neuen Bauern

## 👥 Kontaktinformationen

### Kamerun
- **Pablo Massa**: +237 655 310 460
- **Lydie Meyo**: +237 697 121 480

### Koordination (Deutschland)
- **Daniel Massa**: +49 178 2989360
- **E-Mail**: Daniel.Alfonsin.Massa.IT@protonmail.com
- **Projektkoordination**: massa.consulting.it@pm.me

### Ansprechpartner Familie Massa
- **Michael Massa**: +49 178 2180114
- **E-Mail**: DonMassa-Business@proton.me
- **Strategische Partnerschaften**: daniel.asset.network@proton.me

## 🔧 Technologien

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Datenbank**: MongoDB
- **Hosting**: Railway
- **Version Control**: GitHub

## 📄 Lizenz

Dieses Projekt ist urheberrechtlich geschützt. Alle Rechte vorbehalten.

## 🤝 Beitragen

Beiträge sind willkommen! Bitte erstellen Sie einen Fork des Projekts und senden Sie einen Pull Request mit Ihren Verbesserungen.

## 🐛 Fehler melden

Bitte melden Sie Fehler oder Probleme über die GitHub Issues Seite des Projekts.

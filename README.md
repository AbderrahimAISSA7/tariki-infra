# 🐳 Tariki Infrastructure

Infrastructure Docker pour orchestrer tous les services Tariki.

## 🎯 Objectif

Centraliser et orchestrer :

- Backend (API)
- Frontend
- Base de données PostgreSQL
- pgAdmin
- (Future) Monitoring & DevOps

---

## 🧠 Architecture globale

    ┌─────────────┐
    │  Frontend   │
    └──────┬──────┘
           │
           ▼
    ┌─────────────┐
    │  Backend    │
    └──────┬──────┘
           │
           ▼
    ┌─────────────┐
    │ PostgreSQL  │
    └─────────────┘
           │
           ▼
    ┌─────────────┐
    │  pgAdmin    │
    └─────────────┘

---

## 📦 Services

### Backend
- API principale

### Frontend
- Interface utilisateur

### Database
- PostgreSQL

### Admin DB
- pgAdmin

---

## 🔄 Workflow global


Utilisateur
↓
Frontend
↓
Backend
↓
Database


---

## 🚀 Lancement

Objectif :
- démarrer tous les services ensemble
- environnement stable et reproductible

---

## 🔮 Évolution future

Ajout possible :

- Grafana (monitoring)
- Prometheus (metrics)
- Gitea (git interne)
- CI/CD pipeline
- logs centralisés

---

## 🧠 Philosophie

- séparation claire des services
- architecture scalable
- environnement professionnel

---

## 💥 Objectif final

Avoir une plateforme prête pour :
- développement rapide
- déploiement futur
- montée en charge

- développement rapide
- déploiement futur

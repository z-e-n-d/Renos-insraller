
# Renos

**Renos** is an open-source TikTok-style web app MVP — built with Flask + SQLite — that supports:

- User registration and login (with avatar upload)
- Video uploads with captions
- Liking videos
- Commenting on videos
- Fully functional frontend with mobile layout
- All data saved to a `.db` (SQLite) file (Microsoft database format)

## 🚀 Quick Start

```bash
python setup_renos.py
python renos/app.py
```

Then open `renos/frontend/index.html` in your browser.

## 📂 Structure

- `renos/app.py` — backend server
- `renos/renos.db` — the database (saved automatically)
- `renos/videos/` — uploaded videos
- `renos/avatars/` — uploaded avatars
- `renos/frontend/` — frontend files

## 🤝 License

MIT — feel free to fork and use this as your own foundation!

---

This script is an **all-in-one installer and generator** — just run `setup_renos.py` to install dependencies and generate the project.

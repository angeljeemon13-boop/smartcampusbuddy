# smartcampusbuddy 

**SmartCampusBuddy** — a lightweight student helper web app.

## What's new in this expanded repo
- Basic user authentication (register/login) with session-based auth.
- Unit tests for the recommender (pytest).
- Dockerfile to containerize the app.
- GitHub Actions CI workflow to run pytest on push.
- `git_init.sh` script to create a clean commit history locally.
- Project report PDF personalized (placeholders) and UML/architecture diagrams.

## Quick start (local)
1. Create and activate venv:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
2. Run:
   ```bash
   python app.py
   ```
3. Open `http://127.0.0.1:5000/`

## Docker (optional)
Build and run:
```bash
docker build -t smartcampusbuddy .
docker run -p 5000:5000 smartcampusbuddy
```

## Git reproducible history
Run `bash git_init.sh "Your Name" "your.email@example.com"` to create a local git repo with structured commits.


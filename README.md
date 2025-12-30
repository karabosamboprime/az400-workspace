# Express Hello World Boilerplate

Minimal Node + Express backend that responds to `/` and `/health`.

## Run locally

1. Create the branch and add files:
```bash
git checkout -b add/express-backend
# create files (package.json, index.js, .gitignore, README.md)
git add .
git commit -m "chore: add express hello-world backend"
```

2. Install dependencies and run:
```bash
npm install
npm start
# or for development with auto-restart (requires nodemon):
npm run dev
```

3. Test:
```bash
curl http://localhost:3000/
# -> Hello from Express!

curl http://localhost:3000/health
# -> {"status":"ok"}
```

If your repository is currently empty you may need to first create an initial branch in the remote or push this branch as the main branch:
```bash
git push -u origin add/express-backend
```

## Notes
- Change the start script or add TypeScript later if needed.
- Add CI, Dockerfile, or additional routes as next steps.
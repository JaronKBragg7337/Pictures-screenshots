# 📸 Jaron's Media Library

A persistent, public media archive — upload once, accessible to any AI assistant or human collaborator without re-uploading.

## For AI Assistants

All images are publicly accessible. Reference any image directly:

```
https://raw.githubusercontent.com/JaronKBragg7337/Pictures-screenshots/main/imgs/FILENAME.jpeg
```

Browse all files:
- **Gallery viewer:** https://github.com/JaronKBragg7337/Pictures-screenshots/blob/main/gallery.html
- **File tree:** https://github.com/JaronKBragg7337/Pictures-screenshots/tree/main/imgs
- **GitHub API:** https://api.github.com/repos/JaronKBragg7337/Pictures-screenshots/contents/imgs

## Structure

```
Pictures-screenshots/
├── gallery.html       ← Visual browser (open in browser to view all images)
├── README.md
└── imgs/              ← Drop all photos/screenshots here
    ├── IMG_9490.jpeg
    ├── IMG_9491.jpeg
    └── ...
```

## Adding Images

**Option 1 — GitHub web UI (no install):**
1. Go to the `imgs/` folder on GitHub
2. Click **Add file → Upload files**
3. Drag and drop your images → Commit

**Option 2 — Git CLI:**
```bash
git clone https://github.com/JaronKBragg7337/Pictures-screenshots
cd Pictures-screenshots
mkdir -p imgs
# copy your images into imgs/
git add . && git commit -m "Add photos" && git push
```

---
*Public repo — images are visible to anyone with the URL.*

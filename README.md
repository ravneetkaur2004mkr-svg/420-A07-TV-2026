# To-Do List Practical Project

This folder contains the `test1/index.html` file for the practical assignment.

## Features
- Semantic HTML: `header`, `main`, and `footer`
- Viewport meta tag for mobile devices
- Fetches 12 todos from JSONPlaceholder using `async` / `await`
- Shows each task title and completion status
- Shows a loading message and a friendly error message
- One column on phones, two columns from 768px, and three columns from 1024px
- Live completed-task counter
- Checkboxes let you change task completion status in the page

## Run it
Open `index.html` in a browser while connected to the internet. If your browser blocks requests when opening a local file, run it with the VS Code Live Server extension.

## GitHub submission
From the folder that contains `test1`, run:

```bash
git init
git add test1/index.html
git commit -m "Build responsive to-do list with API data"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with your own GitHub repository URL.

After pushing, open the commit on GitHub and copy its URL. It should look like:
`https://github.com/YOUR-USERNAME/YOUR-REPOSITORY/commit/COMMIT-ID`

Paste that commit URL into the Google Form.

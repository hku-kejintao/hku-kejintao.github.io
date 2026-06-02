# Jintao Ke Personal Homepage

Static personal homepage for GitHub Pages.

## Local Preview

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish on GitHub Pages

For a personal GitHub Pages site, create a public repository named:

```text
hku-kejintao.github.io
```

Then push this folder to the repository's `main` branch. GitHub Pages will serve it at:

```text
https://hku-kejintao.github.io
```

If using GitHub CLI:

```bash
gh auth login
gh repo create hku-kejintao.github.io --public --source=. --remote=origin --push
```

## Updating Videos

The current video section links to the HKU Smart Mobility Lab YouTube channel:

```text
https://www.youtube.com/@hkusmlab/featured
```

To embed specific videos, replace the placeholder in `index.html` with YouTube iframe embed links.

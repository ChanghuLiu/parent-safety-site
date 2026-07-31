# Parent Safety site

Static English and Chinese public pages for Parent Safety.

## Contents

- `index.html` and `zh.html`: home
- `privacy/index.html` and `privacy/zh.html`: privacy policy
- `terms/index.html` and `terms/zh.html`: terms of use
- `support/index.html` and `support/zh.html`: support
- `assets/styles.css`: shared responsive styles

The site uses HTML and CSS only. It has no JavaScript, analytics, cookies, ads, tracking, database, or server-side application.

## Local preview

From this directory, run a static file server such as:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080/`.

## Publish with GitHub Pages

1. Create a public GitHub repository named `parent-safety-site` under `ChanghuLiu`.
2. Push this repository's `main` branch.
3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then choose **Save**.
6. After deployment completes, verify `https://changhuliu.github.io/parent-safety-site/` and each legal/support link.

The Android application expects this GitHub Pages project URL and links Chinese readers to the corresponding `zh.html` file.

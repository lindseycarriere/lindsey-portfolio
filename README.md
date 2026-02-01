# Personal Portfolio

A personal portfolio site built with [Hugo](https://gohugo.io/), used for CV, skills, and project highlights.

## Technology

- **Hugo** — A modern, Golang-based static site generator.

## Installation

Install Hugo on your machine. Pick one method that fits your OS.

**macOS:**
```bash
brew install hugo
```

**Linux:**
```bash
sudo apt install hugo
```

**Or** download the binary for your OS from [Hugo releases](https://github.com/gohugoio/hugo/releases).

Check the install:
```bash
hugo version
```

## Run Locally

From the project root:

```bash
hugo server -D
```

- **`-D`** includes content marked as draft (useful while editing).

Then open **http://localhost:1313** in your browser. The site reloads when you change content or themes.

## CICD

The site is built and deployed to **GitHub Pages** on every push to `main` branch via [GitHub Actions](.github/workflows/hugo.yaml) (see [Hugo: Host on GitHub Pages](https://gohugo.io/host-and-deploy/host-on-github-pages/)).

**One-time setup:** In your repo on GitHub, go to **Settings → Pages**. Set **Source** to **GitHub Actions**. After the first push to `main`, the workflow will run and your site will be available at either `https://<username>.github.io/<repo>/` or your user/org Pages URL.


# Vite Preconfigured Starter Templates

A curated collection of zero-setup Vite templates to jumpstart your frontend development without spending time repeating boilerplate configurations.

---

## Why This Project

Setting up modern toolchains (like Vite + Tailwind CSS + shadcn/ui) often involves repeating the same setup steps, installing boilerplate packages, and tweaking configuration files. It's time-consuming and prone to missing small details.

This repository solves that problem: **clone, install dependencies, and start coding immediately.**

---

## Available Templates

Each template lives in its own dedicated branch:

| Branch | Tech Stack |
| :--- | :--- |
| `main` | Vite + TypeScript |
| `tailwind` | Vite + TypeScript + Tailwind CSS |
| `shadcn` | Vite + React + TypeScript + Tailwind CSS + shadcn/ui |

*More templates and frameworks will be added in future updates.*

---

## Getting Started

You can choose either of the following methods to fetch a template:

### Method 1: Clone a Single Branch (Recommended)

To avoid downloading the entire repository history and other branches, clone only the branch you need:

```bash
git clone --branch vite-react-ts-tailwind-shadcn --single-branch https://github.com/<your-username>/<your-repo-name>.git my-app

cd my-app
npm install
npm run dev
```

### Method 2: Standard Clone & Switch Branch

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git my-app
cd my-app

git checkout <branch-name>

npm install
npm run dev
```
# web-toolkit

**A toolkit of JS functions, recommended tools and best practice guidelines.**

---

## 🚀 Project Structure

```code
/
├── public/
│   ├── robots.txt
│   └── favicon.ico
├── src/
│   ├── components/
│   │   └── *.astro
│   └── pages/
│       └── index.astro
└── package.json
```

- `src/pages/`: Astro looks for `.astro` or `.md` files in this directory. Each page is exposed as a route based on its file name.

- `src/components/`: Astro & React components should be placed in this directory.

- `public/`: Any static assets, like images, can be placed in this directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command      | Action                                      |
|:-------------|:--------------------------------------------|
| `yarn`       | Installs dependencies                       |
| `yarn start` | Starts local dev server at `localhost:3000` |
| `yarn build` | Build your production site to `./dist/`     |

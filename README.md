# LexFG site

LexFG is a Fullstack, Web3 Law Firm for Blockchain Startups, NFT Investors & Crypto Issues

This site is hosted and managed on [Netlify](https://www.netlify.com/)

## 🚀 Project Structure

General overview of file structure:

```
/
├── public/
│   └── (where the assets (fonts, images) are located)
├── src/
│   ├── components/
│   ├── pages/
│   |   └── (where the individual pages are located)
│   └── styles/
│       └── (where all of the styling files are located)
└── package.json
```

Astro files are located in the `pages/` directory.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                                                        | Action                                           |
| :------------------------------------------------------------- | :----------------------------------------------- |
| `npm install`                                                  | Installs dependencies                            |
| `npm run dev`                                                  | Starts local dev server at `localhost:3000`      |
| `npm run build`                                                | Build site to `./dist/`                          |
| `npm run preview`                                              | Preview build locally, before deploying          |
| `npm run astro ...`                                            | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help`                                         | Get help using the Astro CLI                     |
| `sass --watch src/styles/sass/style.scss:src/styles/style.css` | Compile the Sass files to css                    |

For more information on Astro, check [the documentation here](https://docs.astro.build)

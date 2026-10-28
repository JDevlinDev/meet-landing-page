# Newbie FEM Starter Pack 🎒

A friendly starter template for [Frontend Mentor](https://www.frontendmentor.io) challenges.

Most newbie projects start with one HTML file and one CSS file, and that's a great way to learn. But when you're ready for a small step up, this pack gives you a setup that leaves room for your own flair, without making things complicated.

## Why Sass?

Sass is CSS with superpowers. It still compiles to plain CSS, but along the way you get things like:

- **Nesting that fits BEM:** write `&__title` inside `.card` and get `.card__title`, so a whole component lives in one tidy block.
- **Reusable breakpoints:** `@include breakpoints("md") { ... }` instead of retyping media queries, with a warning if you mistype a breakpoint name.
- **Small, focused files:** split styles into modules (`base/`, `components/`, `layout/`…) and pull them together with `@use` and `@forward`.
- **Loops and functions:** this template turns a single color map into CSS custom properties with an `@each` loop, and converts design pixels to rem with `rem(24)`.

## Why Parcel?

A **bundler** takes all your project files (HTML, Sass, images) and turns them into a small, optimized set of files that's ready for the web. Your Sass gets compiled, your code gets minified, and file names get unique hashes so visitors never see a stale cached version.

**Parcel** does all of that with zero configuration. Point it at `index.html`, and it finds your stylesheet, notices it's Sass, and handles the rest. You never write a config file.

## Getting started

1. Click **Use this template** on GitHub to create your own repo, then clone it.
2. Change `name` in `package.json` to your project's name.
3. Install and start the dev server:

```bash
npm ci
npm start
```

Open http://localhost:4321, and the page reloads as you edit.

| Command           | What it does                       |
| ----------------- | ---------------------------------- |
| `npm start`       | Dev server with live reload        |
| `npm run build`   | Production build in `dist/`        |
| `npm run push-gh` | Builds and deploys to GitHub Pages |
| `npm run format`  | Tidies up your code with Prettier  |
| `npm run cleanup` | Deletes build output and caches    |

The card on the starter page is just demo content. Swap it out and make something of your own. Happy coding! ✨

## Credits

Tool and Frontend Mentor logos come from [Simple Icons](https://simpleicons.org) (CC0); the Parcel mark is cropped from [Parcel's official logo](https://github.com/parcel-bundler/website). All logos are trademarks of their respective owners.

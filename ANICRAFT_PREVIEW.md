# AniCraft guided lessons — preview

This branch combines eleven unpublished AniCraft tutorials into one navigable preview. It does not modify submitted pull requests or the official Craft Wiki.

## Reading order

1. [Getting Started](/apps/anicraft/getting-started/)
2. [AniCraft: A Beginner's Guide](/apps/anicraft/anicraft-a-beginner-s-guide/)
3. [Drawing](/apps/anicraft/drawing/)
4. [What is Vector Art?](/apps/anicraft/what-is-vector-art/)
5. [Stroke vs. Fill](/apps/anicraft/stroke-vs-fill/)
6. [Combining and Cutting Shapes](/apps/anicraft/combining-and-cutting-shapes/)
7. [Symbols](/apps/anicraft/symbols/)
8. [Animating](/apps/anicraft/animating/)
9. [The Timeline](/apps/anicraft/the-timeline/)
10. [Keyframe Animation](/apps/anicraft/keyframe-animation/)
11. [Frame-by-frame Animation](/apps/anicraft/frame-by-frame-animation/)

## Local build

```sh
npm ci
npm run build
npm run preview
```

For deployment, connect this branch to a static-site host, build with `npm run build`, publish `dist`. Use the generated preview URL rather than craft.wiki.

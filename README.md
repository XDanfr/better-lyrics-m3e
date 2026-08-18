# Better Lyrics M3E

A Material 3 Expressive-inspired theme for [Better Lyrics](https://github.com/better-lyrics/better-lyrics).

The theme is built as a standalone CSS layer on top of Better Lyrics' documented styling API. It takes inspiration from [M3E](https://github.com/matraic/m3e) for colour, shape, motion, density, and expressive component language without embedding M3E Web Components into Better Lyrics.

## Status

Early development. The first stage is to establish a clean M3 Expressive token foundation, then progressively refine lyric presentation and surrounding UI.

## Architecture

```text
M3 Expressive design concepts
            ↓
       local M3 tokens
            ↓
   Better Lyrics variables
            ↓
      Better Lyrics DOM
```

This keeps the theme independent of Better Lyrics and M3E implementation details while making the design system easy to evolve.

## Planned areas

- [ ] M3 Expressive colour foundation
- [ ] Typography hierarchy
- [ ] Shape and surface system
- [ ] Active/inactive lyric treatment
- [ ] Expressive lyric motion
- [ ] Translation and romanisation styling
- [ ] Loader and no-lyrics states
- [ ] Footer, floating dock, submitter and voting UI
- [ ] Responsive refinements
- [ ] Optional dynamic album-art colour exploration

## Using the theme

The distributable theme entry point is [`theme.css`](./theme.css). Source files are organised under [`src/`](./src/) so the design system can be developed in smaller pieces.

The Better Lyrics styling documentation remains the source of truth for supported selectors and custom properties. This project does not copy Better Lyrics source files.

## References

- [Better Lyrics](https://github.com/better-lyrics/better-lyrics)
- [Better Lyrics styling guide](https://github.com/better-lyrics/better-lyrics/blob/master/STYLING-SKILL.md)
- [Better Lyrics CSS documentation](https://github.com/better-lyrics/better-lyrics/blob/master/STYLING.md)
- [M3E](https://github.com/matraic/m3e)
- [M3E Web Components](https://github.com/matraic/m3e/tree/main/packages/web)

## License

MIT

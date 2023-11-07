# test-astro-with-prettier-3

Basically today I was confused on why Prettier wouldn't format Astro files. Turns out it's because:

- Latest `prettier-plugin-astro` requires Prettier 3.
- Prettier 3 requires explicit `plugins` and `overrides` in order to programatically format files.
- Visual Studio Code requires the Astro to be used as default formatter when formatting Astro files.

# Root redirect for canadiandataproject.github.io

The explorer lives at https://canadiandataproject.github.io/canada-through-time/. The bare address
https://canadiandataproject.github.io/ is served by a separate repository that must be named exactly
`canadiandataproject.github.io` in the `canadiandataproject` organization. Put these two files at the root of that
repository's default branch (GitHub Pages: deploy from branch, `/` root). `index.html` forwards the bare address;
`404.html` forwards any other path on the bare domain, keeping `?query` and `#hash`.

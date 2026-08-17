# nabzo.store

The Nabzo marketing site. Static — one `index.html` plus images.

The app source is NOT here: it lives in the private `cofeea/nabzo` repo. This
repository is public only because GitHub Pages requires it, and it contains
nothing that is not already served publicly at https://nabzo.store.

The Supabase key in the page is the *publishable* key: it is meant to be public,
and every table it can reach is insert-only behind an RLS policy.

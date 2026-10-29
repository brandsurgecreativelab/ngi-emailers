# ngi-emailers

Public image hosting for Nedgroup Investments HTML emailers, served by GitHub Pages at
`https://brandsurgecreativelab.github.io/ngi-emailers/`.

Images only. No HTML, recipient lists or other confidential material belong in this repository.

## Structure

- `shared/brand/`: brand artwork reused across emailers (tagline)
- `shared/icons/`: event detail icons (date, time, venue)
- `shared/social/`: social media icons (Facebook, YouTube, LinkedIn, X)
- `campaigns/<year>-<campaign>/`: artwork unique to one emailer (headers)

## Rules

- Never rename, overwrite or delete an image once an email using it has been sent. Sent emails load it from here forever.
- To change an image, upload it under a new name (for example `header-v2.png`) and point the new email at it.
- All images are PNG at 2× their display size.

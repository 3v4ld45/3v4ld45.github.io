# 3v4ld45.github.io

Laikinas Wishlist programėlės nuorodų puslapis (kol nėra tikro domeno).

- `/invite/<žetonas>` ir `/l/<sąrašo id>` → `404.html` parodo mygtuką „Atidaryti Wishlist“ (Android intent / `wishlist://`).
- `/.well-known/assetlinks.json` – Android App Links patvirtinimas (paketas `lt.ekinzinerija.wishlist`, beta pasirašymo raktas).
- `.nojekyll` – kad GitHub Pages publikuotų `.well-known` aplanką.

Kai bus domenas: perkelti šiuos failus ten ir pakeisti `Brand.publicBaseUrl` bei AndroidManifest App Links host.

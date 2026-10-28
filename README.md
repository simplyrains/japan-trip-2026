# Protected itinerary

This repository contains a password-encrypted HTML itinerary generated with StatiCrypt 3.5.4.
The original HTML and the decryption password are intentionally excluded.

## GitHub Pages setup

1. Place these files at the repository root on the main branch.
2. Open Settings → Pages.
3. Set Source to Deploy from a branch, select main and / (root), then Save.
4. Open the published HTTPS address and enter the password supplied separately.

GitHub Free requires a public repository for Pages. Only these encrypted files should be public.
Do not upload the original itinerary, credentials, or private notes to this repository.

## Using the page

- A strong password is required because the encrypted file itself is publicly downloadable.
- The password screen decrypts the itinerary in the visitor's browser; there is no login server.
- The optional remember checkbox retains an unlocking key on that browser for 14 days.
- To forget an unlocking key, append #staticrypt_logout to the page address and reload.
- The itinerary's checklist, notes, and alternate-plan choices use browser local storage.
  They do not automatically sync across devices or browsers.
- Revoking a password cannot recall a copy of the encrypted file somebody already downloaded.

## License

The bundled StatiCrypt code is MIT licensed; see LICENSE-staticrypt.txt.

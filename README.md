# killer0xx.github.io

Public pages for **Rokra** (روکڑا), the Pakistan app that shows which nearby ATMs have cash right now (live reports from people at the ATM) on a map.

- Privacy policy: https://killer0xx.github.io/Rokra/privacy-policy.html (linked from the app and the Play listing)

Generated from `store/privacy-policy.md` in the (private) Rokra repo by `tools/build_site.py`. Don't edit the HTML here by hand.

## Notification pictures (TASK 77)

- `kaju/kaju_n_*.png` — Kaju's notification faces (the app's final art), used as the picture in Rokra notifications.
- `pins_index.json` — ATM id → bank, short name, city, 0.2° square, for the server's cash alerts. Built from the app's
  data files by `tools/build_pin_index.py` in the Rokra repo; rebuild when the data changes.
- `n/` — pictures the owner uploads from the Rokra admin panel for a notification.

No code and no secrets here: this repo is public.

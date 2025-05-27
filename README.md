# Offline Address Tagger (Mobile-Optimized)

This is a **mobile-friendly** version of the Offline Address Tagger — a lightweight tool for generating OpenStreetMap-style `addr:*` tags quickly and easily while mapping in the field.

Tested and confirmed working on **iOS Safari**, **Chrome**, and most modern mobile browsers.

---

## How It Works

1. Enter your **Starting Number** (e.g., 100).
2. Set your **Increment** (e.g., 2 for even/odd numbering).
3. Fill in the **Street**, **City**, **State**, **ZIP**, and **County**.
4. Tap **Start** to generate your first address.
5. Tap **Next** to increase the house number and generate the next tag set.
6. Tap **Copy** to copy the output to your clipboard for pasting into iD, Rapid, or your notes app.

---

## Output Example

addr:housenumber=100

addr:street=Example Street

addr:city=Sampletown

addr:state=TX

addr:postcode=12345

addr:county=Sample County


---

## When Switching Streets

If you're moving to a **new street** (or ZIP, city, etc.):

- You **must update** the following fields:
  - Street
  - Starting Number (and optionally Increment)
- Then press **Start** again to reset the counter for the new sequence.

---

## Features

- Fully self-contained — runs offline once loaded.
- Tap-friendly buttons and inputs.
- No server, no tracking, no internet required.
- Perfect for **field mapping**, **paper tag sheets**, or on-the-go OSM editing.

---

## Hosting

You can:
- Host it via **GitHub Pages** for mobile access.
- Download and run the `index.html` file directly in any mobile browser.

---

Built for mappers, by a mapper — and battle-tested on iOS.

Happy tagging!

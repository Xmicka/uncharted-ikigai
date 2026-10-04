# Uncharted Ikigai 🌸

A mobile-first keepsake web app for **Uncharted**, a session by Akesh ([@_akesh_02](https://instagram.com/_akesh_02)) at **NLDS'26**, AIESEC in Sri Lanka.

Delegates scan a QR code, answer four short ikigai questions, and get an Instagram-story-sized card to save or share.

**Live:** https://xmicka.github.io/uncharted-ikigai/

## Flow
1. **Welcome:** Uncharted · NLDS'26
2. **Identify:** first name + entity
3. **Loading:** a sakura bloom
4. **Ikigai:** four one-line answers
5. **Keepsake card:** drawn on a canvas, with **Save** (download) and **Share** (native share sheet where supported, save + copy caption everywhere else)

## Notes
- One static `index.html`. No build step, no backend, no login. Nothing leaves the device.
- Day (blush/cream) and night (yozakura indigo/gold) themes follow the phone's setting, and the sun/moon button switches between them.
- The native share sheet needs HTTPS (GitHub Pages provides it). No website can post straight to an Instagram story, so the share sheet is the closest real option.
- Test on real phones on the venue wifi before the session.

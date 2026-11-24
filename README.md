# Cam Remote

**Control your iPhone camera from your Garmin.** Take photos and videos from your wrist: great for group photos, selfies from a distance, or a phone on a tripod.

No iPhone app needed. The camera runs in a web page in Safari that you add to your Home Screen:

**👉 https://sappyfvr.github.io/camremote/**

*[Nederlands staat hieronder.](#nederlands)*

---

## How it works

```
Garmin ──Bluetooth──▶ Garmin Connect app ──internet──▶ relay ──▶ Safari page on your iPhone
(Cam Remote)          (on your iPhone)                          (camera, photos, videos)
```

Your watch sends short commands ("take a photo", "start video"). The Cam Remote page on your iPhone receives them and runs the camera. Your photos and videos never leave your phone.

## Getting started

1. Install **Cam Remote** on your Garmin.
2. Open it on the watch. The first time it shows a **10-digit pairing code**, e.g. `482-093-7556`.
3. On your iPhone, open **https://sappyfvr.github.io/camremote/** in **Safari** and enter the code.
4. Tap **Share → Add to Home Screen**. The icon remembers your code.
5. Open Cam Remote from the icon and tap **Start camera**. The watch shows **"Paired!"**.

Lost your code? On the watch: menu → **Pairing code**. On the page: tap the status bar at the top.

## Using it

| Action | Buttons | Touchscreen |
|---|---|---|
| Take a photo / start or stop a video / cancel the self-timer | **START** | tap the shutter button in the middle |
| Switch lens (back ↔ selfie) | via the menu | tap the button **left** of the shutter |
| Set the self-timer (off → 3 → 5 → 10 → 20 → 30 s) | via the menu | tap the button **right** of the shutter |
| Switch between **PHOTO** and **VIDEO** | **UP** / **DOWN** | swipe up / down |
| Menu: mode, lens, light, self-timer, pairing code | hold **UP** | tap the **Options** button at the bottom |

**Default settings:** tap the gear icon on the Cam Remote page to choose the self-timer, camera (back or selfie) and light the camera starts with. They apply every time you open Cam Remote on your watch. If you installed the app from the Connect IQ Store, the same defaults are also in the app's settings in Garmin Connect; a value chosen there takes priority.

**Saving to Photos:** everything you take stays in Cam Remote first. Tap the photo button (top right) → **Save to Photos** → choose **Save** in the share menu.

## Free trial

You get **3 free shots** (photos or video starts). After that, the watch shows a 6-digit code: go to **www.kzl.io/code**, enter the code and pay once. The app unlocks within a minute and stays unlocked on that watch. Payments are handled by KiezelPay.

## Requirements

- A Garmin with a **touchscreen** and Connect IQ 3.2 or newer (Forerunner, fēnix, epix, Venu, vívoactive, Approach, D2, Descent, MARQ, Edge and more)
- An iPhone with **Safari**; iOS 16.4 or newer keeps the screen on automatically
- The **Garmin Connect** app on the iPhone, and an internet connection
- Keep the Cam Remote page open while you use it

## Good to know

- A command takes about **1–2 seconds**. Use the self-timer for group photos.
- Photos are taken from the live camera image (up to 4K). Safari can't fire the real flash; the light only works where Safari allows it.
- Languages: English, Nederlands, Deutsch, Français, Español, Italiano. The page follows your iPhone's language.

## Privacy

- **Photos and videos stay on your iPhone.** They are never uploaded.
- Commands travel through the free public relay **ntfy.sh**, using your pairing code as a private channel name. Keep your code to yourself: anyone who knows it can operate your camera page.
- For the purchase, the watch sends its device ID and model number to **KiezelPay**.
- The page keeps your settings and unsaved photos only in your own browser.

---

## Nederlands

**Bedien je iPhone-camera met je Garmin.** Maak foto's en video's vanaf je pols, zonder app op je iPhone: de camera draait in een webpagina in Safari.

**👉 https://sappyfvr.github.io/camremote/**

### Zo begin je

1. Installeer **Cam Remote** op je Garmin en open de app. Je ziet een **koppelcode van 10 cijfers**.
2. Open **https://sappyfvr.github.io/camremote/** in **Safari** op je iPhone en typ de code.
3. Tik op **Deel → Zet op beginscherm**, open Cam Remote via het icoon en tik op **Start camera**.
4. Druk op **START** op je horloge (of tik op het scherm) om een foto te maken.

### Proefperiode

Je krijgt **3 gratis opnames**. Daarna toont het horloge een code van 6 cijfers: ga naar **www.kzl.io/code**, voer de code in en betaal eenmalig. De app is binnen een minuut ontgrendeld en blijft dat op dat horloge.

### Privacy

Je foto's en video's blijven op je iPhone. Alleen korte opdrachten gaan via **ntfy.sh**, met je koppelcode als privékanaal; houd die code dus voor jezelf. Voor de aankoop stuurt het horloge zijn toestel-ID en typenummer naar **KiezelPay**.

# Acoustic Messenger

A browser-based prototype for acoustic device discovery, pairing, and short text messaging.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Open the **Actions** tab and check the **Deploy Acoustic Messenger to GitHub Pages** workflow.
4. Once it succeeds, visit:

   https://tarunk04.github.io/acoustic-messenger/

## Use

Open the page on both phones in Chrome and grant microphone permission. Start broadcasting on the phone you want to advertise. The other phone can listen and select the discovered device to pair.

## Experimental status

This is a prototype, not a production messenger. Acoustic packet timing, decoding, and pairing still need real-device validation. A frequency peak shows microphone energy; it does not prove a packet was decoded. Smartphone audio processing, speaker/microphone response, room acoustics, and simultaneous transmissions can affect results.

The QR helper loads its library from a CDN, so QR generation requires an internet connection. Acoustic message transmission itself is intended to work phone-to-phone without an internet transport.

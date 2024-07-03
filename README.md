# SkyLink-Cloudflare - Bluesky DID Detector

A simple web extension that detects if the current website is connected to a Bluesky user.

Remember the good 'ol days of visiting someone's blog and being delighted when the "RSS" lit up in your browser? This is meant to capture that same magic. No more hunting on a page for a random bird icon to see if you can find their online profile.

![chrome_skyline_preview](https://user-images.githubusercontent.com/8367129/235382697-aedfda18-aab3-477b-b59c-c12cdd33bf9b.png)

SkyLink works by detecting Decentralized Identifiers (DIDs) in a domain's TXT records as well as checking via the [alternative HTTPS method](https://psky.app/profile/emily.bsky.team/post/3juuaipn3q424) linking to the associated Bluesky profile.

When a profile is detected, the icon lights up blue and clicking it will take you to their profile.

---

As of May 17, 2023, Bluesky is still invite-only and the web app is at https://bsky.app.

You can find me there at [@adhdjesse.com](https://bsky.app/profile/adhdjesse.com)

**Contributors:**

- [@danielhuckmann.com](https://bsky.app/profile/danielhuckmann.com) - Firefox Support, Privacy & Security Enhancements
- [@aliceisjustplaying](https://bsky.app/profile/alice.bsky.sh) - HTTPS Method of DID Detection

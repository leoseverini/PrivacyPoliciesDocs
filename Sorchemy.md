# Sortchemy — privacy policy

In English and Spanish, the policy Google Play asks for: published at a public address, linked from the store listing and from inside the game. It says what the game as built does. **Before publishing:** fill in the three things in square brackets, and read it against the game once more if ads, purchases or anything online has changed since 2026-10-07. It is not legal advice.

Brought up to version 0.5.0 on 2026-10-07. What it was read against:

- **The game's own code**: it makes no network request of its own (no `HTTPRequest` anywhere outside the ads plugin); the only thing it opens is this policy's address, in the phone's browser. The save has five parts — levels (results, the attempt under way, random mode's choices, the daily challenge's dates), currency (coins and hints), alchemy (recipes found), lab (what was bought and what is worn) and achievements (what was earned and the counts behind them) — and the settings are a second file. Neither is sent anywhere.
- **The ads SDK the build carries**: Google's GMA Next-Gen SDK, `ads-mobile-sdk` 1.4.0, with the User Messaging Platform 4.0.0 for consent (`addons/admob/`, plugin 5.1.0). What it collects is taken from [Google's page for that SDK](https://developers.google.com/admob/android/next-gen/privacy/play-data-disclosure), read 2026-10-07; the page describes "the latest version", so read it again after a plugin update.
- **The daily challenge and the laboratory**, new since the first draft: a day's puzzle is made on the phone from the date, and the laboratory takes coins earned in the game. Neither sends or sells anything, and both are said below so that nobody has to wonder.

The game's side of the link is built: put the address in `data/store.tres` (`privacy_policy_url`) and the settings show "Privacy policy".

---

## Privacy Policy

**Sortchemy** — Leonardo Severini
Last updated: 07/10/2026

Sortchemy is a puzzle game for Android. This policy explains what information is handled when you play it.

### What the game itself keeps

The game stores your progress and your settings in files on your own device. Your progress is the levels you have finished and your stars, your coins and hints, the recipes you have discovered, your achievements and the counts they are earned by, the days on which you played the daily challenge, and what you have bought for your laboratory with coins. Your settings are sound, music, vibration, motion, patterns and language.

This information never leaves your device: the game has no accounts, no online leaderboards and no server of its own, and its developer receives none of it. The daily challenge is made on your device from the date; nothing is downloaded for it. Uninstalling the game, or clearing its data in Android's settings, deletes all of it.

The game asks for no personal information such as your name, email address, contacts, photos or precise location.

### Purchases

Nothing in the game is sold for money. Coins are earned by playing, and the laboratory's bottle styles and backdrops are paid for with those coins.

### Advertising

Sortchemy shows ads provided by Google AdMob. To do that, the game includes Google's Mobile Ads SDK, which automatically collects and shares with Google:

- your device's IP address, which may be used to estimate its general location;
- device identifiers, such as the Android advertising ID and the app set ID, and, where applicable, other identifiers related to accounts signed in on the device;
- how you interact with the game and its ads, such as app launches, taps and video views;
- diagnostic information, such as launch time, hang rate and energy usage.

Google uses this information for advertising, analytics and fraud prevention. It is encrypted in transit. How Google uses information from apps that use its services is described at https://policies.google.com/technologies/partner-sites, and Google's own privacy policy is at https://policies.google.com/privacy.

### Your choices

- **Consent.** If you are in the European Economic Area, the United Kingdom or Switzerland, the game asks for your consent before showing ads, using Google's consent form. You can change your answer at any time under Settings → Privacy options.
- **Advertising ID.** You can reset or delete your advertising ID, or opt out of ad personalization, in your device's settings (Settings → Google → Ads, or Settings → Privacy → Ads).
- **Rewarded ads** are always your choice: the game never requires you to watch one.

### Children

Sortchemy is not directed to children under 13, and its developer does not knowingly collect personal information from children.

### Changes to this policy

If this policy changes, the new version will be published at this address with a new date.

### Contact

Questions about this policy: leoseverini@gmail.com

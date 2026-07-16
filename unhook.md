# Privacy Policy — Unhook

**Effective: 15 July 2026**

Unhook is made by Leonardo Severini (lushgames). This policy explains what the
app does with your information. The short version: **it stays on your phone.**

## What Unhook collects

**Nothing.** Unhook has no servers, no account, no login, no analytics, and no
advertising. There is nowhere for your data to be sent, because there is nothing
on the other end.

## What stays on your device

To do its job, Unhook reads and stores the following **only in the app's private
storage on your phone**:

- **How long you spend in each app**, read from Android's own usage statistics.
- **The limits and pause screens you set**, per app.
- **A record of each completed day** — how long you used your phone and whether
  your limits held — so the calendar and streaks work.
- **Your appearance setting** (light, dark, or system).

None of this is transmitted anywhere. Uninstalling Unhook deletes all of it.

## Permissions, and why each one exists

- **Usage access** (`PACKAGE_USAGE_STATS`) — the only way Android lets an app
  measure how long you spend in other apps. This is what Unhook is for. You
  grant it manually in Settings and can revoke it at any time.
- **Display over other apps** (`SYSTEM_ALERT_WINDOW`) — draws the pause screen
  over an app you have chosen to intercept, at the moment you open it. Unhook
  never draws over an app you have not configured.
- **Notifications** — to tell you when you are near or past a limit, and to show
  the ongoing notice while the background service runs.
- **Run at startup** — so your limits still work after you restart your phone.
- **Foreground service** — Unhook must keep checking while your screen is on,
  otherwise a limit could pass, or an app open, without it noticing.
- **Internet and network state** — used **only** by Google Play's billing
  library to sell the Pro upgrade. Unhook itself makes no network requests and
  sends nothing anywhere. If you never open the upgrade screen, nothing uses it.

## Purchases

Unhook Pro is a one-time purchase handled entirely by **Google Play**. Unhook
never sees or stores your name, email, or payment details — Google processes the
payment and simply tells the app whether the purchase exists. Google's handling
of that transaction is covered by
[Google's Privacy Policy](https://policies.google.com/privacy).

## What Google collects on its own

Independently of this app, Google Play may collect information about
installations and crashes for any Android app, including this one. That is
Google's collection, not ours, and it happens whether or not a developer asks
for it. See Google's Privacy Policy above.

## Children

Unhook is not directed at children and does not knowingly collect information
from anyone. Since it collects nothing at all, there is nothing to collect from
a child either.

## Your data, your control

Because everything is local, you are already in control:

- Revoke usage access or overlay permission in Android Settings at any time.
- Clear the app's storage in Settings → Apps → Unhook → Storage.
- Uninstall the app to remove everything it has stored.

There is no account to delete and no request to send us, because we hold nothing
about you.

## Changes

If Unhook ever collects anything — it does not today — this policy will be
updated before that version ships, and the effective date above will change.

## Contact

Questions: **leoseverini@gmail.com**

---

## Notes for the developer — delete before publishing

- **This is a draft, not legal advice.** It is written to be accurate about what
  the code actually does today; I verified each permission claim against the
  manifest. The legal framing is your responsibility.
- **It must stay true.** The moment you add analytics, a crash reporter, a
  backend, or ads, this becomes false — and a false privacy policy is a Play
  policy violation, not just bad manners.
- **Play requires this at a public URL** before you can publish. GitHub Pages
  works: put it in a repo, enable Pages, use the resulting link.
- **If you have EU users**, GDPR applies. Collecting nothing makes this
  straightforward, but consider whether you want an explicit "no personal data is
  processed" statement and a named data controller. Worth a lawyer's eye if you
  ever monetise beyond a one-off unlock.
- Update the effective date to the day you publish.

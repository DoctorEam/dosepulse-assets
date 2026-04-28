# Notification Reliability — DosePulse Setup Guide

If your DosePulse reminders aren't firing reliably, your phone is probably putting the app to sleep in the background. This is normal Android behavior across every major brand — your phone is trying to save battery, but the side effect is that scheduled reminders get killed.

The fix is the same idea on every device: tell your phone to never sleep DosePulse. Find your brand below for the exact steps.

---

## Samsung Galaxy (One UI)

1. Open **Settings**
2. Go to **Battery and device care → Battery**
3. Tap **Background usage limits**
4. Open **Never auto-sleeping apps**
5. Tap **Add apps** and select **DosePulse**

While you're there, also confirm DosePulse is **not** in **Sleeping apps** or **Deep sleeping apps**.

---

## Xiaomi / Redmi / POCO (MIUI / HyperOS)

1. Open **Settings → Apps → Manage apps**
2. Find and tap **DosePulse**
3. Open **Battery saver**, set to **No restrictions**
4. Go back, open **Autostart**, toggle it **on**
5. Optional but helpful: long-press DosePulse in your recent apps list and tap the **lock icon** to keep it pinned

---

## Huawei / Honor (EMUI / HarmonyOS)

1. Open **Settings → Apps → DosePulse**
2. Tap **Battery**
3. Tap **App launch**
4. Switch off "Manage automatically"
5. Enable all three toggles: **Auto-launch**, **Secondary launch**, **Run in background**

---

## Oppo / Realme / OnePlus (ColorOS / OxygenOS)

1. Open **Settings → Battery**
2. Find **DosePulse**
3. Enable **Allow background activity**
4. Go back to **Settings → Apps → DosePulse → Auto-launch** and turn it **on**

---

## Vivo (FuntouchOS / OriginOS)

1. Open **Settings → Battery**
2. Tap **Background power consumption management**
3. Find **DosePulse**
4. Set to **Allow**

---

## Google Pixel (stock Android)

Usually no extra setup needed. If reminders are still missing:

1. Open **Settings → Apps → DosePulse**
2. Tap **Battery**
3. Set to **Unrestricted**

You can also exclude DosePulse from Adaptive Battery (Settings → Battery → Adaptive Battery → exempt DosePulse) if you don't open the app every day.

---

## Other brands (Motorola, Nokia, ASUS, etc.)

These run close to stock Android — same path as Pixel: **Settings → Apps → DosePulse → Battery → Unrestricted** should be enough.

---

## Still not working?

A few other things to check on any device:

- **Notification permission** is granted (Settings → Apps → DosePulse → Notifications → On)
- **Exact alarms permission** is granted (Settings → Apps → DosePulse → Special access → Alarms & reminders → Allowed) — required on Android 12+
- **Do Not Disturb** isn't on at the slot time
- **Battery saver / power saving mode** is off, or has DosePulse exempted
- The supplement or activity is **active (not paused)** and **today's weekday is in its schedule**

---

## Got feedback?

If your phone brand isn't listed, the steps don't match your version, or you've found another setting that fixed it for you — let us know and we'll update this guide.

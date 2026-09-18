# TikTok - IcySymmetra & NexAlloy (Auto-Build)

Two patched builds of TikTok, made with different tooling. Both are published in every release.

| APK | Source | Tooling | Built against |
| --- | --- | --- | --- |
| `tiktok-icysymmetra-…` | [tiktok-patches-for-morphe](https://github.com/icysymmetra/tiktok-patches-for-morphe) | Morphe | 46.2.3 |
| `tiktok-nexalloy-…` | [SexAlloy](https://github.com/gnadgnaoh/SexAlloy) | LSPatch | whatever version is current |

Each is a universal APK covering `arm64-v8a` and `armeabi-v7a`, so there is nothing to choose between.

The IcySymmetra build is patched the usual way: the patches are compiled into the APK and target one specific TikTok version. The NexAlloy build instead embeds an Xposed module into the APK with [LSPatch](https://github.com/JingMatrix/LSPatch), so it hooks at runtime and is not tied to a TikTok version — but it carries fewer changes.

## Installation

1. Install the latest version of [Build APK](https://github.com/MentalBlank/Tiktok-Revanced/releases/latest).
2. Use [Obtainium](https://github.com/ImranR98/Obtainium) to download and install build updates.

Neither build needs root or a separate LSPosed install; the NexAlloy build has the module loader injected into it.

## Patches

**IcySymmetra** — Hide CAPTCHA popups · Feed filter · Disable screen capture detection · Remember clear display · Downloads · Stop video looping · Custom offline videos limit · Always show publish date · Disable long-press quick share · Disable long-press repost · Hide quick comment reactions · Resume videos after scrolling · Enable non-personalized search · Enable Live search · Show seekbar · Show seekbar thumbnail · Hold-and-slide 2x lock · Playback speed · Copy comments without username · Open external links directly · Feature Gate Lab · Disable login requirement · Fix Google login · Feed tab navigation · Settings · Sanitize sharing links · SIM spoof · Translate comments · Hide floating promotions

Available but off by default: Diagnostic tools.

**NexAlloy** — Remove feed ads · Hide promoted music videos · Disable screen capture detection · Disable login requirement · Fix Google login · Hide CAPTCHA popups · Remove download watermark

## Disclaimer

This patch modifies the original APK, and may violate the app provider's terms of service. Use at your own risk.

## Other Apps:

[Google Photos](https://github.com/MentalBlank/GPhotos-Revanced) | [YouTube](https://github.com/MentalBlank/YouTube-Revanced) | [FB Messenger](https://github.com/MentalBlank/Messenger-Revanced) | [Reddit](https://github.com/MentalBlank/Reddit-Revanced) | [TikTok](https://github.com/MentalBlank/Tiktok-Revanced)

## Thanks To:

[j-hc](https://github.com/j-hc) & [Morphe](https://github.com/MorpheApp/) & [icysymmetra](https://github.com/icysymmetra/tiktok-patches-for-morphe) & [gnadgnaoh](https://github.com/gnadgnaoh/SexAlloy) & [LSPatch](https://github.com/JingMatrix/LSPatch)

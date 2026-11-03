<div align="center">

# Token Printer

**Print Magic: The Gathering tokens as stickers, straight from your phone.**

Browse every token and emblem, pick the art you like, and print it on a small, cheap Bluetooth thermal sticker printer.

[![Latest version](https://img.shields.io/github/v/release/eddie-w2/MTGTokenPrinter-releases?label=latest&color=2ea44f)](https://github.com/eddie-w2/MTGTokenPrinter-releases/releases/latest)
![Android 8.0+](https://img.shields.io/badge/Android-8.0%2B-3ddc84)
![Free](https://img.shields.io/badge/price-free-blue)

### [Download the latest version](https://github.com/eddie-w2/MTGTokenPrinter-releases/releases/latest)

</div>

---

## Why Token Printer?

Tokens are the part of Magic that is always missing when you need it. While dry erase tokens solve for it in the moment, a sticker printer in your bag solves it long term: pick a token, tap Print, and a few seconds later you have a permanent token you can slap on a bulk card and keep with that deck.

## What it does

- **Every token and emblem, always current.** The full list comes from Scryfall, and you can sync new set releases with one tap.
- **Pick your favorite art.** Browse every printing of a token, and heart the one you want to be your default.
- **Fast printing.** Press and hold any token, slide onto **Print** or **Export**, and let go. It uses your last settings.
- **A live preview of exactly what will print**, with controls for the caption, keyword abilities or full rules text, power/toughness, color identity, fonts, text size, line spacing and contrast.
- **Stacked labels.** Mark a single token as "10x", "25x", "50x" or "100x" when one sticker stands in for a whole pile of them.
- **Decks.** Paste a card list from Arena, Moxfield and similar, and Token Printer finds every token your deck creates, so you can print them all at once.
- **Your own tokens.** Draw one, or use a photo, and attach it to an existing token or keep it on its own.
- **Works with other printers too.** Export a token as a JPEG (color, grayscale or black and white) and print it from any printer's own app.
- **Dark mode, backup and restore, and a built-in FAQ.**
- **Updates itself.** See [Staying up to date](#staying-up-to-date).

## Supported printers

Token Printer recognises your printer by its Bluetooth name and sorts it under the app it came with. If you know which app your printer uses, you know whether it's covered.

| Printer's own app | Example models | Status |
| --- | --- | --- |
| **Funny Print** | YTETCN **LX-D02**, LX-D01 to LX-D09, XenGro AH-M2, Dolewa | LX-D02 tested · others experimental |
| **Tiny Print / iPrint** | GB01 to GB05, GT01, X5, X6, X7, and many white-label "cat printers" | Experimental |
| **Fun Print / iBleem** | MX05, MX06, MX08, MX10, YT01, BQ series, MXW01, KERUI | Experimental |
| **Phomemo** | M02, M02X, M02S, M02 Pro, T02, Memoking T02 / Q02E | Experimental |
| **Nada Print** | D20 | D20 tested |
| **Any ESC/POS app** | 58 mm and 80 mm Bluetooth receipt printers | Experimental |
| Anything else | | Use **Export** to make an image and print it from the printer's own app |

*Experimental* means Token Printer speaks that printer's language, but nobody has confirmed it yet on real hardware. If yours works (or doesn't), please use **Settings > Help > Report a bug** to tell me. That's how printers move to *tested*.

Printer not in the list? In the printer window, tap **Show other Bluetooth devices**, then **⋮ > Try as…** and pick the app your printer came with. Or [tell me which one you have](mailto:mtgtokenprinter@gmail.com) and I'll do my best to add it.

Printer support builds on the excellent open-source [TiMini-Print](https://github.com/Dejniel/TiMini-Print) project (Apache License 2.0).

## Install

Token Printer isn't on the Google Play Store, so you install it directly. It takes about a minute.

1. On your Android phone, open the [latest release](https://github.com/eddie-w2/MTGTokenPrinter-releases/releases/latest).
2. Under **Assets**, tap the file ending in **.apk** (for example `TokenPrinter-0.8.01-code12.apk`) to download it.
3. Open the downloaded file. Android will ask whether to allow your browser to install apps. Allow it for this one install.
4. Tap **Install**. If Google Play Protect warns you because the app isn't from the Play Store, choose **Install anyway**.
5. Open **Token Printer**, switch on your printer, tap **Connect**, then **Scan**, and pick your printer.

That's it. The first time you open the app it downloads the token list, so connect to the internet for that step.

**Requirements:** Android 8.0 or newer, and Bluetooth.

## Staying up to date

After the first install, you don't need to come back to this page. Token Printer checks for a new version the first time you open it each day and shows you what changed. Choose **Update now** and confirm Android's prompt. If you pick **Later**, the update waits for you in **Settings > App updates**, where you can also check by hand.

The first update asks you to allow Token Printer to install updates. This is a one-time Android permission.

Every version, and what changed in it, is listed on the [Releases page](https://github.com/eddie-w2/MTGTokenPrinter-releases/releases).

## Need help?

- The app has a built-in **FAQ** (Settings > Help > Open the FAQ).
- To reach me, use **Settings > Help > Contact me**, or email [mtgtokenprinter@gmail.com](mailto:mtgtokenprinter@gmail.com).
- Found a bug? Use **Settings > Help > Report a bug**. It fills in your app version, the date and your phone model for you, which makes problems much easier to track down.

## Open source

Token Printer is free, open-source software under the **GNU General Public License v3.0 or later**. The source code lives at
[github.com/eddie-w2/MTGTokenPrinter](https://github.com/eddie-w2/MTGTokenPrinter). Printer reports, bug reports and
fixes are welcome there.

## Legal

Token Printer is unofficial Fan Content permitted under the Fan Content Policy. Not approved or endorsed by Wizards of the Coast. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.

Magic: The Gathering, its card names, art, symbols and token designs are trademarks and copyrighted works of Wizards of the Coast LLC and their respective artists. This app is not affiliated with, sponsored or endorsed by Wizards of the Coast, Hasbro, Scryfall or any printer maker.

Card data and images are provided by [Scryfall](https://scryfall.com) and are fetched onto your phone. Nothing is copied to any server by the app, and no card data or art is included in the download. Art stays credited to its artists. Use printed tokens for personal play only, not for sale.

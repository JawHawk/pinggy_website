---
title: Access localhost from your phone!
description: Access localhost on your phone with Pinggy's QR code support. Start a tunnel, press 'u' or 'c' for QR, or use 'qr'/'aqr' as usernames for persistent QR. Add your token with '+'. Enjoy easy connectivity!
date: 2023-08-10T08:45:25.000Z
draft: false
og_image: images/qr/pinggyqr.webp
tags:
  - update
  - guide
outputs:
  - HTML
---

{{< video poster="/assets/tunnelvideothumb.jpg" src="/assets/qr.webm" >}}

{{% tldr %}}

- Start a Pinggy tunnel and press `**u**` or `**c**` to see QR code.
- Press `**Esc**` to hide QR code.
- Or use `**qr**` or `**aqr**` as username to always show QR in the terminal:


- You can pass your `token` along with `qr` by appending them with the `+` symbol:

{{% /tldr %}}

Pinggy can print QR codes for the tunnel URLs in ASCII or Unicode. The instructions for both are as follows.

## ASCII

Start a regular Pinggy tunnel:

```javascript
ssh -p 443 -R0:localhost:8000 a.pinggy.io

```
Press `**c**` to show the QR Code. It will display the QR Code representing the tunnel URL in ASCII form as shown in the screenshot below.

You have the option to utilize the **arrow keys** to cycle through various URLs and their corresponding QR Codes. To revert to the standard page, press the `**Esc**` key.

{{< figure src="../../../doc_img/qrcode/qr-ascii2.webp" alt="Press c to display QR-Code in ASCII" >}}

The QR Code presented here is crafted using ASCII characters, ensuring compatibility with the majority of terminals. Nonetheless, in instances where terminal windows are smaller, they might not fit optimally. For a QR Code with a more condensed appearance, opt for the Unicode version.

## Unicode

For a more compact QR Code, you can choose the Unicode QR option. Simply press `**u**` to generate a QR Code displayed using Unicode characters.

{{< figure src="../../../doc_img/qrcode/qr-unicode2.webp" alt="Press u to display QR-Code in Unicode" >}}

The Unicode QR-Code can easily fit within a 80x25 terminal. But, the terminal must have support for the Unicode character-set.

Pinggy also supports keywords `qr` and `aqr` while creating a tunnel to always show the QR codes in the terminal.

{{< figure src="../../../doc_img/qrcode/qr-inline-unicode2.webp" alt="Always display QR-Code in TUI" >}}

```javascript
ssh -p443 -R0:localhost:8000 qr@a.pinggy.io

```
If one wants to pass some other keyword like a token, simply add it with a `+` symbol:

```javascript
ssh -p443 -R0:localhost:8000 qr+token@a.pinggy.io

```
Here `qr` would produce QR code in Unicode while `aqr` would produce QR code in ASCII.

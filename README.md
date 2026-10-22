# Fluent Shade

**A customizable per-site dark and light theme extension for Firefox.**

Fluent Shade lets you customize the appearance of websites using dark and light themes. It is designed for users who want more control over how websites look while browsing.

## Features

- **Dark and light themes** — customize the appearance of supported websites.
- **Per-site customization** — configure themes for individual websites.
- **Firefox integration** — access the extension through the browser toolbar and options page.
- **Local settings** — designed to keep extension settings in your browser rather than requiring an online account.

## Installation

### Install from Mozilla Add-ons

Once Fluent Shade is approved and published, you will be able to install it through its official Mozilla Add-ons listing.

### Install manually for testing

1. Download or clone this repository.
2. Open Firefox and enter `about:debugging` in the address bar.
3. Select **This Firefox**.
4. Click **Load Temporary Add-on**.
5. Select the extension's `manifest.json` file.

Temporary installations are removed when Firefox restarts. For regular use, install a Mozilla-signed release when one is available.

## Permissions

Fluent Shade requests browser permissions to support its functionality:

- **Storage** — save extension settings.
- **Active tab and tabs** — interact with browser tabs as needed for extension features.
- **Website access** — allow the extension to apply themes to websites.

Website access is broad because the extension is intended to work across different websites. Review the source code if you want to understand exactly how these permissions are used.

## Privacy

Fluent Shade is designed to apply website styling and manage its settings within the browser. It does not require users to create an online account.

Review the source code and permission declarations for details about its behavior and data handling.

## Known limitations

Website structures differ, so the appearance of some pages may not be perfect. Certain content, including elements inside cross-origin frames or shadow DOM, may not be fully affected by the theme.

Compatibility can vary depending on the website and its design.

## Disclaimer

Fluent Shade is provided **"as is," without warranties of any kind**. Use it at your own discretion. Compatibility and appearance are not guaranteed on every website.

## License

This project is distributed under the **GNU General Public License v3.0 only (GPL-3.0-only)**. See the [LICENSE](LICENSE) file for the full license text.

Fluent Shade is an independent project and is not affiliated with or endorsed by Mozilla or the original Dark Reader team.

## Credits

Created and maintained by **Brandy**.


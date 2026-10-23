# Fluent Shade

**A customizable per-site dark and light theme extension for Firefox and Microsoft Edge.**

Fluent Shade lets you customize website appearance with dark and light themes, per-site rules, and browser-local settings.

## Features

- **Dark and light themes** — customize the appearance of supported websites.
- **Per-site customization** — configure themes for individual websites.
- **Local settings** — theme preferences are stored in browser-local storage; no Fluent Shade account is required.
- **Firefox and Edge builds** — browser packages use the appropriate background configuration for each browser.

## Installation

### Microsoft Edge (manual testing)

1. Download and extract the Microsoft Edge-specific ZIP package.
2. Open `edge://extensions`.
3. Turn on **Developer mode**.
4. Select **Load unpacked** and choose the extracted folder containing `manifest.json`.

### Firefox (manual testing)

1. Download and extract the Firefox ZIP package.
2. Open `about:debugging#/runtime/this-firefox`.
3. Select **Load Temporary Add-on** and choose the package's `manifest.json`.

Temporary development installations may be removed when the browser restarts. For public distribution, submit the relevant package through the browser's official add-on store after testing and review.

## Permissions

Fluent Shade uses storage to save settings and browser-tab access to apply updated settings to open websites. It requests broad website access because it is designed to theme sites across the web. Review the manifest and source code to understand the requested permissions.

## Privacy

The intended core styling behavior runs locally in the browser. Settings, per-site rules, schedule preferences, and custom CSS are stored in browser-local storage. The extension does not require a Fluent Shade account or server. Review the code and permissions before installing; modified versions may behave differently.

## Known limitations

- **YouTube is currently unsupported in both the Firefox and Microsoft Edge builds.** Fluent Shade may not apply its themes correctly to YouTube's interface.
- Website structures differ, so styling may not look perfect on every page.
- Content in cross-origin frames, shadow DOM, and browser-restricted pages may not be fully affected. Website changes can also affect compatibility.

## Creator's no-monetization position

The creator's intention is for Fluent Shade to remain freely available and not be monetized. The creator does not endorse or encourage selling this project or modified versions, charging for access or premium features, adding advertisements or subscriptions, or soliciting donations as a way to monetize the project.

**Important license clarification:** This statement expresses the creator's wishes; it does not amend or override the GNU GPL-3.0 license. The GPL permits recipients to charge for copies or services when they comply with its terms. The license text governs the legal permissions granted to recipients.

## Disclaimer

Fluent Shade is provided **"as is," without warranties of any kind**. Use it at your own discretion. Compatibility and appearance are not guaranteed on every website. The author does not promise ongoing maintenance or user support.

Fluent Shade is an independent project and is not affiliated with or endorsed by the original Dark Reader team, Mozilla/Firefox, or Microsoft/Edge. Product names and trademarks belong to their respective owners.

## License

This project is distributed under the **GNU General Public License v3.0 only (GPL-3.0-only)**, subject to the rights and license terms applicable to included components. See [LICENSE](LICENSE) for the full license text.

## Credits

Created and credited to **Brandy**.

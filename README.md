# Audio Router privacy and support

Public privacy policy and support pages for the Audio Router macOS app by PotatoPlanetStudios.

- Privacy policy: https://potatoplaneta.github.io/audio-router-privacy/
- Support: https://potatoplaneta.github.io/audio-router-privacy/support.html
- Private support and privacy requests: potatoplanet.studios@gmail.com
- Public bug reports: https://github.com/potatoplaneta/audio-router-privacy/issues

## Publishing

GitHub Pages serves the root of `main`. No build step, dependencies, JavaScript, external fonts, or analytics are required. `.nojekyll` enables static hosting. Push changes to `main` to publish.

`styles.css` is unchanged from [Wheel Launcher’s privacy and support site](https://github.com/potatoplaneta/wheel-launcher-privacy). `app-icon.png` is Audio Router’s 256-pixel app icon. Update the effective dates when privacy practices change.

For local preview, run `python3 -m http.server 8788 --bind 127.0.0.1`, then open http://127.0.0.1:8788/.

## App integration

Audio Router’s `AudioRouterPrivacyURL` and `AudioRouterSupportURL` Info.plist keys point to these pages. Use the same URLs in App Store Connect’s Privacy Policy URL and Support URL fields. Publishing this repository does not edit App Store Connect metadata.

The content was checked against Audio Router’s implementation on October 15, 2026. Recheck audio processing, permissions, local retention and deletion, StoreKit and Keychain records, and support practices when app behavior changes. Keep the private application source out of this public repository.

GitHub Issues are public and require a GitHub account. Direct private support and privacy requests to the email address above.

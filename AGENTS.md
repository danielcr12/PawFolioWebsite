# PawFolioWebsite Agent Instructions

- This repository publishes PawFolio's public legal and support pages with GitHub Pages. Keep page paths stable because the app and App Store Connect link to them.
- Maintain English, Latin American Spanish (`es-419`), and Thai pages for the home/support landing page, privacy policy, data deletion guide, and terms.
- Public contact email: `danicarrero92@gmail.com`. Keep every `mailto:` link on this address.
- When editing data deletion guidance, verify the current implementation in the PawFolio app repository at `../PawFolio/PawFolio/Settings/DataAndSync/DataManagementView.swift` and `../PawFolio/PawFolio/Shared/ICloudProfileStore.swift`. Describe device-only deletion, iCloud-zone deletion while keeping local data, and device-plus-iCloud deletion, plus the effects on other devices that keep syncing.
- Keep app-side link construction in `PawFolio/Settings/Core/SettingsLegalLinks.swift`, App Store Connect metadata in `PawFolio/metadata/`, and `PawFolio/Documentation/Website-And-Public-Links.md` aligned with these pages.
- Keep the pages static, accessible, and usable without JavaScript. Verify every localized route after publishing.

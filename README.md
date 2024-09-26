
[.theme.css]:  https://github.com/gold-me/DiscordIcons/raw/master/DiscordIcons.theme.css

[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[css-color]:       https://developer.mozilla.org/en-US/docs/Web/CSS/color
[css-url]: https://developer.mozilla.org/en-US/docs/Web/CSS/url_value

[shield-vc-dl]:     https://img.shields.io/github/downloads/gold-me/DiscordIcons/DiscordIcons.theme.css?color=orange&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/gold-me/DiscordIcons?label=Repository&style=flat-square%20%22Total%20size%22 "Total size"

[github]:  https://github.com/gold-me/DiscordIcons/raw/master/DiscordIcons
[Vencord]:  https://github.com/Vendicated/Vencord

[release-vc-gh]:    https://github.com/gold-me/DiscordIcons/releases/latest/download/DiscordIcons.theme.css "Get latest release"
# DiscordIcons
[![Vencord GitHub downloads][shield-vc-dl]][release-vc-gh]
[![Total repository size][shield-repo-size]][github]

A lightweight, highly customizable theme that adds more icons to your settings.

## Installation
<details open><summary>Click to expand</summary>

⚠️ This theme is designed for use with [Vencord][Vencord]; other client mods are not supported.

Enable the `ThemeAttributes` plugin in `Settings` > `Vencord` > `Plugins`.
### Local
1. Download `DiscordIcons.theme.css`:
    - [GitHub][release-vc-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://gold-me.github.io/DiscordIcons/main.css`
</details>

## Customisation

| Variable name     | Description               | Value                | Default value |
| ----------------- | ------------------------- | ------------------------- | ------------- |
| `--si-size`     | Icon size                 | \<[length][css-length]\> | `24px`        |
| `--si-height`   | Height of sidebar boxes   | \<[length][css-length]\> | `32px`        |
| `--si-animations`   | Toggles sidebar animations | \<true \| false\> | `true`        |
| `--si-expand`   | Toggles expand animations | \<true \| false\> | `false`        |
| `--si-color`   | Color of icons when hovered/selected | \<[color][css-color]\> | `currentColor`        |
| `--si-permacolor`   | Icons always show their set color | \<true \| false\> | `false`        |
| `--si-*`   |Icon Variable. Used for setting it's url | \<[url][css-url]\> | `*`        |
| `--si-color-*`   |Icon Variable. Used for setting it's color | \<[color][css-color]\> | `*`        |

## Extended Customization
Below are exhaustive lists of all existing variables for all icons and their respective colors.

<details><summary>Icons</summary>

~~~ css
--si-my-account: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Manage_Accounts.svg");
--si-profile-customization: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Style.svg");
--si-privacy-safety: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Security.svg");
--si-family-center: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Supervisor_Account.svg");
--si-authorized-apps: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/App_Registration.svg");
--si-sessions: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Devices.svg");
--si-connections: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Link.svg");
--si-settings-clips: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Theaters.svg");
--si-friend-requests: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Group_Add.svg");
--si-discord-nitro: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/Nitro.svg");
--si-nitro-server-boost: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/Server_Boost.svg");
--si-subscriptions: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Fact_Check.svg");
--si-library-inventory: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Redeem.svg");
--si-billing: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Receipt_Long.svg");
--si-appearance: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Brush.svg");
--si-accessibility: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Accessibility_New.svg");
--si-voice-video: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Perm_Camera_Mic.svg");
--si-powermode-settings: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/Party.svg");
--si-text-images: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Chat.svg");
--si-notifications: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Notifications_Active.svg");
--si-keybinds: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Keyboard.svg");
--si-language: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Translate.svg");
--si-windows: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Logo-Windows.svg");
--si-linux: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Logo-Tux.svg");
--si-streamer-mode: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Videocam.svg");
--si-advanced: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Tune.svg");
--si-vencordsettings: url("https://raw.githubusercontent.com/jdecked/twemoji/main/assets/svg/1f431.svg");
--si-vencordplugins: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Extention.svg");
--si-vencordthemes: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Format_Paint.svg");
--si-vencordupdater: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/System_Update_Alt.svg");
--si-vencordcloud: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Cloud.svg");
--si-vencordsettingssync: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Backup.svg");
--si-vesktop: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Vencord.svg");
--si-activity-privacy: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Privacy.svg");
--si-game-activity: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Gamepad.svg");
--si-overlay: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Overlay.svg");
--si-changelog: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Update.svg");
--si-merchandise: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Shirt.svg");
--si-hypesquad-online: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/HypeSquad.svg");
--si-experiments: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Experiment.svg");
--si-developer-options: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-hotspot-options: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-dismissible-content-options: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-payment-flow-modals: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-design-system: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-text-playground: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-text-component: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-intl-testing: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-profile-effects-preview-tool: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-web-setting-tree-tool: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Memory.svg");
--si-logout: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Logout.svg");
--si-overview: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Info.svg");
--si-roles: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Badge.svg");
--si-emoji: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Emoji.svg");
--si-stickers: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Stickers.svg");
--si-soundboard: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Soundboard.svg");
--si-widget: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Widgets.svg");
--si-guild_templates: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Library_Books.svg");
--si-vanity_url: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Share.svg");
--si-integrations: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Mediation.svg");
--si-app_directory: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Apps.svg");
--si-moderation: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Safety_Setup.svg");
--si-safety: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Safety_Setup.svg");
--si-guild_automod: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/AutoMod.svg");
--si-audit_log: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Audit_Log.svg");
--si-bans: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Gavel.svg");
--si-community: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Info.svg");
--si-onboarding: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Groups.svg");
--si-analytics: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Insights.svg");
--si-partner: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/Partner.svg");
--si-discovery: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Explore.svg");
--si-community_welcome: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Explore.svg");
--si-guild_premium: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Discord/Server_Boost.svg");
--si-role_subscriptions: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Fact_Check.svg");
--si-members: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Group.svg");
--si-instant_invites: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Send.svg");
--si-delete: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Delete.svg");
--si-permissions: url("https://raw.githubusercontent.com/gold-me/DiscordIcons/master/Icons/SVG/Permissions.svg");
~~~
</details>

<details><summary>Icon Colors</summary>

~~~ css
--si-color-my-account: var(--si-color);
--si-color-profile-customization: var(--si-color);
--si-color-privacy-safety: var(--si-color);
--si-color-family-center: var(--si-color);
--si-color-authorized-apps: var(--si-color);
--si-color-sessions: var(--si-color);
--si-color-connections: var(--si-color);
--si-color-settings-clips: var(--si-color);
--si-color-friend-requests: var(--si-color);
--si-color-discord-nitro: var(--brand-500);
--si-color-nitro-server-boost: var(--guild-boosting-pink);
--si-color-subscriptions: var(--si-color);
--si-color-library-inventory: var(--si-color);
--si-color-billing: var(--si-color);
--si-color-appearance: var(--si-color);
--si-color-accessibility: var(--si-color);
--si-color-voice-video: var(--si-color);
--si-color-powermode-settings: var(--si-color);
--si-color-text-images: var(--si-color);
--si-color-notifications: var(--si-color);
--si-color-keybinds: var(--si-color);
--si-color-language: var(--si-color);
--si-color-windows: var(--si-color);
--si-color-linux: var(--si-color);
--si-color-streamer-mode: var(--si-color);
--si-color-advanced: var(--si-color);
--si-color-vencordsettings: var(--si-color);
--si-color-vencordplugins: var(--si-color);
--si-color-vencordthemes: var(--si-color);
--si-color-vencordupdater: var(--si-color);
--si-color-vencordcloud: var(--si-color);
--si-color-vencordsettingssync: var(--si-color);
--si-color-vesktop: var(--si-color);
--si-color-activity-privacy: var(--si-color);
--si-color-game-activity: var(--si-color);
--si-color-overlay: var(--si-color);
--si-color-changelog: var(--si-color);
--si-color-merchandise: var(--si-color);
--si-color-hypesquad-online: var(--si-color);
--si-color-experiments: var(--si-color);
--si-color-developer-options: var(--si-color);
--si-color-hotspot-options: var(--si-color);
--si-color-dismissible-content-options: var(--si-color);
--si-color-payment-flow-modals: var(--si-color);
--si-color-design-system: var(--si-color);
--si-color-text-playground: var(--si-color);
--si-color-text-component: var(--si-color);
--si-color-intl-testing: var(--si-color);
--si-color-profile-effects-preview-tool: var(--si-color);
--si-color-web-setting-tree-tool: var(--si-color);
--si-color-logout: var(--si-color);
--si-color-overview: var(--si-color);
--si-color-roles: var(--si-color);
--si-color-emoji: var(--si-color);
--si-color-stickers: var(--si-color);
--si-color-soundboard: var(--si-color);
--si-color-widget: var(--si-color);
--si-color-guild_templates: var(--si-color);
--si-color-vanity_url: var(--si-color);
--si-color-integrations: var(--si-color);
--si-color-app_directory: var(--si-color);
--si-color-moderation: var(--si-color);
--si-color-safety: var(--si-color);
--si-color-guild_automod: var(--si-color);
--si-color-audit_log: var(--si-color);
--si-color-bans: var(--si-color);
--si-color-community: var(--si-color);
--si-color-onboarding: var(--si-color);
--si-color-analytics: var(--si-color);
--si-color-partner: var(--si-color);
--si-color-discovery: var(--si-color);
--si-color-community_welcome: var(--si-color);
--si-color-guild_premium: var(--guild-boosting-pink);
--si-color-role_subscriptions: var(--si-color);
--si-color-members: var(--si-color);
--si-color-instant_invites: var(--si-color);
--si-color-delete: var(--si-color);
--si-color-permissions: var(--si-color);
~~~
</details>


## Credits
[GoogleFonts]:               https://github.com/google/fonts
[GoogleFonts-author]:        https://github.com/google

[ionicons]:         https://github.com/ionic-team/ionicons
[ionicons-author]:  https://github.com/ionic-team

[twemoji]: https://github.com/twitter/twemoji
[twemoji-author]: https://github.com/twitter

- [Google Fonts][GoogleFonts] by [Google][GoogleFonts-author] - Apache License, Version 2.0
- [Ionicons][ionicons] by [Ionic][ionicons-author] - MIT license
- [Twemoji][twemoji] by [Twitter][twemoji-author] - MIT license

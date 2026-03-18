# Rose Pine Discord Theme

A theme for Discord with the Rose Pine color palette.

## Installation

Download the CSS theme file of your choice and put it in your client theme folder.

## 🙋 FAQ

- Q: **_"Can this get my account banned?"_**
- A: Using third party clients and injecting custom css is against the ToS. While nobody has ever been banned for simply using discord client mods, We are not responsible for anything that might happen to your account by using third party clients. Use at your own discretion!

- Q: **_"Can I automatically switch flavors between light and dark mode?"_**
- A: The following snippet showcases a configuration that switches between dawn in light mode and rose-pine in dark mode by adding an inline [`prefers-color-scheme` media feature](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme), `(prefers-color-scheme: <light-or-dark>)`, after each `@import` statement (see ["Importing CSS rules conditional on media queries" - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@import#importing_css_rules_conditional_on_media_queries)).

  ```css
  @import url("https://tranquil-tr0.github.io/rose-pine-discord-theme/rose-pine.theme.css")
  (prefers-color-scheme: dark);
  @import url("https://tranquil-tr0.github.io/rose-pine-discord-theme/rose-pine-dawn.theme.css")
  (prefers-color-scheme: light);
  ```

- Q: **_"Can I disable Rainbow Threads"_**
- A: Yes, by placing the following in your QuickCSS threads will be the same colour as typical channels. *note: please respect the `space` between the colon and semi-colon*
  ```css
  :root {
    --ctp-rainbow-thread-disabled: ;
  }
  ```

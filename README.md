# ermis-chat-css

> Bundled CSS for ErmisChat SDKs

## Install

```bash
# with npm
npm install --save ermis-chat-css
# with yarn
yarn add ermis-chat-css
```

## Usage

This repository comes as a dependency of `ermis-chat-react-sdk` and doesn't
require explicit installation if you're using the component library. Add the
styles to your app by importing the bundled CSS:

```tsx
import 'ermis-chat-css/dist/css/index.css';
```

## License

## Icons - for Stream Developers

- The icons for the UI components can be exported from
  [Figma](https://www.figma.com/files/project/42134328/SDK-Teams-support-files?fuid=1038443988589634784)
- Icons are used as fonts, the font files are located in `src/assets/icons`
- If you need to change icons you have to regenerate the icon fonts:

1. Go to [https://fontello.com/](https://fontello.com/)
2. Upload the `svg` font from `src/assets/icons`
3. Edit the font
4. Set the font name to `stream-chat-icons` and the CSS prefix to
   `str-chat__icon--`
5. Download the font, and copy the content of the `font` folder to
   `src/assets/icons`, and copy the mapping from `css/stream-chat-icons.css` to
   `src/v2/Icon/Icon-layout.scss`

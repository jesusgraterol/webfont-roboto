# WebFont: Roboto

The `webfont-roboto` package simplifies self-hosting the [Roboto Font](https://fonts.google.com/specimen/Roboto) for your web applications. This means you can use the font without relying on external services. It works with both vanilla CSS and popular frameworks like Tailwind.

</br>

## Getting Started

Install the package:

```bash
$ npm install -S webfont-roboto
```

Import it into your main stylesheet:

```css
@import url('/node_modules/webfont-roboto/dist/index.css');
```

Register it in your application:

```css
html {
  font-family: "Roboto", sans-serif;
  font-size: 16px;
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  ...
}
```


Alternatively, if you're using Tailwind CSS:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer base {
  html {
    font-family: "Roboto", sans-serif;
    font-size: 16px;
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    ...
  }
}
```





<br/>

## Built With

- CSS





<br/>

## License

[MIT](https://choosealicense.com/licenses/mit/)





<br/>

## Acknowledgments

- [Google Fonts](https://fonts.google.com/specimen/Roboto)





<br/>

## Deployment

1. Install dependencies:
```bash
$ npm install
```

2. Build the package:
```bash
$ npm start
```

3. Publish to `npm`:
```bash
$ npm publish
```
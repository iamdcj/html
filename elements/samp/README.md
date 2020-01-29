# Sample Output

The `<samp />` element's purpose is to enclose inline text which renders copy representing the output of a computer program.

```
<p>
  The console printed the following:
  <br >
  <samp>
  HELLO WORLD!
  </samp>
<p>
```

See [example](samp.html)

The `<samp />` element is to be confused with the `<output />` element; if the contents is calculated code from a program then it should reside within an `<output />` element.

### Styling

#### Font amily

The font family used for the `<samp />` element is set to the browser's default monospace font.

Any attempt to override the font-family via CSS is not guaranteed to be respected by the browser engine.

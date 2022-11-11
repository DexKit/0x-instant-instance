## 0x Instant

Minimal code to run instant in your app:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <script src="https://dexkit-storage.nyc3.digitaloceanspaces.com/zrx/v4/instant.js"></script>
  </head>
  <body>
    <script type="text/javascript">
      function renderZeroExInstant() {
        zeroExInstant.render({}, "body");
      }
    </script>
    <button onClick="renderZeroExInstant()">Hello World</button>
  </body>
</html>
```

The package is available as a UMD module named `zeroExInstant` at https://instant.0x.org/v4/instant.js or https://dexkit-storage.nyc3.digitaloceanspaces.com/zrx/v4/instant.js.

Check 0x instant code source at [Instant](https://github.com/0xProject/0x-instant)

# Deployment

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FDexKit%2F0x-instant-instance)

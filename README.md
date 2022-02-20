# AdonisJS Assets Compilation Issue

I seem like I don't see the frontend assets are being output by **encore** package. I expect it to look like [this](http://prnt.sc/26xton4), instead I get [this](http://prnt.sc/26xtky1). I have already [created an issue](https://github.com/msrumon/adonisjs-assets-compilation-issue/issues/1) to work on that.

## Reproduction Steps

```bash
docker compose run --rm yarn install
```

```bash
docker compose up -d app
```

Now visit <http://localhost:3333>.

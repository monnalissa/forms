# forms

Generic forms with easily customizable theme

## Demo

[https://monnalissa.github.io/forms/](https://monnalissa.github.io/forms/)

## Run & Build

```bash
# Run Dev
sitegen -site ./ -public ./docs -base /forms -serve

# Build
sitegen -site ./ -public ./docs -base /forms -clean -minify
mv docs tmp && mv tmp/forms docs && rm -rf tmp
```
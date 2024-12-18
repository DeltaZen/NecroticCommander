# Necrotic Commander

A little tower defense. This is a WebXDC port of https://github.com/d-jeffery/NecroticCommander

## Developing

### Installing Dependencies

After cloning this repo, install dependencies:

```
pnpm i
```

### Testing the app in the browser

To test your work in your browser (with hot reloading!) while developing:

```
pnpm start
```

### Building

To package the WebXDC file:

```
pnpm build
```

The resulting optimized `.xdc` file is saved in `dist-xdc/` folder.

### Releasing

To automatically build and create a new GitHub release with the `.xdc` file:

```
git tag -a v1.0.1
git push origin v1.0.1
```

# Steps to reproduce

This will fail:

```sh
# install latest pnpm
npm i -g pnpm

# reset everything (in case built before)
pnpm run reset

# build
pnpm run build

```

This will execute successfully:

```sh
# install latest known working version of pnpm
npm i -g pnpm@3.5.3

# reset everything (in case built before)
pnpm run reset

# build
pnpm run build

```
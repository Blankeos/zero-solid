# Zero + Solid + TypeScript + Vite

## Some notes I have

1. Only use `npm`, not bun or pnpm: https://bugs.rocicorp.dev/issue/3292.

- Though one way to use Bun is to add trustedDependencies with the `"@rocicorp/zero-sqlite3"`

2. It's nice, very fast.
3. The folder structure is not ideal for me.

- 3x tsconfigs. Why?
- docker folder for docker-compose. With seed.sql and wait-for-pg.sh. Not sure what those are for.

```bash
git clone git@github.com:rocicorp/hello-zero-solid.git
cd hello-zero-solid
npm install
npm run dev:db-up

# in a second terminal
npm run dev:zero-cache

# in yet another terminal
npm run dev:ui
```

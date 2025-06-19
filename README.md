# OpsLayer shared configs

## Install

```shell
pnpm add -D opslayertech/shared-configs
```
## [Biome.js](https://biomejs.dev/)
### [Shared config usage](https://biomejs.dev/guides/configure-biome/#share-a-configuration-file)



`package.json`

```json
  "devDependencies": {
    "@opslayertech/shared-configs": "github:opslayertech/shared-configs",
  },
```

`biome.json`

```json
{
  "extends": ["@opslayertech/shared-configs/biome"]
}
```

BiomeV2

```json
{
  "extends": ["@opslayertech/shared-configs/biomeV2"]
}
```

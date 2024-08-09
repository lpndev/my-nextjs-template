## Getting Started
Please, run the following commands on your local environment.

### Build for development

#### Clone repository and rename
```shell
git clone https://github.com/lpndev/template.git
mv template [project-name]
cd [project-name]
```

#### Update dependencies
```shell
pnpm update
```

#### Initiate project
```shell
pnpm install
pnpm run dev
```

### Build for deploy

> It's a good practice test the app with Google Lighthouse!

#### Check code
```shell
pnpm run lint
pnpm run format
```

#### Build locally
```shell
pnpm run build
pnpm run start
```

## License
Licensed under the [MIT](https://github.com/lpndev/template/blob/main/LICENSE) license.
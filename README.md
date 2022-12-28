# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) which lets you scaffold and manage your project in seconds.

### Usage

Add environment variables (.env)

```
HOST=0.0.0.0
PORT=1337
APP_KEYS=MpbTvKK0q5E4VsnXAkOPow==,W9XxV8P1TDVKNsUoGB/7Ig==,50sVtUcavOpkMms/a9zJrw==,/vBLyozD6+g7tB86fFyOyQ==
API_TOKEN_SALT=FFvk73QUjn3Ua9z/84Y22A==
ADMIN_JWT_SECRET=9Du9xI2wbZPOHGOGVj3BMQ==
DATABASE_HOST=127.0.0.1 #For local database
DATABASE_PORT=5432
DATABASE_NAME=<CREATE EMPTY DB IN POSTGRESQL AND ENTER THE NAME HERE>
DATABASE_USERNAME=<YOUR DATABASE USERNAME>
DATABASE_PASSWORD=<YOUR DATABASE PASSWORD>
DATABASE_SSL=false
JWT_SECRET=tiwk6JRjN0YkVQVRf8lhrQ==
```

### Install dependencies

The dockerfile contains configurations for yarn. So its preferable to install yarn first.

```
yarn install
# or
npm install
```

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```
npm run build
# or
yarn build
```

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

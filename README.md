# Svelte Starter


This Svelte starter template provides a comprehensive foundation for developing with Svelte and Vite, including preconfigured support for TailwindCSS, Flowbite-Svelte, and Svelte-Spa-Router. Additionally, it includes a sample implementation of fetching data from a backend API, making it easy to integrate with your own server-side infrastructure.

## Installation

```bash
git clone git@github.com:shinokada/svelte-starter.git my-app
cd my-app
pnpm i
```

Update dependencites:

```sh
pnpm update
pnpm i flowbite-svelte@latest flowbite@latest
```

## Backend API env value

Update your backend API value in `.env`:

```text
API_ENDPOINT=http://localhost:3000/api
API_SECRET=1234
```

## Start a local server

```bash
npm run dev
```

## How to use this for GitHub page

```
npm run build
npm run deploy
```

This will deploy your GitHub page to `https://<username>.github.io/<repository name>` URL. Don’t forget to change the username and repository name to your personal Github username and repository.
It may take a couple of minutes. You can check the progress in GitHub Actions tab.

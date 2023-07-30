# Twiter Clone with T3 Stack

Build A Twitter-Like Social Media App Using [The T3 Stack](https://create.t3.gg/)

Live Demo: https://t3-twitter-clone.hwangblood.com

## App Setup

### PlanetScale Setup

https://app.planetscale.com

### Authentication Setup

https://create.t3.gg/en/usage/next-auth#setting-up-the-default-discordprovider

also, generate a new secret and paste it into `.env` as `NEXTAUTH_SECRET` to make app a little bit safer

### Deployment Setup

Follow deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.

## Run app in dev

```shell
yarn prisma db push
yarn run dev
```


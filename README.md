# Twiter Clone with T3 Stack

Build A Twitter-Like Social Media App Using [The T3 Stack](https://create.t3.gg/)

## App Setup

### PlanetScale Setup

https://app.planetscale.com

### Authentication Setup

https://create.t3.gg/en/usage/next-auth#setting-up-the-default-discordprovider

also, generate a new secret and paste it into `.env` as `NEXTAUTH_SECRET` to make app a little bit safer

## Run app in dev:

```shell
yarn prisma db push
yarn run dev
```


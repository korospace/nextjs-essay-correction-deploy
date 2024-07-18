### Before you guys push the repo, run steps bellow for migrate to vercel's remote postgres

#### 1. Make sure you have create vercel's postgres

#### 2. copy env.template to .env

```
cp env.template .env
```

#### 3. run

```
yarn install

yarn prisma migrate dev

yarn run db-seed
```

# Creating a Stock index tracker

Today we will create a stock index tracker using NextJS, Firebase and Shadcn UI.

# Getting started

First create a NextJs project by running the following command:

```bash
pnpm create next-app@latest stock-index-tracker --typescript --tailwind --eslint
```

Then install firebase using the [following link](https://firebase.google.com/docs/cli#install-cli-mac-linux)

ANd login to firebase

```bash
firebase login
```

Then enable frameworks

```
firebase experiments:enable webframeworks
```

Then create a new project on firebase and link it to your project

```bash
firebase init hosting
```


## Errors encountered

The build failed for the `npm ci` command for firebase hosting as that expects a package.lock.json file. I had to change the command to `npm install` to fix the issue.



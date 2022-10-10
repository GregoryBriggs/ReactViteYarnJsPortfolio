# ReactViteYarnPortfolioGregBriggs

## Original setup steps

NPM is required to install yarn. Make sure the lastest is installed and avialable

Download and install NodeJS latest

Run 

```
npm i yarn -g
```

to install yarn globally. Check for up-to-date instructions for Yarn as these change with some regularity. Most notable at time of install was that ```.yarnrc.yml``` had to be added manually and a nodelinker key needed to be added of value of ```[pnp|pnpm|node_modules]```

e.g.
```
nodelinker: pnp
```

> Note: pnp is Plug-N'-Play and manages transative dependencies. 

### Install react

Yarn can be installed via vite and react
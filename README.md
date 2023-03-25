# pwa_test


## setup

```
$ docker-compose run --rm node sh -c  "npm install -g @vue/cli @vue/cli-init && vue create pwa_vue && chown -R node:node /app"

---
> Manually select features
> Babel, Progressive Web App (PWA) Support, Linter / Formatter
> 3.x
> ESLint with error prevention only
> Lint on save
> In package.json
> Use NPM
```

```
$ docker-compose up -d
```


## build

```
$ docker exec pwa_test sh -c "cd pwa_vue && npm run build"
```

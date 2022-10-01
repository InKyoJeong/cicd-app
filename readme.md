 ## React CI/CD

http://poor-question.surge.sh/

## start

```bash
$ npm start
```

## prettier

```bash
# npx prettier --write "**/*.js"
# npx prettier --check "**/*.js"


$ npm run format
$ npm run format:check
```

## test

```bash
CI=true npm run test -- --coverage
```

## deploy

```bash
$ surge
# domain: http://poor-question.surge.sh/

# token: surge token
# email: surge whoami
```
# ts-boilerplate
Starter typescript template project

- Linting with eslint
- Consistent formatter with prettier
- Pre-commit hook using husky

Scripts:

```
{
  "build": "rimraf ./dist && tsc",
  "dev": "nodemon",
  "start": "node dist/index.js",
  "lint": "eslint . --ext .ts",
  "fix": "eslint . --ext .ts --fix",
  "format": "prettier --config .prettierrc 'src/**/*.ts' --write",
  "test": "echo \"Error: no test specified\" && exit 0",
  "prepare": "husky install"
}
```


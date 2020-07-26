# test-babel-node-configuration-files

This fails:
```bash
./node_modules/.bin/babel-node --config-file ./.test-babelrc.js -e "const a = 1"
```

This works:
```bash
./node_modules/.bin/babel-node --config-file ./.test-babelrc.js ./test.js
```

# eslint-ignore-test

```sh
$ node_modules/.bin/eslint .
$ node_modules/.bin/eslint ignoreDir/

Oops! Something went wrong! :(

ESLint: 6.8.0.

ESLint couldn't find the config "invalid" to extend from. Please check that the name of the config is correct.

The config "invalid" was referenced from the config file in "/eslint-ignore-test/ignoreDir/.eslintrc.json".

If you still have problems, please stop by https://gitter.im/eslint/eslint to chat with the team.
```

I expect `eslint ignoreDir/` to behave like `eslint .`.

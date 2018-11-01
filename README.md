
# 使用详情

```sh
yarn
yarn workspace @foobar/umi-monorepo-test start
```

会出现错误

```
$ umi dev
✖  error     Plugin built-in:plugins/afwebpack-config initialize failed

Cannot find module '/Users/me/playground/umi-monorepo/packages/@foobar/umi-monorepo-test/node_modules/react/package.json'
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed.
Exit code: 1
Command: /usr/local/Cellar/node/11.0.0/bin/node
Arguments: /usr/local/Cellar/yarn/1.12.1/libexec/lib/cli.js start
Directory: /Users/me/playground/umi-monorepo/packages/@foobar/umi-monorepo-test
Output:
```

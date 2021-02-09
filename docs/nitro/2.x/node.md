# Installing Node Dependencies

Nitro’s [`npm`](commands.md#npm) command lets you to run any npm command without having Node or npm installed on your host machine.

```bash
$ cd ~/dev/my-craft-project
$ nitro npm install
  … checking /Users/oli/dev/docs/package.json ✓
  … pulling docker.io/library/node:14-alpine ✓
Running npm install

131 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

npm install complete 🤘
```

## Specifying a Node Version

The `npm` command allows to to specify any version of node based on the Docker Image tags. To use a different version of npm, run the following:

```bash
$ nitro npm --node-version=12 install
```

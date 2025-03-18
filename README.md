# SimpleLocalize CLI via npm (work in progress)

The main goal of this project is to give frontend developers an easier way to use the [SimpleLocalize CLI](https://github.com/simplelocalize/simplelocalize-cli) in their workflows.

## Installation

```
npm install @simplelocalize/cli@1.0.8
```

After installing the package, it should automatically choose the right binary for your system, [download it](https://github.com/simplelocalize/simplelocalize-cli/releases), and install it into the `node_modules/.bin` directory, making it available for your scripts in `package.json`.

> The work on this package is in progress, and at the time of writing this documentation, the plugin installs the newest version of the CLI, which is 2.8.0.

## Usage

After successfully installing the SimpleLocalize CLI in your project, you should be able to use it in the `package.json` scripts to build a workflow of your choice.

```
{
  "name": "My project",
  "version": "1.0.0",
  "private": true,
  "dependencies": {
    "@simplelocalize/cli": "^1.0.8",
  },
  "scripts": {
    "start": "react-scripts start",
    "sl:download": "simplelocalize downlaod",
    "sl:upload": "simplelocalize upload",
    "sl:autotranslate": "simplelocalize autotranslate"
  },
}
```

Learn more about [SimpleLocalize CLI commands](https://github.com/simplelocalize/simplelocalize-cli)

## System installaton

To install the CLI globally in your system please follow the instructions here: https://simplelocalize.io/docs/cli/get-started/

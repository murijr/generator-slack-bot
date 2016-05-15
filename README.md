<h1 align="center">Slack bot Yeoman Generator</h1>
<p align="center">
  <img title="yeoman generator" src='/assets/yeoman-logo.png' alt='yeoman logo' width="100px" height="100px" />
  <img title="slack logo" src='/assets/slack-logo.png' alt='slack logo' width="100px" height="100px" />
</p>
<p align="center">
  <a title='Build Status' href="https://travis-ci.org/eromano/generator-slack-bot" >
    <img src='https://travis-ci.org/eromano/generator-slack-bot.svg?branch=master' alt='Build Status'  />
  </a>
  <a href='https://coveralls.io/r/eromano/generator-slack-bot'>
    <img src='https://img.shields.io/coveralls/eromano/generator-slack-bot.svg' alt='Coverage Status' />
  </a>
  <a href='https://github.com/eromano/generator-slack-bot/blob/master/LICENSE'>
    <img src='https://img.shields.io/badge/license-MIT-blue.svg' alt='license' />
  </a>
  <a alt='downloads stats' href='https://npmjs.org/package/generator-slack-bot'>
    <img src='https://img.shields.io/npm/dm/generator-slack-bot.svg' alt='downloads stats' />
  </a>
  <a href="https://nodei.co/npm/generator-slack-bot/">
    <img src="http://img.shields.io/npm/v/generator-slack-bot.svg" alt='npm version' >
  </a>
</p>

## About Slack bot Yeoman Generator
>Full Yeoman Generator to create Slack Bot with travis, coveralls and test.

## Installation

First, install [Yeoman](http://yeoman.io) and generator-slack-bot using [npm](https://www.npmjs.com/) (we assume you have pre-installed [node.js](https://nodejs.org/)).

```bash
npm install -g yo
npm install -g generator-slack-bot
```

Then generate your new Bot:

```bash
yo slack-bot
```

Which will generate the following project structure, if for example your bot name is Mazinga:

    ├── '.travis.yml',
    ├── '.gitignore',
    ├── '.jscsrc',
    ├── 'LICENSE',
    ├── 'README.md',
    ├── 'app.json',
    ├── 'package.json',
    ├── 'Gruntfile.js',
    ├── 'configBot.json',
    ├── 'grunt/coveralls.js',
    ├── 'grunt/jscs.js',
    ├── 'grunt/jshint.js',
    ├── 'grunt/mocha_istanbul.js',
    ├── 'grunt/mochaTest.js',
    ├── 'src/main.js',
    ├── 'src/botMazinga.js',
    ├── 'test/botMazinga.spec.js',
    └── 'test/mockoBjects/channel.js'

And run `npm install` for you to fetch all dependencies.

## Getting Started with the bot

In order to make the bot works you need a TOKEN_SLACK.
Your Slack bot integration token is obtainable at https://my.slack.com/services/new/bot.
After you have obtained your TOKEN_SLACK copy it in the configBot.json

## History

For detailed changelog, see [Releases](https://github.com/Alfresco/generator-slack-bot/releases).

## Contributors

Contributor | GitHub profile | Twitter profile |
--- | --- | ---
Eugenio Romano (contributor)| [Eugenio Romano](https://github.com/eromano) | [@RomanoEugenio](https://twitter.com/RomanoEugenio)

All contributors [contributors](https://github.com/eromano/generator-slack-bot/graphs/contributors).

## License
[MIT](https://github.com/eromano/generator-slack-bot/blob/master/LICENSE)
 

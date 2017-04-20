# npmtest-claudia-bot-builder

#### basic test coverage for  claudia-bot-builder (v2.15.0)  [![npm package](https://img.shields.io/npm/v/npmtest-claudia-bot-builder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-claudia-bot-builder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-claudia-bot-builder.svg)](https://travis-ci.org/npmtest/node-npmtest-claudia-bot-builder)

#### Create chat-bots for various platforms and deploy to AWS Lambda quickly

[![NPM](https://nodei.co/npm/claudia-bot-builder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/claudia-bot-builder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-claudia-bot-builder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-claudia-bot-builder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-claudia-bot-builder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/test-report.html](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-claudia-bot-builder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-claudia-bot-builder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-claudia-bot-builder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-claudia-bot-builder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-claudia-bot-builder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "claudia-bot-builder",
    "version": "2.15.0",
    "description": "Create chat-bots for various platforms and deploy to AWS Lambda quickly",
    "main": "index.js",
    "scripts": {
        "pretest": "eslint lib spec *.js",
        "test": "node spec/support/jasmine-runner.js",
        "debug": "node debug spec/support/jasmine-runner.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/claudiajs/claudia-bot-builder"
    },
    "keywords": [
        "claudia",
        "aws",
        "lambda",
        "apigateway",
        "bot",
        "chatbot",
        "messenger",
        "telegram",
        "viber",
        "line",
        "alexa",
        "skype",
        "slack",
        "twilio",
        "kik",
        "groupme"
    ],
    "author": "Slobodan Stojanovic <slobodan@cloudhorizon.com> (http://slobodan.me/), ",
    "contributors": [
        "Alexander Simovic (https://github.com/simalexan)",
        "Gojko Adzic <gojko@gojko.com> (https://gojko.net)"
    ],
    "license": "MIT",
    "dependencies": {
        "alexa-message-builder": "^1.1.0",
        "claudia-api-builder": "^2.0.1",
        "minimal-request-promise": "^1.3.0",
        "oh-no-i-insist": "^1.0.0",
        "souffleur": "^1.0.0",
        "tsscmp": "^1.0.5"
    },
    "devDependencies": {
        "claudia": "^2.0.0",
        "eslint": "^2.11.1",
        "eslint-config-defaults": "^9.0.0",
        "fake-http-request": "^1.3.0",
        "jasmine": "^2.5.2",
        "jasmine-spec-reporter": "^2.7.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

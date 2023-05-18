# botium-crawler
This repo is to test the botium crawler feature via cli

Installation and set up would be same as botium-test repository(refer the other repo)

Make sure you have updated version of Node.js and npm

Then install the botium-cli related things and then run below command to test botium-crawler for the sample Google dialogflow

> botium-cli crawler-run

After every run, make sure you clear crawler-result folder, because that is where your new scripts get added after every crawl and you can also add them to test_cases folder before clearing the folder, else you will see error like below,


_Botium-Crawler failed:  Error: The output path 'crawler-result/scripts' has to be empty
    at handler (/usr/local/lib/node_modules/botium-crawler/src/crawler-run/index.js:31:13)
    at builder.handler (/usr/local/lib/node_modules/botium-cli/bin/botium-cli.js:34:7)
    at /usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:8993
    at j (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:4956)
    at _.handleValidationAndGetResult (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:8962)
    at _.applyMiddlewareAndGetResult (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:9604)
    at _.runCommand (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:7231)
    at [runYargsParserAndExecuteCommands] (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:58539)
    at te.parse (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:40478)
    at te.get [as argv] (/usr/local/lib/node_modules/botium-cli/node_modules/yargs/build/index.cjs:1:62028)
THSLT10075:botium_trial_four leela$ botium-cli crawler-run_

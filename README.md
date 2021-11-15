<h1>WebdriverIO-with-require-and-import</h1>

To enable webdriverio to run tests in the 'require' and 'import' code styles 
at the same time, package.json files with {"type": "module"} have been created 
in the folders with the 'import' code style.

Now possible to run test file example.e2e.js in 'require' mode by: <br>
<strong>npx wdio run ./wdio.conf.js --spec example.e2e.js</strong>


and without any changed code to run test file example.e2e.import.js in 
'import' mode by:<br>
<strong>npx wdio run ./wdio.conf.js --spec example.e2e.import.js</strong>
# node-windows-spa-custom-deployment-scripts
Examples of quickstart SPA's, SSR's, or Node frameworks requiring a build for client code or transpiling, using custom deployment scripts on Node.js App Service Windows

To initiate a custom deployment script, we need two files:
- a `.deployment` file which points to the actual deployment script we want to run
- a custom deployment script (in this case named `deploy.cmd`.

[KuduScript](https://www.npmjs.com/package/kuduscript) can be used to scaffold out a quick deployment script example (and can be changed as needed).

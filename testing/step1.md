# Getting started with Zowe

Zowe is an integrated and extensible open source framework for z/OS.

Zowe offers modern interfaces to interact with z/OS and allows you to work with z/OS in a way that is similar to what you experience on cloud platforms today. You can use these interfaces as delivered or through plug-ins and extensions that are created by clients or third-party vendors.

Zowe is composed of several components, each improving the learning ability, accessibility, and possibility of mainframe development.

For more information, visit www.zowe.org

All the dependencies are preinstalled, primarily NodeJS and NPM. 
Now we can install zowe, so run:
`npm install @zowe/cli`{{execute}}
This uses the public repo to get the Zowe CLI utility.

To run Zowe CLI, as we didn't install this globally, we would have to run `npx zowe`{{execute}}.

To make it easier to run.  Runt this:
`alias zowe="npx zowe"`{{execute}}

Without this, you would need to type `npx zowe` to run the command. We can now run `zowe`{{execute}}

# Getting started with Zowe

Zowe is an integrated and extensible open source framework for z/OS.

Zowe offers modern interfaces to interact with z/OS and allows you to work with z/OS in a way that is similar to what you experience on cloud platforms today. You can use these interfaces as delivered or through plug-ins and extensions that are created by clients or third-party vendors.

Zowe is composed of several components, each improving the learning ability, accessibility, and possibility of mainframe development.

For more information, visit www.zowe.org

We need to install zowe, so run:
`npm install @zowe/cli`{{execute}}

Now we need to make it easier to run.  As we do not have global rights, add this line:
`alias zowe="npx zowe"`{{execute}}

Without this, you would need to type `npx zowe` to run the command. We can now run `zowe`{{execute}}
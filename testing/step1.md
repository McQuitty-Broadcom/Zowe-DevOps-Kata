# Getting started with Zowe
All the dependencies are preinstalled, primarily NodeJS and NPM. 

Note, you can click on the commands and they will run for you, or you can type them into the terminal in the lower right.
Let's ensure our system is set up properly and run:
``source envs.sh``{{execute}}
This file sets our Zowe login information, so we aren't prompted for it later.

Now we can install zowe, so run:
`npm install @zowe/cli`{{execute}}
This uses the public repo to get the Zowe CLI utility.

To run Zowe CLI, as we didn't install this globally, we run `npx zowe`{{execute}}.

To make it easier to run.  Run the alias command:
`alias zowe="npx zowe"`{{execute}}

Without this, you would need to type `npx zowe` to run the command every time. We can now type just `zowe`{{execute}}

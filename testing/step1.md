The Katacoda Ubuntu Environment is a flexible single node environment. Users are connected to the environment as root. This provides them with full flexibility to install additional packages, explore the internals of Linux and experiment with new ideas.

The environment also comes with Docker, meaning additional containers can be pulled and access as and when required.

We need to install zowe, so run:
`npm install @zowe/cli`{{execute}}

Now we need to make it easier to run.  As we do not have global rights, add this line:
`alias zowe="npx zowe"`{{execute}}

Without this, you would need to type `npx zowe` to run the command. 
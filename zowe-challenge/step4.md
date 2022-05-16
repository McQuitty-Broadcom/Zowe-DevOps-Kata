In order to use those services, we need to tell Zowe how to connect to the mainframe.  

We are using Zowe V2, verifiable by running `zowe -V`{{execute}}

With Zowe V2, we can use configuration files.  These files describe the services available and how to access them.  All we need to do is provide the login details. 

We have the configuration files loaded for you.  

Zowe will read this in the current directory and prompt us for the details. 

To get a list of datasets, we can run:

`zowe files list data-set cust001.*`{{execute}}

If this runs successfully, you should see a list of datasets.

If you are prompted for a hostname, username and passowrd, press CTRL+C.
The re-run ``source envs.sh``{{execute}}
Then retry the command above.
Now let's upload the files back to the mainframe.  

We do this using the `zowe files upload dtp` command.  There's various options, but we will use the full upload here.

The command will upload a directory to pds (dtp).  It takes two parameters.  The first is the directory that contains the members, the second is the PDS we are sending it to.  You'll note that cust001/marbles/jcl is very similar to cust001.marbles.jcl.  This is because the `zowe download all-members` creates a directory structure to match the HLQ. 

Let's add our new member back to the mainframe.
`zowe files upload dtp cust001/marbles/jcl cust001.marbles.jcl`{{execute}}

The screen will show the status of the upload.  

Now, we can run `zowe files list am "cust001.marbles.jcl"`{{execute}} and see the new member on the mainframe.

Now let's take a look into a data-set.  Let's download all the members of a dataset and inspect them.

Run the download command for all members in the cust001.marbles.jcl dataset:
`zowe files download all-members "cust001.marbles.jcl"`{{execute}}

In the VS Code section, you will notice that a new folder appeared, called "cust001".  You can open that folder and view the contents.

There should be six files in that folder.  These include "marbcopy.txt", "marbdb2.txt", etc.

You can click on any of those files and view the contents.


Let's create a new member:
`touch cust001/marbles/jcl/newmember.txt`{{execute}}
`/root/cust001/marbles/jcl/newmember.txt`{{open}}
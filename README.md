# Red Hat JBoss Fuse: Tooling Tutorials

The `jbdsis-tooling-tutorials-jboss-fuse-63.zip` file contains two folders:

## blueprintContexts Folder
Contains two prefabricated `blueprint#.xml` files (5 and 6), which enable you to run through individual tutorials 5, 6, 7, 8 and 9, without having to complete any preceding tutorial, except tutorial 2, _To Create a New Route_, which is the only tutorial you must complete to be able to work through the remaining tutorials.

* Use `blueprint5.xml`, which is the routing context resulting from completing tutorial 4, to complete tutorial 5, _To Add Another Route to the CBR Routing Context_
* Use `blueprint6.xml` to complete any of the tutorials 6 through 9:
_To  Debug a Routing Context_, 
_To Trace a Message Through a Route_,
_To Test a Route with JUnit_, and _To Publish a Fuse Project to Red Hat JBoss Fuse_.


To use either of the prefabricated `blueprint#.xml` files:

1. Unzip `jbdsis-tooling-tutorials-jboss-fuse-63.zip` in a convenient location external to the CBRroute project’s workspace.
2. Delete the existing `blueprint.xml` file from the `CBRroute/src/main/resources/OSGI-INF/blueprint/` folder. 
3. Install the `blueprint#.xml` file corresponding to the tutorial that you want to complete in the vacated `CBRroute/src/main/resources/OSGI-INF/blueprint/` folder.
4. Rename the `blueprint#.xml` file to `blueprint.xml`.
5. In the Red Hat JBoss Fuse: Tooling Tutorials guide, follow the instructions for completing the target tutorial.

## Messages folder
Contains six prefabricated `message#.xml` files (1 through 6), which are provided to jumpstart your working through any of the eight tutorials in the Red Hat JBoss Fuse: Tooling Tutorials guide. If you are working through tutorial 1, _To Create a New Route_, you need not install `message1.xml`.

Install the prefabricated `message#.xml` files into your CBRroute project’s `src/data/` folder.
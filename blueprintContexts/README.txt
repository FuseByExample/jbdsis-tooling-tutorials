Red Hat JBoss Fuse: Tooling Tutorials
—————————————————————————————————————

camelContexts.zip
—————————————————
Contains two prefabricated blueprint#.xml files (5 and 6) to use to run through individual tutorials 5, 6, 7, and 8, without having to complete preceding tutorials, except 2. 

NOTE: The only tutorials you must complete to be able to work through the remaining tutorials are 2 “To create a New Route” and 8 “To Test a Route with JUnit”.

* Use blueprint5.xml to complete tutorial 5 “To Add Another Route to the CBR Routing
  Context”
* Use blueprint6.xml to complete any of the tutorials 6 through 8: “To  Debug a Routing Context,” 
  “To Trace a Message Through a Route,” and “To Test a Route with JUnit”
* To complete tutorial 9, “To Publish a Fuse Project to Red Hat JBoss Fuse” you must have successfully completed
  tutorial 8 “To Test a Route with JUnit” and saved the CBRroute project.


To use any of the prefabricated blueprint#.xml files:
1. Unzip camelContexts.zip in a convenient location external to the CBRroute project’s workspace.
2. Delete the existing blueprint.xml file from the CBRroute/src/main/resources/OSGI-INF/blueprint/ folder. 
3. Install the blueprint#.xml file corresponding to the tutorial that you want to complete in the vacated CBRroute/src/main/resources/OSGI-INF/blueprint/ folder.
4. Rename the blueprint#.xml file to blueprint.xml.
5. In the Red Hat JBoss Fuse: Tooling Tutorials guide, follow the instructions for completing the target tutorial.
# emberJS-reOpen-reOpenClass
Updating the class implementation without redefining it and reopening the class by specifying new properties in it


open the app.js file and add the following line at the top of the file −

import reopenclass from './reopenclass';
Where, reopenclass is a name of the file specified as "reopenclass.js" and created under the "app" folder.

Next call the inherited "reopenclass" at the bottom, before the export. It executes the reopenclass function which is created in the 
reopenclass.js file −

reopenclass();

Only reopenclass.js file included in the repository

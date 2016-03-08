# wsaccess-javascript-sample-plugins

Starting with Oxygen 17.1 you can create a workspace access plugin to contribute custom toolbar and menu actions or custom behaviors using Javascript and the Rhyno engine:
https://www.oxygenxml.com/doc/versions/17.1/ug-editor/#concepts/workspace-access-plugin-js.html

Each of the folders in this repository is a sample plugin which use this technology to alter different behaviors in Oxygen. So if you take each of these folders, copy it to the "OXYGEN_INSTALL_DIR/plugins" folder and start Oxygen, the plugin will start to work.

The sample plugin "runScenarios" adds a toolbar action called "Transform to PDF". When the button is pressed, it invokes an already defined transformation scenario called "DITA PDF" on the current opened XML document.

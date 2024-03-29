**How to create new plugin modules, including a custom build.gradle using templates with one click:**

- Inside your IntelliJ Idea Settings (File -> Settings, or Ctrl + Alt + S) go to Plugins.

- At the top click “Marketplace” Search for “Generate Module From Template” and press install.

- While still in your settings, in the top left corner search for “templates”, you should see “File and Code Templates” on your left side, its inside the Editor dropdown menu.

- Make sure you have 4 templates set up, "Piggy Plugin", "Piggy Overlay", "Piggy Config" (with an extension of “java”) and "Piggy Build" (with a file name of “build” and an extension of “gradle”). 
Templates for these will be appended to the bottom of this guide.
If you want a 'plug and play' experience (pun intended), make sure to name yours exactly as I did above.

- Scroll to the bottom of the left-hand side menu. Inside the Tools dropdown menu you should see “Module Template Settings”

- Inside the top left corner of the Module Template Settings, where the +, -, Paste, Import and Save icons are located.
Click on the “Blue Import Icon” and using the Open File Dialog Menu, browse for "PiggyPlugins.json", which will also be appended to the bottom of this guide.

- Confirm the file “Structure” matches, and that the “File Template” names match your file template names, you may also want to check the “Placeholder” settings and set a Default Value for your PACKAGE_NAME i.e ‘com.piggyplugins’.

- Once you confirmed you’ve done everything correctly, right-click the ‘PiggyPlugins’ project folder, click “Create Module From Template”. 
You will be presented with a new plugin set-up menu, which will generate a plugin folder structure with the file templates you set up in your IDE.

Any questions feel free to PM or @ me

Credits to @polymorphicj for the templates.

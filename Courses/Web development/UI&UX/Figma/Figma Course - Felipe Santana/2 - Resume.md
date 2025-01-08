#Class11 #KeyBoardShortCuts #Constrants 
**2.1 - Frames**

Hierarchy - with frames we can create a structure in which there are frames within another frame, the internal frames respect a hierarchy, where the outside frames group all the internal frames.
![[Pasted image 20250108170836.png]]

	
	KEYBOARD SHORTCUTS:
		- Ctrl+D => Duplicates a selected object.
		- Alt+Drag the mouse => Duplicates an object 
		selected.
		- Ctrl+Alt+G => Activates frame selection. 
		Select the frames and type the shortcut to 
		group the frames.
		- a => Selects the frame in the toolbar.
	
Constrants or Restrictions - constrants have a lot to do with responsiveness. They define the behavior of elements on the screen, that is, what position each element will occupy on the screen when it changes size or orientation. Ex.: if the constraint is defined at [center], all content will be aligned to the center, on different screen sizes.
![[Pasted image 20250108171023.png]]

![[Pasted image 20250108171043.png]]


#Class12
**2.2 - Grid**

In figma, Grid is a layout grid system that organizes elements consistently across different media such as mobile devices, tablets, and desktops.

Pattern to start a figma design:
	Grid: columns
	Count: 4
	Type: stretch
	Width: auto
	Margin: 16
	Gutter: 16

*Note: once the Margin and Gutter are defined, when the screen changes size, the grid also changes, but the Margin and Gutter remain in the same space.
![[Pasted image 20250108171156.png]]

#Class13 #AtomicDesign #CreateMultipleComponents #Assets #ResetComponent
**2.3 - Componentes e Assets**

The concept of component basically comes from Atomic Design, where you have a main component (atom) and from it you can create other elements. 
![[Pasted image 20250108171703.png]]

This main component is available in your library, it becomes the master component, so all components derived from it are lower in the hierarchy. So every change made to the main component is reflected in its derivatives, but a change made to a derived component does not change the main one.

*Atomic Design is a methodology for creating interface design systems that organizes the visual development process into five levels: Atoms, Molecules, Organisms, Models, Pages.

*The idea is that a design can be broken down into its smallest parts, the "atoms", which can be combined to form more complex components. 

*See some examples of how Atomic Design elements work: 

- A search icon and an input box are two separate atoms.
- When you put these two atoms together, a molecule is formed, which is the search box.
- By adding block content placeholders below the search box, you create a template.
- By filling the template with content text and images, a complete page is created.

		KEYBOARD SHORTCUTS:
	
		Ctrl+Alt+K => Used to create components.
		T => Calls the text tool.
	

**To create a component, select the objects on the screen, click on the '"Create component" option on the toolbar or press the command Ctrl+Alt+K**

There is also the option to create multiple components. Just select the multiple objects and click on "Create multiple components" in the toolbar.
![[Pasted image 20250108172515.png]]

To access your components, simply select the "Assets" tab in the Layers sidebar, where all your created components will be saved.
![[Pasted image 20250108172412.png]]

*To reset the initial state of a derived component, go to "Reset all overrides" in the toolbar.*
![[Pasted image 20250108172326.png]]

#Class14
**2.4 - Essential shortcuts**

 - Space (keep pressed) => Activates the handtool.
 - F => Activates the default options sidebar for Frames.
 - Ctrl+Shift+H => Activates the function of hiding objects on the screen.
 - Ctrl+Shift+L => Activates the function to lock or deactivate the Layer of an object.
- Shift+A => Activates the AutoLayout function. Ex.: "Button with text in the center" Select the objects and type the shortcut Shift+A. Objects are transformed into Frame and are already converted into AutoLayout.

  
For a complete list of shortcuts, within Figma, go to the Figma icon (top left), Help and account, Keyboard Shortcuts.
![[Pasted image 20250108173221.png]]

		KEYBOARD SHORTCUTS:

		Ctrl+Alt+? => Opens a window with all Figma shortcuts.


#Class15 #InsertPhotosRandomly #DeletePlugins
**2.5 - Plugins**

To access the plugins page.
![[Pasted image 20250108174007.png]]

*Note: Always check the frequency and when the plugin was last updated.

To delete a plugin, click on the Figma icon (top left menu), Plugins, Manage plugins.
![[Pasted image 20250108174329.png]]

#Class17
**2.6 - Wireframes**

The Wireframe has the function of defining the content structure of our application, it helps to identify in order of priority what the hierarchy of elements will look like. 

Use an existing website as an example or model, which is a reference in the following, to identify the elements and components of each screen. This way you will have a starting point to build the project.
![[Pasted image 20250108174628.png]]
  
To start building the Wireframe, take screenshots of the template website pages and insert these images into the project. Using the model, map and define what the content architecture of your project will be like. And then wireframe your project.
![[Pasted image 20250108170604.png]]

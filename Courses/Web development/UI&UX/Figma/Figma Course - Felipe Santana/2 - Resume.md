#Class11 #KeyBoardShortCuts #Constrants 
**2.1 - Frames**

Hierarchy - with frames we can create a structure in which there are frames within another frame, the internal frames respect a hierarchy, where the outside frames group all the internal frames.
![[frame_grouping.png]]

	
	KEYBOARD SHORTCUTS:
		- Ctrl+D => Duplicates a selected object.
		- Alt+Drag the mouse => Duplicates an object 
		selected.
		- Ctrl+Alt+G => Activates frame selection. 
		Select the frames and type the shortcut to 
		group the frames.
		- a => Selects the frame in the toolbar.
	
Constrants or Restrictions - constrants have a lot to do with responsiveness. They define the behavior of elements on the screen, that is, what position each element will occupy on the screen when it changes size or orientation. Ex.: if the constraint is defined at [center], all content will be aligned to the center, on different screen sizes.
![[constrants_and_responsiveness.png]]

![[constrants_and_responsiveness2.png]]


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

***Note:** once the Margin and Gutter are defined, when the screen changes size, the grid also changes, but the Margin and Gutter remain in the same space.
![[grid.png]]

#Class13 #AtomicDesign #CreateMultipleComponents #Assets #ResetComponent
**2.3 - Componentes e Assets**

The concept of component basically comes from [[Atomic Design]], where you have a main component (atom) and from it you can create other elements. 
![[component.png]]

This main component is available in your library, it becomes the master component, so all components derived from it are lower in the hierarchy. So every change made to the main component is reflected in its derivatives, but a change made to a derived component does not change the main one.

		KEYBOARD SHORTCUTS:
	
		Ctrl+Alt+K => Used to create components.
		T => Calls the text tool.
	

**To create a component, select the objects on the screen, click on the '"Create component" option on the toolbar or press the command Ctrl+Alt+K**

There is also the option to create multiple components. Just select the multiple objects and click on "Create multiple components" in the toolbar.
![[multiple_components.png]]

To access your components, simply select the "Assets" tab in the Layers sidebar, where all your created components will be saved.
![[assets.png]]

*To reset the initial state of a derived component, go to "Reset all overrides" in the toolbar.*
![[reset_overrides.png]]

#Class14
**2.4 - Essential shortcuts**

 - Space (keep pressed) => Activates the handtool.
 - F => Activates the default options sidebar for Frames.
 - Ctrl+Shift+H => Activates the function of hiding objects on the screen.
 - Ctrl+Shift+L => Activates the function to lock or deactivate the Layer of an object.
- Shift+A => Activates the AutoLayout function. Ex.: "Button with text in the center" Select the objects and type the shortcut Shift+A. Objects are transformed into Frame and are already converted into AutoLayout.

  
For a complete list of shortcuts, within Figma, go to the Figma icon (top left), Help and account, Keyboard Shortcuts.
![[list_shortcuts.png]]

		KEYBOARD SHORTCUTS:

		Ctrl+Alt+? => Opens a window with all Figma shortcuts.


#Class15 #InsertPhotosRandomly #DeletePlugins
**2.5 - Plugins**

To access the plugins page.
![[plugin_page.png]]

***Note:** Always check the frequency and when the plugin was last updated.

To delete a plugin, click on the Figma icon (top left menu), Plugins, Manage plugins.
![[manage_plugin.png]]

#Class17
**2.6 - Wireframes**

The Wireframe has the function of defining the content structure of our application, it helps to identify in order of priority what the hierarchy of elements will look like. 

Use an existing website as an example or model, which is a reference in the following, to identify the elements and components of each screen. This way you will have a starting point to build the project.
![[template_website.png]]
  
To start building the Wireframe, take screenshots of the template website pages and insert these images into the project. Using the model, map and define what the content architecture of your project will be like. And then wireframe your project.
![[wireframe.png]]

#Class18 #DesignSistem #MaterialDesign #HardGrid #SoftGrid #PixelPerfect
**2.6 - Defining a Grid**

To start, you need to understand what [[Design Sistem]] is. 
Design System is the way in which the company communicates in its digital products, it defines the style sheet, components, images, interactions, among other things.

The company Google provides a vast amount of content on the subject for free, this content is Material Design. In it the company shows how they use Design Sistem in their products.

Link to Material Design
https://m2.material.io/design

Anyway, talking about Grid. To access the content that talks about Grid in Material Design, on the website dashboard, go to Design (top right menu), Layout (right menubar), Responsive layout grid.
![[responsive_layout_grid.png]]

Google uses a 4-point Grid and an 8-point Grid. 

Grid is basically how you space your content. There are 2 types of Grid:
	- **Hard grid** => consists of dividing a layout horizontally and vertically, and then placing each element on the grid, ensuring visual consistency.  It's a more rigid structure that works well in print, but can be inefficient when designing digital products.
	- **Soft grid** => is basically the distance between elements based on multiples of 8, regardless of the size of the elements. It emerged to meet demands that the Hard grid could not deal with.

The responsive layout grid is made up of 3 elements: columns, gutter, margin.
![[grid_elements.png]]

- Columns => in responsive layouts the width of the columns is defined as a percentage. The number of columns is defined by the brakpoint range. Breakpoints are nothing more than a point where the layout is changed to one with other dimensions, when the screen size exceeds that breakpoint. For cell phones, for example, the breakpoint is 360dp (dp means pixel density) and is made up of 4 columns.
![[colluns.png]]

- Gutter => it is the space between the columns, and has a fixed value for each breakpoint. The Gutter can have different sizes at each breakpoint, larger screen sizes require a Gutter with larger dimensions.
![[gutter.png]]

O tamanho dos Gutter pode ser ajustado para criar mais ou menos espaço entre as colunas.

Um espaço menor sugere que as imagens estão intimamente relacionadas entre si, dando impressão de que fazem parte de uma coleção.
![[relational entities.png]]

Um espaço maior sugere que cada imagem é um entidade individual na coleção.
![[individual entities.png]]

- Margin => the margins are the spaces on the sides of the screen. Margins are defined using fixed or scale values ​​at each breakpoint. To better adapt to each screen size, it is ideal to define different sizes at each breakpoint. For cell phones, the image size is 16dp, and for a more spacious margin, the size of 24dp can be used.
![[margins.png]]
****Note:**** use multiples of 4 and 8 to define the grid in the layout => it is good practice to use multiples of 4 and 8 not only to define the grid, but also to define the size of elements on the screen, such as text, image and etc. This practice is called [[Pixel Perfect]]

**Nudge** => Nudge is a function that allows you to move elements using the arrow keys. The Nudge has 2 values, the small nudge and the big nudge, leave the big nudge configured with the value 8 to maintain multiple proportions of 8.
It can also be used to change the size of texts, for example. Just click on the text and use the Up or Down arrows.

Follow the steps to configure Nudge:
![[nudge.png]]

	KEYBOARD SHORTCUTS:
		- Right => with the element selected, click the right arrow          button.
		- Shift+Eight => with the element selected, press Shift and          click the right arrow button

To save the grid, click on Layout grid, Create style, and define the grid name:
![[saving_grid.png]]
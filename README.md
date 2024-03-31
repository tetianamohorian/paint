# Paint
### 1.  Description

- This code creates a simple paint program using C# and the .NET Framework.
- It offers basic drawing tools like freehand drawing, lines, rectangles, ellipses, and a fill tool.
- Users can select colors using a color picker or a standard color dialog.
- Paintings can be saved as JPEG images.

### 2. Files

    - Form1.cs: This is the main file containing the code for the program's form and functionality.
    - Resources.resx: A resource file containing images or icons used in the program.
    - App.config: An optional configuration file for application settings.

### 3. How the program was programmed?

    * Key components:
        - Windows Forms: Used to create the user interface elements like buttons, picture boxes, and color pickers.
        - Graphics class: Used to draw shapes and lines on a Bitmap object, which represents the drawing canvas.
        - Mouse events: Captured to track mouse actions and draw accordingly.
        - Core steps in the program's execution:

    * Initialization:
        - Create a Bitmap object to represent the drawing canvas.
        - Create a Graphics object associated with the Bitmap to perform drawing actions.
        - Set up user interface elements and event handlers.
    * User input:
        - Handle mouse events (clicks, moves, etc.) to initiate drawing actions.
        - Capture color selections from buttons and color pickers.
    * Drawing:
        - Use Graphics methods like DrawLine, DrawEllipse, DrawRectangle, and Fill to create shapes and lines on the Bitmap object.
    * Saving:
        - Allow saving the drawn image as a JPEG file using a SaveFileDialog and the Bitmap object's Save method.

### 4. Links to source code and websites that were used in the solution

-   [.NET](https://dotnet.microsoft.com/en-us/)
-   [Microsoft Developer Network](https://learn.microsoft.com/en-us/windows-server/networking/)

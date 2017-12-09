# ConstraintLayout - Tutorial by CodeLabs 
Link: <https://codelabs.developers.google.com/codelabs/constraint-layout/#0>

## The Infer Constraints tool

The Infer Constraints tool infers, or figures out, the constraints you need to match a rough layout of elements. It works by taking into account the positions and sizes of the elements. Drag elements to the layout in the positions you want them, and use the Infer Constraints tool to automatically create the constraint connections.

## What's the difference between Inference and Autoconnect?

The **Infer Constraints tool** calculates and sets constraints for all of the elements in a layout, rather than just the selected element. It bases its calculations on inferred relationships between the elements.
The **Autoconnect tool** creates constraint connections for a selected element to the element's parent.

As soon as you constrain one dimension to be `match_constraint`, the `Toggle Aspect Ratio Constraint` option appears in the inspector view in the top left corner of the square.

Click the `Toggle Aspect Ratio Constraint` option. The ratio entry box appears below the bottom right corner of the square:
By using ratios you can ensure your designs stay perfect while allowing images to be resized on different device screens.

`Barriers` allow you to specify a constraint based on multiple UI elements. You'll want to use barriers any time that multiple elements could dynamically change their size based on user input or language.

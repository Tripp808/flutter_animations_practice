# flutter_animation_practice
This is a simple Flutter application demonstrating basic animations. The app contains a container that smoothly transitions its size and color when a button is pressed.

Features
Size Animation: The container's size transitions between 50x50 and 200x200.
Color Animation: The container's color transitions between blue and red.

## Code Explanation
## Animation Setup

### An AnimationController is used to manage the animation's timing.

### Tween<double> is used for the size transition.

### ColorTween is used for the color transition.

## Key Components
### AnimationController: Manages the animation's duration and state.

### Tween: Defines the start and end values for the animation.
### CurvedAnimation: Applies an easing curve to the animation.
### AnimatedBuilder: Rebuilds the widget tree whenever the animation value changes.

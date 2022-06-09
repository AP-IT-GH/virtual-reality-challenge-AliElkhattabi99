# virtual-reality-challenge-AliElkhattabi99
virtual-reality-challenge-AliElkhattabi99 created by GitHub Classroom

### 1.  The Canvas that allows you to change the shape on the pedestal follows the camera.
        - change canvas_pedestal to world space mode.
### 2.  The toggled ray and palette canvas are tracking the opposite hands.
        - change input refrences left hand to left hand refrences
### 3.  The paint brush activation is backwards, starting when the trigger is released and stopping when it’s pressed. 
        - change the paintbrush events on activate to CreateTrail.StartTrail and on deactivate to CreateTrail.EndTrail
### 4.  The medium brush size button turns invisible when pressed and makes the trail gigantic.
        - change XR Rig -> lefthand -> canvas_pallette -> button_size  pressed color to the same color as the others and change trail width to 0.03
### 5.  The paint brush sound effect stays the same, regardless of how far it is from you.
        - change min audio distance to 0.1 and max to 1

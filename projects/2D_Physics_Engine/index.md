---
layout: project
project_title: "Cleaning (turtle)bot"
project_caption: "One-liner description | Date-Year"

project_content:
    - 
        type: image
        title: A caption for the above image.
        body: /assets/images/thumbs/grid_clean.gif" alt="https://www.w3schools.com/bootstrap4/paris.jpg
    
    -
        type: paragraph
        title: "Overview"
        body: "To simulate and animate fundamental movements behind a house cleaning robot using ROS.
        <br>
        <br>

        The configuration variables are:<br>
        q = [x_box, y_box, θ_box, x_jack, y_jack, θ_jack]
        <br>
        At the start, the turtlebot rests at a coordinate (5,5).<br>
        "
    -
        type: image
        title: A caption for the above image.
        body: /assets/images/thumbs/move_fwd.gif" alt="https://www.w3schools.com/bootstrap4/paris.jpg
    
    -
        type: paragraph
        title: "Description"
        body: "
        <br>
        <i><strong>Rigid Body transformations</strong></i><br>
        
        <br>
        <br>

        <i><b>Forces and Constraints</b></i><br>
        <br>
        An external force of 700*sin(pi*t) is applied on the box in the x direction. A sinusoidal type of force provides a back and forth shaking motion. 700 is the amplitude and pi*t is the period; frequency=2pi/period.<br>
        And another external force of magnitude of the gravitational force acting on the box (Total mass of box*gravity*height of the box from its center of mass with respect to the world frame) is applied in the opposite direction of that gravitational force to prevent the Box from falling down and going outside the scene.<br>

        <br>

        "
    -
        type: image
        body: /assets/images/thumbs/jack2.png" alt="https://www.w3schools.com/bootstrap4/paris.jpg
        

    -
        type: image
        body: /assets/images/thumbs/jack3.png" alt="https://www.w3schools.com/bootstrap4/paris.jpg

    -
        type: image
        body: /assets/images/thumbs/jack4.png" alt="https://www.w3schools.com/bootstrap4/paris.jpg
        
    -
        type: image
        body: /assets/images/thumbs/jack5.png" alt="https://www.w3schools.com/bootstrap4/paris.jpg
        
    -
        type: paragraph
        body: "
        <i><b>Observation</b></i>
        <br>
        The box is shaking as expected which slowly starts to die down until the impact from the jack adds a torque to the box. The box’s height is maintained to an extent and not changing much with respect to its center of mass to the world frame and it does not fall out of the scene.<br>
        The jack due to the force of gravity acting on it always tries to fall down while staying inside the box.<br>
        The impact of the jack on the walls of the box causes the jack itself to rotate as well as bounce from one wall to another.<br>
        "
---


# Demo
![screenshot](http://s3.imathis.com/dev/compass/fancy-buttons/demo.png)

Without CSS gradient support:  
![screenshot](http://s3.imathis.com/dev/compass/fancy-buttons/demo-no-gradients.png)


## Install

Install the plugin:

    sudo gem install fancy-buttons

If you don't have compass colors 0.3.1
    
    sudo gem install compass-colors

To create a new project based on fancy-buttons:

    compass -r compass-colors -r fancy-buttons -f fancy-buttons your_project_name

To add fancy-buttons to an existing compass project:

    # Add the following lines to your compass configuration file:
    require 'compass-colors'
    require 'fancy-buttons'
    
    # Then run the following command:
    compass -i -f fancy-buttons

# Project Goals:

- Generate a color palette from the base color
- Discern sensible palette variations based on a base color (dark, medium, light)
- Allow button style types (subtle gradient, shiny gradient)
- Make it easy to override/modify styles
- Reduce weight of generated styles (define button base, add color through additional classes)
- Create good defaults
- Ensure approximate consistency for browsers that don't support CSS gradients
- Style the button element
- Provide a decent alternative styling for ie6
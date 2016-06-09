# PanFrame rotate PFView

On line 256 of SimpleStreamPlayerActivity, you can find the method for the click on “orientation” button. And on line 291, you’ll find the method “onConfigurationChanged” where I manually rotate the screen with the PFView.setViewRotation method. From this point, when you move your device, the image is skewed.

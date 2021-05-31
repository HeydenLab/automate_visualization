#### Automate molecular visualization using selenium and speck.

A script to obtain molecular vizualizations for publications from .xyz file format, like the following, 



<p align="center">
  <img src="https://user-images.githubusercontent.com/15354922/120192334-0d52c100-c1e9-11eb-9260-d524b08162b7.png" width="400" height="400">
</p>



The advantage is, if we have a lot of intermediates and transition states in our reaction systems, we can easily supply them as a list
and rotate or zoom in or out the rendering canvas of speck according to our specifications, and save the visualizations without having to do the manual task. 
The script uses selenium for automation and speck for molecular visualization. To use selenium, please download the chromedriver from [here](https://chromedriver.chromium.org/downloads) and provide the path to the driver in the script variable *path_to_driver*. Please modify the script according 
to your preferred visualization options.

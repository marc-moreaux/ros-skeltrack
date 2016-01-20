# ros-skeltrack
ROS Wrapper for Skeltrack

#Installation

1. Install the Skeltrack library. If using Ubuntu 14.04:
    ```bash
    install libgirepository1.0-dev gobject-introspection gtk-doc-tools
    ./autogen.sh --enable-tests=no
    sudo make install
    ```
    
2. Clone this repo into your workspace :
    `git clone git@github.com:marc-moreaux/ros-skeltrack.git`
   
3. Ruild it : 
    `catkin_make`

4. Run the node ;)

# Neural Network Line Follower

Please visit our [**final website**](https://project-memory.github.io) for more information.

This project contains all of the code for the [final project](https://sites.google.com/site/comprobo17/projects/final-project) for Computational Robotics, spring 2017.

## Team Members
- [Lauren Gulland](https://github.com/laurengulland)
- [Nathan Yee](https://github.com/nathanyee)
- [Eric Miller](https://github.com/halthewise)

## Running the code

1. Clone this repository into your `catkin_ws/src` folder
2. Run `rosdep install --ignore-src --from-paths $(rospack find line_follower)/..`
3. In your root `catkin_ws` folder, run `catkin_make`
4. Use the package
  - Training data collection: `roslaunch line_follower training_controller.launch base_name:=PUTSOMETHINGHERE`

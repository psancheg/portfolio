# Software engineer

## Education
- Master's degree computer graphics, games and virtual reality, University Rey Juan Carlos (2018)
- Computer Science degree, University Carlos III de Madrid (2016)
## Work Experience 
### Research engineer at SEDDI (02-2018, 05-2024)
Focused on the research and implementation of several systems to obtain and process parametric avatars from different types of inputs.

- Avatar from video: development of a pipeline to obtain an SMPL parametric avatar that fits a target point cloud obtained from a video by using: structure from motion, 3D post-processing and non-linear optimization of the avatar’s pose and shape parameters.
- Avatar from measurements: development of a system to obtain an SMPL parametric avatar with a 3D body that matches a set of target measurement values.
- Implementation of the required tools to aid with the development, testing, analysis and research of the avatars’ technology.

Used Python, PyTorch, Blender, Git, Pandas, COLMAP, Tkinter, Polyscope.

## Proyects
### Small game engine (In progress)

Small implementation of a game engine in my free time. 
https://gitlab.com/pablosherrerog/thule_engine

There are some topics that I'm interested to learn, so the idea of this project is to have something to apply the things that I learn. 
- I wanted to understand better C++ and the overall architecture of a Game Engine, including automatizing the build and testing steps (CI/CD).
    - To learn more about the general structure of Game Engines I'm reading the book [Game Engine Architecture](https://www.gameenginebook.com/) (Jason Gregory).
    - I'm using also the channel (The Cherno)[https://www.youtube.com/@TheCherno].
- I was interested in learning more about the ECS approach so I used [Austin Morlan introduction to ECS] (https://austinmorlan.com/posts/entity_component_system/#demo).
- I would like in the future to learn more about Vulkan or DirectX but for now I'm using OpenGL since is more approachable
  - Using https://learnopengl.com/ as the main resource.

### Master thesis (2018). Parametric avatar reconstruction using point clouds
Used linear blend skinning and principal component analysis to create a custom parametric avatar with pose and body shape parameters. Used non-linear optimization with the avatar’s parameters to deform the avatar’s mesh to fit a target point cloud.

Used: C++, OpenGL, Blender, Ceres, COLMAP.

### Bachelor thesis (2016) Computer visión integrated with virtual reality devices applied to video games. 

Used an Oculus headset (DK1) and computer vision using a Kinect camera (V1) to create a VR experience. I learned about virtual reality devices, positional tracking systems, computer vision, and Unity

[LightSaber game with Unity, Kinect, OpenNI2, OpenCV, Oculus Rift DK1 and a pool noodle](https://www.youtube.com/watch?v=pCz_zCBTLQw)

Used C++, Unity, Kinect, Blender and OpenCV.

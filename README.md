# ARCore Experiments

### Test Data:

```
./test_data:
|-- camerapose
|   |-- input<i>_cam.ply (ARCore camera coordinates: Camera.getPose())
|-- compressed_videos
|   |-- input<i>.mp4     (compressed input videos)
|-- pointcloud
|   |-- input<i>_pc.ply  (ARCore estimated point clouds: PointCloud.getPoints())
|-- projectionmatrix
|   |-- input<i>_projection.matrix   (ARCore camera projection matrix: Camera.getProjectionMatrix())
`-- viewmatrix
    |-- input<i>_view.matrix    (ARCore camera view matrix: Camera.getViewMatrix())
```

Download high resolution test videos from here: https://drive.google.com/open?id=1hqFePacDPE0gt4O1-4DEaVtFKdaC9qNW

### Point Cloud estimation:

- Scene 1:

| Camera | PointCloud |
|:-------------------------:|:-------------------------:|
| <img width="400" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene1_2.jpg?raw=true"> | <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene1.gif?raw=true">  <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene1_pointcloud_1.png?raw=true"> | |

- Scene 2:

| Camera | PointCloud |
|:-------------------------:|:-------------------------:|
| <img width="400" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene2.jpg?raw=true"> | <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene2.gif?raw=true">  <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene2_pointcloud_1.png?raw=true">  <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene2_pointcloud_2.png?raw=true"> |

Points in red are the positions of the phone (camera).

- Scene 3:

| Camera | PointCloud |
|:-------------------------:|:-------------------------:|
| <img width="400" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene3.jpg?raw=true"> |  <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene3_pointcloud_1.png?raw=true">  <img width="500" alt=" " src="https://github.com/vikasTmz/ARCore_Experiments/blob/master/images/scene3_pointcloud_2.png?raw=true"> |

Points in red are the positions of the phone (camera).

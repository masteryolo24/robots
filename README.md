# ROBOT ASSIGNMENT 2

### First Time Setup:
```
pip install -r requirement.txt
```

### Run:
- Generate Top-view picture:
```
python generate_topview.py + (scene_number)
```
- Main:
```
(sudo) python ai2thor.py + (scene_number)
```

## Challenge-01: Object detection and Classification on First View Cameras.
Link Download pre-traned :https://bitly.vn/3h60 (due to the BigFile)<br>
Once you have the Robot file, run<br>
```
sudo python AI2THOR.py
```
When the First view of Robot show Up, Use W, S, A, D for Move up, down, left, right. Use Key arrow to rotate the camera of robot<br>
If you want to change Sceen, press 'q'<br>
Detect Object By YOLO: 'F' key<br>
Detect Object By ai2thor metadata: 'P' key<br>

## Challenge-02: Drawing Trajectories on Top-view Map of the room.
#### Overview: 
- Capture Top-View Image
- Display Location of Robot in map on Top-View Image
- Update Real-time new Location of Robot each step and distinguish by RGB color<br>
#### Controller:
- Move: Arrow Keys
- Change Views Rotation: W-A-S-D
#### Note:
Take a rest between key press to ensure the stability of application



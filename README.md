# Velocity-Estimation-and-Lane-Detection
This is a group project about computer vision. Using python to develop a programme estimate vehicle velocity and detect high-way driving lane.

## Group

| Name         | Email                   | Responsibility                 |
| ------------ | ----------------------- | ------------------------------ |
| Haonan Zhang | z5151812@ad.unsw.edu.au | Driving Lane Detection, Report |
| Hanrui Tao   | z5237012@ad.unsw.edu.au | Driving Lane Detection, Report |
| Fei Xu       | z5239235@ad.unsw.edu.au | Velocity Estimation, Report    |
| Yiyang Ke    | z5244460@ad.unsw.edu.au | Velocity Estimation, Report    |
| Dannie Zhao  | z5266355@ad.unsw.edu.au | Report                         |

## Preview
- Velocity Estimation

- Driving Lane Detection


## Dataset
- [Dataset for Velocity Estimation](https://github.com/TuSimple/tusimple-benchmark) (click here to access datasets)
- [Dataset for Driving Lane Detection](https://github.com/TuSimple/tusimple-benchmark/tree/master/doc/lane_detection) (click here to access datasets)


## Method Structure
### Velocity Estimation
- Estimate relative distance of other vehicles
- Estimate relative velocity of other vehicles

### Driving Lane Detection
- Preprocessing of Dataset
    - Region of interest (ROI)
    - Gaussian smoothing
    - Color Space Selection (combine RGB and HSV color spaces)
- Detection 
    - Canny Edge Detector
    - Hough Transform
- Optimization
    - Average of slope and intercept

## How to Use
1. Clone/Download the repo [https://github.com/conanzahn/Vehicle-Detection-Computer-Vision-.git]
2. Download Datasets to your local machine 
- Velocity Estimation[https://github.com/TuSimple/tusimple-benchmark]
- Driving Lane Detection[https://github.com/TuSimple/tusimple-benchmark/tree/master/doc/lane_detection]
3. Run Jupyter notebook/ Python file.

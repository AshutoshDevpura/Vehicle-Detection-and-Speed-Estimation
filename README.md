# Vehicle-Detection-and-Speed-Estimation

## About The Project
Major Project for SRM Institute of Science and Technology.

This repositary contains a tool to detect Speed of the Vehicle and Vehicle Direction using Object and Centroid tracker based on Computer Vision along with finding the Vehicle count and color using TensorFlow Object Detection API.

### Clone 

```
git clone https://github.com/AshutoshDevpura/Vehicle-Detection-and-Speed-Estimation
```

### Prerequisites 
1. ![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)

2. ![pip3](https://img.shields.io/badge/pip-v21.0+-blue.svg)

### Architecture diagram

![Fig 1](https://user-images.githubusercontent.com/46817661/132096238-2f2e71db-4d22-4411-9743-fad49910f95c.png)

### Object Detection Algorithm

Single Shot Multi-Box Detector has remarkable performance and precisionfor  object  detection  tasks,  scoring  an  average  74  %  mean  Average  Precision(mAP) at 59 frames per second on the standard COCO dataset.

![MobileNet SSD](https://user-images.githubusercontent.com/46817661/132956189-53a61b91-909f-45e5-9829-9f74d57b135b.png)





### Installation

1. cd Vehicle-Detection-and-Speed-Estimation.
2. Install virtual environment. 
  ``` 
  pip3 install virtualenv
  ```
3.  Create the virtual environment.
  ```
   virtualenv env_name
  ```
4. Download all requirements from requirements.txt.
  ```
  pip3 install -r requirements.txt
  ```
5. Run the program
  ```
  python3 vehicle_detection_main.py 
  ```
  ```
 python3 speed_estimation_dl.py
  ```
    
### Output 


![output](https://user-images.githubusercontent.com/46817661/127166371-406d9414-84c0-4dc7-af16-09d65c5133bf.png)

```
$ python speed_estimation_dl.py --conf config/config.json
[INFO] loading model...
[INFO] warming  up camera...
[INFO] Speed of the vehicle that just passed is: 26.08 MPH
[INFO] Speed of the vehicle that just passed is: 22.26 MPH
[INFO] Speed of the vehicle that just passed is: 17.91 MPH
[INFO] Speed of the vehicle that just passed is: 15.73 MPH
[INFO] Speed of the vehicle that just passed is: 41.39 MPH
[INFO] Speed of the vehicle that just passed is: 35.79 MPH
[INFO] Speed of the vehicle that just passed is: 24.10 MPH
[INFO] Speed of the vehicle that just passed is: 20.46 MPH
[INFO] Speed of the vehicle that just passed is: 16.02 MPH

```



## Conference Paper
https://link.springer.com/chapter/10.1007/978-981-16-7167-8_6

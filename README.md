# ROS_tutorial

## 1. 개발환경 확인
```python3 -V```  
python 3.8.10

``` lsb_release -a ```

  No LSB modules are available.  
  Distributor ID:	Ubuntu  
  Description:	Ubuntu 20.04.6 LTS  
  Release:	20.04  
  Codename:	focal

## 2. sources.list 설정
```sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'```

## 3. 키 설정 
```curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -```  

## 4. 패키지 업데이트
```sudo apt-get update```

## 5. ROS noetic 버전 설치 
```sudo apt install ros-noetic-desktop-full```

## 6. 환경설정
```source /opt/ros/noetic/setup.bash```

## 7. python 패키지 설치
```sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential```

## 8. rosdep 초기화
```sudo rosdep init```  
## 9. rosdep 업데이트
```rosdep update```  
## 10. 

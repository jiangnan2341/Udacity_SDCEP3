# Scan Matching Localization
The purpose of this project is to implement, use and compare two localisation algorithms (ICP and NDT) in case of a car equipped with a lidar. The target of the application is to keep the max pose error below 1.2m for 170 travelled meters. For testing our algorithms, we use CARLA Simulator to provide lidar scan at regular intervals.

### Installation

This project uses Udacity workspace of the project "Scan Matching Localization" of the Lesson 3 "Localization" of the Self-Driving Car Engineer Nanodegree program.

### Usage

Firstly, to use ScanMatchingLocalisation, Carla simulator needs to be running in the background. To do it, running the following commands:

```
su - student # Ignore Permission Denied, if you see student@ you are good
cd /home/workspace/c3-project
./run_carla.sh
```

Meanwhile, Carla Simulator is running in a dedicated prompt, compile and run ScanMatchingLocalization application using the following commands:

```
cd /home/workspace/c3-project
cmake .
make
./cloud_loc
```

### Results

I know my code works because I did do some tests. Unfortunately, my workspace starts to have some issue before I got the chance to take screenshots of my results. I tried refresh workspace and even reset data. The problem persists even after reset data and before I introduced any updates. See screenshot below to get the problem detail:

![](workspaceIssue.png)

I only updated the c3-main.cpp file. Hope the reviewer can take my code and run on their side to get proof of my work. Sorry for the trouble. At the same time, I will try to contact support to get the workspace problem fixed.

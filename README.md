# RobotController_bin
This is a binary of [RobotController](https://github.com/social-robotics-lab/RobotController).

# Install
Run the following commands in Sota.
```
git clone https://github.com/social-robotics-lab/RobotController_bin.git
cd RobotController_bin
mkdir RobotController_lib
cd RobotController_lib
git clone https://github.com/vstoneofficial/SotaSample.git
cp SotaSample/lib/* .
rm -rf SotaSample/
wget https://repo1.maven.org/maven2/com/google/code/gson/gson/2.8.5/gson-2.8.5.jar
wget https://repo1.maven.org/maven2/org/json/json/20180813/json-20180813.jar
```

# Run
```
cd RobotController_bin
java -jar RobotController.jar
```

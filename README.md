# RobotController_bin
RobotControllerの実行ファイル


# Install
Sotaの中で以下を実行。
```
git clone https://github.com/social-robotics-lab/RobotController_bin.git
cd RobotController_bin
mkdir RobotController_lib
cd RobotController_lib
git clone https://github.com/vstoneofficial/SotaSample.git
cp SotaSample/lib/* .
rm -rf SotaSample/
wget https://repo1.maven.org/maven2/org/apache/activemq/activemq-all/5.15.8/activemq-all-5.15.8.jar
wget https://repo1.maven.org/maven2/com/google/code/gson/gson/2.8.5/gson-2.8.5.jar
wget https://repo1.maven.org/maven2/org/json/json/20180813/json-20180813.jar
```


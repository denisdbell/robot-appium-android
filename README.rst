RobotFrameWork Appium Library
=========

This tutorial demonstrates how to execute functional tests on an android device using robot framework and appium.

Prerequisites
=========

Ensure that the following are installed before proceeding:

  - Robotframework + ride (using easy install or pip)
 
 '''sh
pip install robotframework-ride
easy_install robotframework-ride
'''
  -  appium library for robotframework
'''sh
   pip install robotframework-appiumlibrary  
'''

  - appium
  
'''sh
 brew install node     
npm install -g appium  
npm install wd         
'''

 -Download Android SDK and add it to the system PATH
   
'''sh
  export ANDROID_HOME=$HOME/Downloads/android-sdk-macosx
export ANDROID_SDK=$ANDROID_HOME
PATH=$PATH:$ANDROID_HOME/build-tools
PATH=$PATH:$ANDROID_HOME/platform-tools
PATH=$PATH:$ANDROID_HOME/tools   
'''
----------------

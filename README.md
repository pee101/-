# ionic cordova plugin add cordova-plugin-facebook4 --variable APP_ID="YOUR_APP_ID" --variable APP_NAME="YOUR_APP_NAME"
 APP_ID="1107112762801303"  ได้จาก ID ของแอพ
 NAME="login - Test1"  ได้จาก ชื่อแอพในdevelopers.facebook.com ที่สร้าง


เข้าไปไฟล์package.json:  แก้ 
 "cordova-plugin-facebook4": {
                "APP_ID": "1107112762801303",
                "APP_NAME": "login - Test1"

com.ionic.facebook ได้มาจากการตั้งชื่อแพ็คเกจบน Google Play

แก้ในไฟล์ config.xml เอาชื่อ com.ionic.facebook ใสแทน com.axelhardy.fbtutorial
<widget id="com.axelhardy.fbtutorial" version="0.0.1" xmlns="http://www.w3.org/ns/widgets" xmlns:cdv="http://cordova.apache.org/ns/1.0">

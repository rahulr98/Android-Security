## Android Security Lecture-1

  -  First, we have to create a project in Android Security

![image](https://github.com/rahulr98/Android-Security/assets/116432525/186fe825-93f1-47ec-a0bb-77483af27263)

  -  Then, we have to set up a new Android device for further purposes.
  -  We can select any model from the list, Here I'm selecting the **Pixel 2** device.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/e71bd344-478f-4477-92fc-48803fecd034)

  - Now, we have to modify the 'activity_main.xml'.
  - Insert a new line for ID.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/3681b17e-a38d-4cf3-88a6-0db0cbb95480)

  -  To view the text in the 'MainActivity.java', we need to include a 'TextView' section.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/39c7d205-e2a0-4f3a-ba7f-5d03ddf2c364)

  -  To add a new 'Button', we need to customize the 'activity_main.xml' file.
  -  These actions will be shown in the Virtual device.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/6d49ff1c-e5a9-48f8-aaa0-fcce8b67e2dd)

![image](https://github.com/rahulr98/Android-Security/assets/116432525/51198612-e54f-4893-85de-a418e2ef2114)

  -  Now, we installed a Vulnerable App in the emulator.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/52c78356-ee01-4444-a29f-a3bda71506f7)

  -  Using adb command, we went inside the shell.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/f8b1f4e7-be53-4ef3-b5aa-d729d22fa8cd)

  -  Now we list the packages by adding a filter 'example'.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/9a87fd51-fc3a-4357-9eb1-3753bce3a678)

  -  Now open the database folder.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/27d8e85c-c56d-4cbc-af73-a97987d2642d)

  -  Forward data from the emulator to the PC using adb command.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/06da806c-5657-449e-9af6-f178056a7258)

  -  Now we search for SQLite Database where the tables are present.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/09e897ab-0d4a-497f-b517-329d11a1fb39)

  -  When we use the implicit function,

![image](https://github.com/rahulr98/Android-Security/assets/116432525/2c043978-69ac-44e7-bc2c-fe637ec579e7)

  -  The output will be,

![image](https://github.com/rahulr98/Android-Security/assets/116432525/387442fb-1609-4b83-b2e3-a811a1536bcc)

  -  Now we try explicit function,

![image](https://github.com/rahulr98/Android-Security/assets/116432525/695c34c7-068c-4474-8c31-6380c5fef84d)

  -  We get the output website in the app itself.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/99fb21e5-005e-4b14-b559-645cefc5915d)

  -  The UID of the user-installed app is checked and we list the number of users.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/469c4be6-05ca-4720-9479-c23552853bd7)
![image](https://github.com/rahulr98/Android-Security/assets/116432525/202f699d-03da-4b5f-893f-78065ed4b274)

  -  Then we checked the package Youtube in the guest user package.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/6dc1e93f-0eac-4516-8dc7-24e18ba9859c)

  -  Now we look into the shared preferences option.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/aed4751b-715a-492a-9b62-199ce2cf8937)

  -  We checked the shared preferences through the command line,

![image](https://github.com/rahulr98/Android-Security/assets/116432525/7ba1fdf3-9009-4e96-ba5f-15c427ff311c)

  -  Now debug the application App-debug using Apktool.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/5662bb4c-b55b-4d0d-8bc9-8aa269e3c0e3)

  -  Install DIVA App

![image](https://github.com/rahulr98/Android-Security/assets/116432525/694fc7b2-9c01-4eeb-a681-857cddeec25b)

  -  Now we go to the insecure Logging and enter any random credit number.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/644091f9-67bb-41c1-9ae8-02dce1a692de)

  -  It will be reflected in the logcat.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/5eece387-6e67-46cf-b58e-46a038fe49dd)

  -  Now coming into hardcoding issues, decompile the code to get the vendor key

![image](https://github.com/rahulr98/Android-Security/assets/116432525/dde5569c-48cd-4fb2-903b-3622077be7a3)

  -  Now we enter the vendor key in the Hardcording issues interface to get Access

![image](https://github.com/rahulr98/Android-Security/assets/116432525/39c4b6ae-70f7-413b-a0ee-5280d5cacd5f)
![image](https://github.com/rahulr98/Android-Security/assets/116432525/a81a6ec7-d33e-4878-9c4f-429701358e20)

  -  Now coming into ' Insecure Data Storage - Part 1', we enter 3rd party username and
password there.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/50e839f2-f821-404c-b975-1386ab0bd973)

  -  The 3rd party entered the username and the password was saved directly in this folder.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/8eb03e31-7c20-4aa0-a25b-f05cf0bd32e3)

  -  Now coming into ' Insecure Data Storage - Part 2', we enter 3rd party username and
password there.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/d4b6f813-7e39-4a41-a504-28e5fac27f30)

  -  The entered 3rd party credentials are saved in a database in tables.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/c4d293f1-64b5-4def-ba76-98cdf8d10a68)

  -  Now coming into ' Insecure Data Storage - Part 3', we enter 3rd party username and
password there.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/0d94f068-69c6-4de0-add7-407bc482dc16)

  -  The credentials got saved as a separate file in the application saves.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/1592f003-b3d5-4ef0-86c3-7c8feac261fd)

  -  Now coming to ' Input Validation issues - Part 1', we give a string ' 1' or 1=1 -'

![image](https://github.com/rahulr98/Android-Security/assets/116432525/b2da0dbb-a956-42de-b3b4-d535e44020f8)

  -  which results in all the usernames and passwords present and it got saved in SQLITE databases.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/9be2ca7b-c89e-4a65-ba80-3365b5524ee7)
![image](https://github.com/rahulr98/Android-Security/assets/116432525/e014f468-9eaf-4549-9cdc-18c1129739ea)

  -  Now coming into ' Input Validation issues - Part 2', we give the filename where the
username and password are being saved.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/63fcabaa-1c47-45c2-9189-2052e7c4a83c)

  -  Next in Access Control Issues - Part 1' without interacting with the application we can
get access to API credentials.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/cfba59d4-0695-4173-b22a-7fe39e5ac7ee)

  -  In ' Access Control Issues - Part 2' we getting the API credentials we will get access to
the page through 'am' command.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/790f85e4-b5d0-4455-acdc-e1e0c533e9f6)
![image](https://github.com/rahulr98/Android-Security/assets/116432525/1d20e0ba-8ef3-4a4d-9abd-ed45a096772f)

  -  We get access to the notes saved in the SQLite databases without any pin(as root).

![image](https://github.com/rahulr98/Android-Security/assets/116432525/d6466adb-91ab-49d1-ac08-1f802aee15e9)

  -  We, as normal users, can also get access to these notes through content queries.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/ee632868-de8b-4b3b-b713-5067bd8d711a)

  -  Now we go into the lib folder which is present where we extracted the application using apktool.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/93281ab4-a782-4670-94fc-a48f68f8c521)

  -  We enter the retrieved word into the 'Hardcord Issue - Part 3 and access is granted


![image](https://github.com/rahulr98/Android-Security/assets/116432525/9b4517d0-302c-4bab-8287-a92d285dfcb6)

  -  When coming to ' Input Validation Issues - Part 3 ' we go through the application which asks for the launch code.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/bd63639f-0930-4687-885c-5012538f2da4)

  -  When we enter some random string of longer lengths, the application crashes due to stack overflow.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/38f6e115-768c-469d-813d-6b5f0232423f)

  -  The result for grep diva gives,

![image](https://github.com/rahulr98/Android-Security/assets/116432525/6fe09651-b86c-4e48-b857-5e094e099465)

  -  Now use apksigner to verify the signature of the application.

![image](https://github.com/rahulr98/Android-Security/assets/116432525/23c52fae-8b9c-4b00-a51e-650b5b2cc7a0)

  -  Now we use keytool to generate keystore

![image](https://github.com/rahulr98/Android-Security/assets/116432525/b8bf1200-3f3e-4ff5-99c3-2dd2b0cdbbdb)

  -  

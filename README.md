# Video Call-Implementation-Using-Sinch-SDK
Video Calling implementation Using Sinch SDK


1. You Have to Register your App on Sinch
Go to Snich Website https://www.sinch.com/

2.Click on GET STARTED button to move ahead

3.Quickly fill in details and register 

4.you need to verify your phone number

5.Once the verification is done, you shall see a welcome page.

6.After that, Click Get Started Button

7.Give Your App name And description

8.Fill The required details as asked and click create button. and select Video Calling then choose android.

![snich](https://cloud.githubusercontent.com/assets/15822647/25472623/b3656a42-2b49-11e7-8f15-b09517d2afd0.png)

9.In the above screen you can see the three unique keys have been assigned to your app.
Copy them somewhere as you’re gonna need these in this app.

10.Click the Download Android SDK button and wait for it to be downloaded.

<h2>Android Part</h2>

1.Create a new Project on Android Studio

<strong>Importing Sinch SDK to Your Project</strong>



2.Unzip the downloaded file and go to the following directory-:

3.sinch-android-rtc-3.8.0-VIDEO-20151119.112353-6\sinch-android-rtc-3.8.0-VIDEO-SNAPSHOT\libs

4.You shall see something like below

![import](https://cloud.githubusercontent.com/assets/15822647/25472874/cfd843ec-2b4a-11e7-91ea-864a59772c4b.png)

5.Now copy the jar file from the above directory.

6.Go to this  directory  YourAppName/app/libs  in your project and paste the jar file in the libs folder.

7.RightClick on the jar file and click on Add as Library and wait for the Gradle to be synced.

8.Now, go to the folder from where you copied the jar file and this time copy the two folders by the name armeabia-v7a and x86.

9.Next, in the following directory YourAppName/app/src/main of your project, create a new directory  by the name jniLibs in the main folder.

10.Paste the two folders that your previously copied in the jniLibs folder

<h3>Testing</h3>

When Your app is ready to be tested.

Just login with  unique usernames on two mobile phones. and in  the recipients name, enter one of the usernames, hit the call button and you shall see the other phone ringing.

![screenshot_20170427-131832](https://cloud.githubusercontent.com/assets/15822647/25473231/435ee69e-2b4c-11e7-9eb6-28df93938a28.png)

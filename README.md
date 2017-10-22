# Weather-Cloud-API
How to deploy Spring boot application in Google cloud 

How to deploy application to Google cloud

1.First of all add app engine plugin into maven 
 
2. Open the Cloud Platform Console.
https://console.cloud.google.com/home/dashboard
In the drop-down menu at the top, select create a project.
Give your project a name.
Make a note of the project ID, which might be different from the project name. The project ID is used in commands and in configurations.
Enable billing for your project.
3. Install the Google Cloud SDK.
 
If you haven't already installed the Google Cloud SDK, install and initialize the Google Cloud SDK now. The SDK contains tools and libraries that enable you to create and manage resources on Google Cloud Platform.
4. Configure the app.yaml descriptor
The app.yaml descriptor is used to describe URL dispatch and resource requirements. This example sets manual_scaling to 1 to minimize possible costs. These settings should be revisited for production use.
  
5. Then set your project id in app engine as below
Run from cloud sdk installed directory C:\Users\bahota\AppData\Local\Google\Cloud SDK
 
6. Check whether your application set properly or not with below command
 
7. Run mvn spring-boot:run
Visit http://localhost:8080      Deploy to App Engine flexible environment
8. mvn appengine:deploy
Visit http://YOUR_PROJECT.appspot.com.
Then after run this it will display your Application URL in console just hit that it will work.
Referral Video: https://www.youtube.com/watch?v=PN4NLSpAJWc&feature=youtu.be

Thank you
Basant Hota


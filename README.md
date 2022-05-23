# Http using Volley 

Volley is an HTTP library that makes networking for Android apps easier and most importantly, faster.

Below is the dependency for Volley which we will be using to get the data from API. 
For adding this dependency navigate to the app > Gradle Scripts > build.gradle(app) and add the below dependency in the dependencies section.  


 
 
 
 
                       implementation 'com.android.volley:volley:1.2.1'






Adding permissions to the internet in the AndroidManifest.xml file
Navigate to the app > AndroidManifest.xml and add the below code to it.  








                       
                        <!--permissions for INTERNET-->
                        <uses-permission android:name="android.permission.INTERNET"/>
                        
                        
                        
                        



if getting error like this : Cleartext HTTP traffic not permitted
add this line in AndroidManifest.xml
                        
                        
                        
                        
                        <application
                        ....
                        android:usesCleartextTraffic="true"
                        ....
                        </application>
                        
                        
                        
                        
                        
                        
                        
![Screenshot 2022-05-23 122325](https://user-images.githubusercontent.com/101108540/169769516-8bf335a7-af67-4309-bd83-96c098c5a613.jpg)
             
                        
![Screenshot 2022-05-23 130428](https://user-images.githubusercontent.com/101108540/169769529-2252c3f4-b929-4a54-9827-e0e122262dea.jpg)
            
                        

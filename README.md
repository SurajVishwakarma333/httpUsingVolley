# Http using Volley

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
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        
                        

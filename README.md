# VuforiaSamples-6-2-10_AndroidStudio
1. Download the Vuforia SDK for android. Extract it in your projects directory.
2. Download this project and extract it in "samples" directory of vuforia sdk extracted in point 1.
3.Obtain your Vuforia license key at https://developer.vuforia.com/targetmanager/licenseManager/licenseListing
4.Paste the key in "SampleApplicationSession.java" file which is located in your project under
app/src/main/java/com.qualcomm.vuforia.samples/SampleApplication/SampleApplicationSession in line 347
paste it between the "" as the third parametar: 
Vuforia.setInitParameters(mActivity, mVuforiaFlags, "");
5. Open the project in Android Studio
6. Click Build ->Clean Project
7. Click Build ->Rebuild Project
8. Click Run -> Run 

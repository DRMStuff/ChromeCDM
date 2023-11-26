1. Extract the zip file
2. Go to the extracted folder
3. You will see a license.json file, open it in any text editor.
4. Go to line 2 and change the "api_key" field's value with an API key you generate for your hosted API code/server. Change the "api_url" field with your hosted API's url's /extension endpoint. Make sure to save the file after editing!

You can use the extension only on windows. You can use the extension in chrome/brave/vivaldi browsers.

Method of adding the extension in chrome browser:-
• Go to chrome > three dots at the top right corner > more tools > extensions
											OR
• Go to chrome > three dots at the top right corner > Extensions > Manage extensions

• Make sure to turn on the developer mode at the top right corner. 
• Click "Load unpacked"
• Select the extracted folder. (Make sure to double click and go inside to the extracted folder and then press "Select Folder")

Method of adding the extension in brave browser:-
• Go to brave > three lines at the top right corner > extensions
• Make sure to turn on the developer mode at the top right corner.
• Click "Load unpacked"
• Select the extracted folder. (Make sure to double click and go inside to the extracted folder and then press "Select Folder")

5. Pin the extension.

Important :- Please disable any eme logger extension/scripts and any pssh capture extensions/scripts if you have added before.

6. Go to your DRM video an play it. (You may need to accept the install widevine popup when first playing a DRM video on brave browser and then reload the page again!)

7. If you get an error as "Incorrect Padding", please follow the guide mentioned here:- https://t.me/chromecdm/94. 
The solution for this error is basically replacing the dll files in the browser as mentioned in the solutions of the above guide. 
If the solutions mentioned in the above link are not working for you or if you still get issues with it, you can follow the below two video tutorial solutions. 
(Note that these tutorials were created as a demonstration of my extension but follow the steps of it for replacing the dll and then add your own extension instead of the one shown in the video.)

"""Solution 1 - Steps for adding the extension on Google Chrome browser and steps for fixing the "Signature verification failed!" error. (Temporary solution)

Video tutorial Link:- https://mega.nz/file/cVNwkR5B#EeU9PG_guoit2rWu_nYNRKHi0tum6_ke4D_ejhF9IPA

Notes:-
- First of all watch the above video tutorial.
- If you have watched the video, then continue to read the below guide with the steps which will explain how to properly do what I did in the above video.
- This solution is temporary. If you want a more easy and a permanent solution, please watch and read the Solution 2 from the message below this.
- In the provided extension's readme file it will be mentioned to use older chrome browser versions. However if you follow this guide properly, you will be able to use the extension in the latest chrome browser version even on the latest one.

Guide:-
• Install Google Chrome browser if you do not have it already.
• If you have not added the extension, open the Google Chrome browser and add the extension to the browser as shown in the above video by adding your given API key correctly. Then please close the chrome browser.
• Now open the program RUN on windows. (You can find this by searching on the search bar of windows or by pressing WIN + R keys together)
• Paste the following location on the text box in RUN: %LOCALAPPDATA%\Google\Chrome\User Data\WidevineCdm
• Press the button OK. It will open a folder.
• Then in that opened folder check whether it is empty or if an folder exists there. If a folder exists there, please make sure to delete it first. If any folder do not exist in that opened folder, please continue with the below steps.
• Now go this link (https://mega.nz/file/5B8kkKiQ#px6NpH7JMQkaBiozO3sg_K891dD47pPfWxoDOlaKNc4) and download the WidevineCDM version 4.10.2557.0 zip file.
• Extract it somewhere and copy the extracted folder.
• Now go to that previously opened folder and paste this copied folder there.
• If you did everything correctly, it should look like this (https://postimg.cc/hzwq7kJW).
• Now go to this link (https://mega.nz/file/wJcRkJbR#bkiiVd2cdYsAfzTUpMvZyLPye96wZFmcll72KNFSFf8) and download the .bat file. After it gets downloaded, double click it and run it. It will open a folder. This folder will contain two files named widevinecdm.dll and widevinecdm.dll.sig. Delete those files.
• Now go to this (https://t.me/chromecdm/92) link and download the widevinecdm.dll and widevinecdm.dll.sig files and paste them in the above location as shown in the video.
• Now if your chrome browser is opened, please close it. 
• Open your chrome browser again. Now you are ready. Now you can go to the site which will have the DRM videos you want to get the keys of. Then just by playing it, the keys will be displayed right in front of you.

Note:- If you again get the "Signature verification failed!" error when using the extension in future, that will be because chrome has updated it self again automatically. If this happens, please follow the above procedure again!"""


"""Solution 2 - Using the extension in Portable Google Chrome browser and fixing the "Signature verification failed!" permanently. (Permanent and easy solution)

Video tutorial Link:- https://mega.nz/file/JZV0xBTL#9eAUM2B4atZVnlF6iWf1f-fYTgju3uW6Qfzgyjq8FFM

Notes:-
- First of all watch the attached video tutorial.
- If you have watched the video, then continue to read the below guide with the steps which will explain how to properly do what I did in the above video.
- This solution is permanent (until the ChromeCDM version 4.10.2557.0 gets revoked).

Guide:-
• First download install Portable Google Chrome browser version 110 from this link: https://sourceforge.net/projects/portableapps/files/Google%20Chrome%20Portable/GoogleChromePortable64_110.0.5481.178_online.paf.exe/download
• Then open the installed portable chrome and just add the extension in it as shown in the above video by adding your given API key correctly.
• Now you are ready. Now you can go to the site which will have the DRM videos you want to get the keys of. Then just by playing it, the keys will be displayed right in front of you.

Note:- Please make sure to pin the portable google chrome browser to your windows taskbar since you might not be able to find it again through windows search after you close it."""
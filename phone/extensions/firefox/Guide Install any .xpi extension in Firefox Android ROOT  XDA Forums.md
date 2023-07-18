[![chocolote4444](https://forum.xda-developers.com/data/avatars/s/5727/5727404.jpg?1619268069)](https://forum.xda-developers.com/m/chocolote4444.5727404/)

-   [](https://forum.xda-developers.com/t/guide-install-any-xpi-extension-in-firefox-android-root.4591013/post-88589267)
-   [#1](https://forum.xda-developers.com/t/guide-install-any-xpi-extension-in-firefox-android-root.4591013/post-88589267)

**This guide is purely for educational purposes. I am not responsible for anything wrong that happens to your browser when doing this method.**

**Also note that this isn't a very user friendly way of doing it. This is purely for educational purposes. I'll provide a user-friendly way of doing it soon!!**

**Follow the steps exactly as I do in the video or follow steps below video**

**[YouTube Tutorial](https://youtu.be/JhEuMgpWsRg)**

**\***

**Requirements\*

**



**1\. Rooted phone with Magisk**

**2\. A file explorer!!**

**3\. My extension template**

**1\. Find what extension you want to download. Any links from Gitlab or GitHub will work. For example, any extension with the release links on GitHub you will copy into your clipboard.**

**2\. Download my template and store is somewhere. You'll be editing THREE things inside it. They are the following:**

**public","url":"INSERT URL HERE!!!!!",**

**"name":"INSERT NAME HERE!!!!",**

**"summary":"INSERT SUMMARY HERE!!!",**

**You will replace url with the url download link to the xpi file you copied into your clipboard.**

**Add a name to the extension**

**Then lastly, provide a summary.**

**Save the file.**

**3\. Copy the entire code to your clipboard. Then, with a root browser, navigate to this location:**

**/data\_mirror/data\_ce/0/org.mozilla.fenix/files**

**You will see a file called: mozilla\_components\_addon\_collection\_en\_Extensions-for-Android.json**

**Open it up with a text editor**

**Scroll all the way to the bottom where there will be ":null}\]} at the end of the code**

Delete the last two characters: \]} and add "," Then PASTE your code.

4\. Once pasted, make sure the end of the code ends with

\]}

5\. Close Firefox and relaunch it. You should see an additional extension added at the bottom of the list of extensions.

6.

**Profit!!!!!!!**

**I will be making an Apk or a script soon that will make the process much easier and quicker. I'll provide more updates soon!!!!**



-   [](https://forum.xda-developers.com/attachments/firefox-nightly-addon-template-json.5921571/)
    
    Firefox nightly addon template.json
    
    3 KB · Views: 105
    

Last edited: May 30, 2023
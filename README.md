# facebook-useapp-button
Use a Mobile App or Website Redirecting by Simply use a HTML File.

How to Use:
1) Chek your Device :
##### Browser List :
- /Edge\/\d+/
- /MSIE 9/
- /MSIE 10/
- /MSIE 11/
- /MSIE\s\d/
- /rv\:11/
- /Firefox\W\d/
- /Chrom(e|ium)\W\d|CriOS\W\d/
- /\bSafari\W\d/
- /\bOpera\W\d/
- /\bOPR\W\d/

##### OS List :
- /Windows NT 10/
- /Windows NT 6\.0/
- /Windows NT 6\.1/
- /Windows NT 6\.\d/
- /Windows NT 5\.1/
- /Windows NT [1-5]\./
- /Mac/
- /Linux/
- /X11/
##### Mobile List :
- /iPhone/
- /iP[oa]d/
- /Android/
- /Windows Phone/
- /Lumia/
- /BlackBerry/
- /PlayBook/
- /BB10/
- /webOS/
- /Mobile Safari/
- /IEMobile/
- /Opera Mini/
- /\bCrMo\/
- /Opera Mobi/

##### Tab List :
- /Tablet/
- /iPad/


2) Download the redirect-app.html and Edit the code as you need
```
<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<title>Online Redirection by Devomman</title>
<script type="text/javascript"> // <![CDATA[
//iPhone User:
if((navigator.userAgent.match(/iPhone|iPad/i))) {
    window.location = "https://apps.apple.com/app/xxxxxxxx";}
//Android User:
else if((navigator.userAgent.match(/android|Tablet/i))) {
    window.location = "https://play.google.com/store/apps/details?xxxxxxxxxxx";}
//Website User:
else  {
    window.location = "http://devomman.com";}
// This Code Generate by Muhammad Omman
// email:devomman@gmail.com
</script>
</body>
</html>
```
3) Upload to your host
Ex. yourdomain.com/redirect-app.html
4) Goto your facebook page add a button then use app and add yourdomain.com/redirect-app.html link

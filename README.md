<h1>Computer-Vision-Food-Mixture-Level-Decision-System</h1>
Utilizing Computer Vision to decide whether food is mixed enough compared to designated sample image.<br>

<hr>
<h2>Result</h2>
<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/77074edb-4e76-4d7e-a113-cd6257a02e17" width="45%" height="45%" title="System Decision 1"> &nbsp;&nbsp;
<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/e867d928-8eb7-4f21-b75f-5a7f0dcd7a10" width="41%" height="41%" title="System Decision 2">  <br><br>
When given a standard image, the system decides whether entry image is well mixed or lacks mixed level than the standard image.<br><br><br>

<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/43cfe5a0-c37d-4eb8-8264-6b7c6c6cd4e2" width="45%" height="45%" title="System Decision 3">
<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/55a2f8d1-7152-46bd-b92d-b06edecd4755" width="45%" height="45%" title="System Decision 4"> <br><br>
This is an image of actually using a camera to evaluate whether current food is well mixed. "Good" with green background means food mixed level is high enough, and "Bad" with red background means food is not yet mixed well enough.<br>

<hr>
<h2>Utilizing Hue Entropy</h2>
Key idea to solving this problem is Using Hue compoment of an image. Convert the RGB Image into HSI Image, Getting Hue, Saturation, Intensity information. Hue is mainly used to define what color the bit is. By calculating the Entropy of Hue, we get to know how diverse the colors are in an image.

<hr>
<h2>Acknowledgement</h2>
This system does not guarantee correct analysis of given image. The result could differ from the changes in light setting, resolution of the camera, image noise, unwanted parts such as plate included in the image, etc. <br>
<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/6ad15e4a-bf9f-4d99-aee2-34739e48b7e0" width="41%" height="41%" title="System Decision Fault Example"> &nbsp; &nbsp;
<img src = "https://github.com/mongshil553/Computer-Vision-Food-Mixture-Level-Decision-System/assets/129606995/fdeb09a6-d12e-4cd9-a5a5-be7a35558fd6" width="35%" height="35%" title="Entroy Graph"> 


<hr>
<h2>Image Sources</h2>
Image used in this project is both collected from the Internet and created by our teammates.<br>
Sources of Images collected from the Internet are the following:<br>
https://www.youtube.com/watch?v=X7ozj9FPvNA<br>
https://blog.naver.com/kutty1945/222251561774<br>
https://www.10000recipe.com/recipe/1395916

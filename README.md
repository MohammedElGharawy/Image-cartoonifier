# Image-cartoonifier
Created an Image cartoonifier using Python, Matplotlib and OpenCV

In this project I attempted creating a cartoonified version of an input image by overlaying an edge map created using several filters over a filtered version of the original image.

Stages of filtering:

First I treated the image using median and laplacian filter to reduce noise, define and detect the edges to create an edgemap

⦁	Input image:

![ScreenShot_20210630035619](https://user-images.githubusercontent.com/34549365/123890235-29b45b80-d957-11eb-82c9-7c141a53f687.png)

⦁	Grayscale version:

![ScreenShot_20210630035725](https://user-images.githubusercontent.com/34549365/123890323-4ea8ce80-d957-11eb-8d74-a7aeb3741e6e.png)

⦁	Median Filter:

![ScreenShot_20210630035808](https://user-images.githubusercontent.com/34549365/123890385-684a1600-d957-11eb-93d4-4d109b73fd90.png)

⦁	Laplacian filter:

![ScreenShot_20210630035840](https://user-images.githubusercontent.com/34549365/123890429-7ac44f80-d957-11eb-8407-62e80c8d6ab3.png)

⦁	Thresholding (Edge map) :

![ScreenShot_20210630035910](https://user-images.githubusercontent.com/34549365/123890472-8d3e8900-d957-11eb-8302-7343608b63e3.png)

⦁	Bilateral filter:

![ScreenShot_20210630040007](https://user-images.githubusercontent.com/34549365/123890558-af380b80-d957-11eb-9422-b2f9b9f5cdf4.png)

⦁	Then i  overlaid the output from the bilateral filter over the edge map (Final output):

![ScreenShot_20210630040042](https://user-images.githubusercontent.com/34549365/123890592-c4ad3580-d957-11eb-9c48-ee036d83e996.png)

Output from some test images:

Input

![ScreenShot_20210630040227](https://user-images.githubusercontent.com/34549365/123890841-3ab19c80-d958-11eb-9565-4b846e9d57fb.png)

Output

![ScreenShot_20210630040246](https://user-images.githubusercontent.com/34549365/123890861-42714100-d958-11eb-8f2e-3f89f6b3c4d7.png)


Input

![ScreenShot_20210630040307](https://user-images.githubusercontent.com/34549365/123890876-48ffb880-d958-11eb-884a-f8e6e7ee9ed9.png)

Output

![ScreenShot_20210630040319](https://user-images.githubusercontent.com/34549365/123890890-4e5d0300-d958-11eb-8277-6ccd7433287c.png)


Input

![ScreenShot_20210630040329](https://user-images.githubusercontent.com/34549365/123890899-5452e400-d958-11eb-883e-1b753f4cb775.png)

Output

![ScreenShot_20210630040338](https://user-images.githubusercontent.com/34549365/123890906-587f0180-d958-11eb-8a3b-ff1d65b0e434.png)


Input

![ScreenShot_20210630040347](https://user-images.githubusercontent.com/34549365/123890920-5cab1f00-d958-11eb-8f47-0648f6fec71c.png)

Output

![ScreenShot_20210630040400](https://user-images.githubusercontent.com/34549365/123890936-616fd300-d958-11eb-87fb-5d30abafaed9.png)

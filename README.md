# GoogleImageScrapping
Create a deep learning dataset by scrapping images from Google Images

Deep learning algorithms, especially Convolutional Neural Networks, can be data hungry beasts.
And to make matters worse, manually annotating an image dataset can be a time consuming, tedious, and even expensive process.
So is there a way to leverage the power of Google Images to quickly gather training images and thereby cut down on the time it takes to build your datase.


## STEPS

1. Clone or download the code/repo.

2. Head to Google Images(https://www.google.com/imghp?hl=EN) and enter a query for example 
   (For Example - Carton)
   
3. Open up the JavaScript console by pressing Control + Shift +J

4. The next step is to start scrolling! Keep scrolling until you have found all relevant images to your query.

5. Copy the code from 'js_console.js' file and paste it on JavaScript console and Press ENTER

6. A 'url.txt' file will be downloaded which contains the url of all the images.

7. To download the images files, run python script - 'download_images.py'

8. All the images will be collected in the folder.

Enjoy :)

# GoogleDrive-AutoDateChanger
This is an auto clicker code written on Python to automatically change the dates on photos stored at Google Photos.

Step-by-Step Guide:

1. First, we import the necessary libraries.
2. Second, we define the keyboard commands such as "click", "press", "press and hold", etc. 
  * Note that VK_CODE is the virtual keyboard codes to define the buttons.
3. "Real Code Starts Here" is where the main code is going to be. This is what you need to modify for your own application.
  * You need to define the coordinates as (x,y) where you want to click automatically.
  * To do that, first follow your own hand movements to get the task done.
4. To find out where your mouse is on a screen, type win32gui.GetCursorPos() after hovering your mouse at a location and hit Enter.
5. Change the order of operations based on your needs.
  * Note that this code is prepared to automatically change the dates of the photos on Google Drive, since batch move/change is not available at Google Drive. You may need to adjust the code according to your needs.

# mediciarchiveproject
Automator scripts for the Medici Archive Project by Rijul Jain.

-- For the MIA Upload script (currently only for Mac): 
1. Download this code (click the big green "Code" button and click "Download ZIP") and open the MIA-Upload.workflow file once it downloads. It should open in the Automator application.
2. Have two folders, one for images that haven't been uploaded yet, and one for images that have been uploaded already.
3. Change the existing file path on the line starting with "property uploadFolder" to the file path to your folder for not-yet-uploaded images. (A file path looks like this, for example: "/Users/phoebeprice/Desktop/MDP 518/todo". You can get the file path for your folder by right-clicking on your folder, clicking "Get Info", right-clicking on what's written after "Where: ", and clicking "Copy as Pathname".)
4. Do the same for the file path to the folder for already uploaded images below for the line starting with "property alreadyUploadedFolder".
5. On the MIA Upload page, make sure you've manually started the upload with enough images that there's at least one full page of images. 
6. On the MIA Upload page, click "Add files to upload" and then "CHOOSE IMAGES" and make sure the folder that comes up is your folder for not-yet-uploaded images.
7. On the MIA Upload page, press Command+Shift+Minus two or three times to zoom out the webpage view. This is so that all the buttons the script needs will be in view without scrolling the page.
8. Finally, go back to the script and click the play button right below "Run AppleScript." It should start uploading automatically. If you need to stop the script at any point, just press the square stop button next to the play button.
   
Additional notes:

You may need to watch the MIA window in case any errors pop up that aren't automatically handled by the script. If you press "Close" quickly enough, the script should keep running fine.

What to do if the script crashes: check for the following. If some images show up as having been uploaded on the website, but haven't been moved to the already-uploaded folder on your computer, move those images manually to the already-uploaded folder and then restart the script. Or, if some images have been moved to the already-uploaded folder but haven't been uploaded, just manually upload those and then restart the script. Otherwise, you can restart the script immediately. 

If you get some kind of error when trying to start the script, click anywhere in the code window and press Command-Z to undo any accidental changes to the code. 

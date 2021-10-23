# Anti-ep
A bot for automatically answering Education Perfect mathematics list questions. It currently cannot solve more conplex questions or questions from other topics and can only be a list.

**Note:** It may answer questions incorrectly, will be patched in the future.

**Credit:** Forked from [ExpandingS/Anti-ep](https://github.com/ExpandingS/Anti-ep) 

# Installing/Setup
First of all, please install chromedriver [here](https://chromedriver.chromium.org/downloads), and choose one of the following:
![image](https://user-images.githubusercontent.com/72182515/138532371-b8987eeb-0847-4166-8418-c896c423d13b.png)

It should redirect you to a file directory which will look like this:
![image](https://user-images.githubusercontent.com/72182515/138532408-4cfae696-014b-4361-a685-53b924b23016.png)
Choose one of the zip files according to your OS.

Be sure to extract the folder within the zip file into your Downloads folder. After you have done so, download this repository, extract the contents, open app.py in your code editor and change the executable file path on line 13 to the file path where your own version of the chromedriver file is located.

Navigate to your command prompt, navigate to the folder's path and run `pip install -r requirements.txt`.

If you are not using Windows 64, you will need to remove the geckodriver.exe file and download a new one from [here.](https://github.com/mozilla/geckodriver/releases)

Make sure you have Chrome installed.

To run, type 'app.py' in your command prompt or terminal.
Enjoy!

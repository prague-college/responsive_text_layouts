# Responsive Text Layout

In this project you will be using HTML5 and CSS3 to create a responsive text layout. You'll each be given an article and images that you will use for your layout. 

### Files in this repo
This repo contains the following files and folders which you will use as a starting point.

- `responsive_boilerplate/index.html` 
  - Starting HTML page
- `responsive_boilerplate/main.css` 
  - Starting CSS file with pre-set breakpoints
- `responsive_boilerplate/img`
  - image folder
  
  
Download this entire repository and use it to start your project.

You will need to have some devices on hand to preview your designs while coding. Ideally you will have access to a smartphone, and a tablet, but understandably you might not have these devices. If you can borrow them for a short time to test your design your outcomes will be a lot better, and you'll get more experience dealing with actual devices. If you are unable to get your hands on real devices, you can resize your browser window to view the different breakpoints.


### Designing in the browser
We'll be starting off with some rough static designs, just to prototype the layouts. After a few quick sketches in your design software of choice we will move on to the actual code. This is the best way to develop and refine a web design. 

While coding, be sure to have a browser open and displaying your file. There is a really great tool called Live Reload, which will reload your page each time you save a file, saving you a lot of time from having to manually refresh the page after each save. It costs $10 on the app store. 

#### Preivew your work live on your devices
Follow these steps.

1. Open up **terminal.app** (it's not as scary as you think)
2. Point the terminal to the folder where you are working. To do this first type `cd` which stands for 'change directory'. Don't hit enter yet. Now drag your project folder into the terminal window. It should add the path to the folder into the prompt, looking something like this `cd /Users/ryan/Desktop/project_folder`. Now hit enter.
3.  To view your webpage on other devices, you'll need to find out the IP address of your computer. Paste this command `ipconfig getifaddr en1` into the prompt. This will show you your local IP address. Mine right now is `192.168.1.6`. Write this down someplace as we'll need it in a minute.
4. Now we'll start up a really simple web server to serve your files. Copy this command into the window `python -m SimpleHTTPServer`. This will cause the terminal to display a message like `Serving HTTP on 0.0.0.0 port 8000 …` Cool! Now we can access your folder on other devices on the same network!
5. View your webpage by opening a browser on your phone or tablet and enter the IP address that you received a couple of steps back. You should see your page. 

This is a really cool workflow because you can view your changes in realtime on multiple devices without needing to upload files or anything too time consuming. 

To make this even easier you can install Live Reload and it will automatically refresh all devices every time you save a file!

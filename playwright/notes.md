Playwright is an open-source automation testing tool that is used for testing modern web applications. The prerequisite for Playwright is Node.js
Advantages
- Cross-browser testing, this applies to the CS team currently
-Cross-platform testing is also applicable to the CS team
-Accommodates different programming languages (I prefer JavaScript)
-Allows for mobile emulation(This is advantageous for mobile responsive scenarios) 
-Auto Wait(You do not have to manually write out the waiting for the elements to load Playwright does this for you. 

light bulb Instead of writing:



python
page.wait_for_selector("#login-button") page.click("#login-button") 

You can simply write:



python
page.click("#login-button") 

And Playwright auto-waits for the button to be ready before clicking.)
-Tracing
-Reporting(Crucial for testing)
-Faster and reliable
-Powerful Tooling(This refers to the ability to co-use it alongside other tools)
-No flaky tests

 

PLAYWRIGHT ARCHITECTURE 

Open image-20250423-100842.png
image-20250423-100842.png
The client is our automation script that we write, and we write it in our preferred language.
The server is the middleman between the client and the web browser engines. Playwright is currently making use of CDP to communicate with Chromium and has implemented CDP for the other browsers as well

🧠 What is CDP?

CDP (Chrome DevTools Protocol) is a low-level protocol that is exposed to Chrome and Chromium-based browsers. It lets tools like Playwright control the browser in a very granular way, like inspecting pages, monitoring network traffic, capturing performance data, and even simulating devices.

 

Why we are using Playwright:
Supports multiple browsers
Supports multiple programming languages 
Supports multiple frameworks
Muliple operating systems
Open Source
Emulates mobile devices which we are already doing with the devices on Browserstack
It is fast 
It supports reporting(This can make the current reporting a little bit more easier)
Auto wait - More reliable and less flakey tests

Software Requirements for Playwright

NodeJS

Visual Strudio Code

JavaScript

 

Installation and folder structure

Create a new folder 

Open the folder in VSCode 

Navigate to the Extensions and search for playwright for VSCode and install

Navigate to the Explorer and search for Playwright and select the four options besides the GitHub one and press OK

Let the installations run in the terminal as displayed

The correct folder structure will be displayed

 

✅ So, Why headless: false?

We use headless: false when:

🧪 Debugging – You want to watch what’s happening in the browser step-by-step.

👀 Visual Confirmation – You're testing UI and need to see if elements are loading properly.

📸 Screenshots or Video Recording – It helps when recording tests or doing screen captures.

🧑🏽‍💻 Learning or Demos – If you're just learning Playwright, it’s helpful to see the browser doing its thing

44:02 Continue 

Cursor AI does not run the code by itself. you can run the following command in the Terminal (npx playwright test) which will execute the test for you.

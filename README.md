# L2_Intro_to_git_starter_code
starter code for git activity


→ Click Download or clone and copy the link

→ Now in your machine, create a folder and name it: DS4200
→ In the folder DS4200, create another folder called L2

→ For WINDOWS USERS: right-click on the folder L2 and “open gitbash here” ( if you don’t have git, follow instructions below to download it)
→ For MAC USERS:  right-click on the folder L2 and ‘open Terminal here’

→ In gitbash, write command: git clone (paste the link) then ENTER
→ To navigate into the folder, write command: cd (folder name)
→ Now check status: git status

→ Navigate to DS4200→ L2→intro-to-git-(your_name)
→ Have a look at the HTML, CSS and js files. Detailed explanation: https://www.freecodecamp.org/news/how-to-create-your-first-bar-chart-with-d3-js-a0e8ea2df386/

→ To run these files, we need a Python server.
→ If you don’t already have Python installed, you need to install it 
→ While installing it, make sure you check the box that says: Add Python 3.7.2 to PATH
Refer here if you have doubts:https://realpython.com/installing-python/

→ After installing Python, right click on intro-to-git-(yourname), and open Powershell for Windows or open terminal for MAC
→ Confirm Pyhon is installed by writing command: python --version (you should get the version number as output)
→ Run a local server by writing this command: python -m http.server
→ Wait for the output: Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) …

→ Now open a web browser and type the url as: localhost:8000
→ You should see the bar chart

Now, You need to:
→ Open index.js in a text editor and change the color of the bars from steelblue to red
→ Save it
→ Refresh the web browser, and you should see the change

→ Now download this image in the folder intro-to-git-(yourname) folder:
http://www.quickmeme.com/img/75/7509f68823389e4af3777ca6d3744c632cc32ab3547bc56e319126aa29ab149a.jpg
→ Open the index.html file in a text editor (notepad, sublime, vs code etc)
→ Uncomment the following:
<!-- <h4> Adding an Image here</h4>
       <img src="" /> →

 → And change it to 
<h4> Adding an Image here</h4>
<img src="" />

→ Now add your image in the " " 
→ Save
→ Refresh the web browser to see the changes (you should see the image below the barchart)

→ Now its time to push these changes to the remote repository
→ Go to gitbash/ terminal
→ Write these commands in the order: git add .
                    git commit -m “comment”
                    git push
                       
 
NOTE: If any of this fails, ask for assistance and do not proceed ahead. This is because this will put your repository in an uncertain state which will be hard to undo.





For Windows users:

→ Download git if you don’t have it in your machine. Follow this link:
https://git-scm.com/downloads

→ Click download for windows
 

→ MAKE SURE YOU CHECK THE BOX SAYING (GIT BASH HERE)

→ After installation, open git bash.

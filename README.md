# My Website
My website developed using CSS and HTML5, using the SASS build tool.

# To Modify
1. Clone copy of code from GitHub repo.
2. From Git bash prompt, run git clone [code repo] to install on local directory. 
3. Change directory to code folder
4. Run npm install to install node dependencies
5. Run code . to launch code in Visual Studio IDE
6. In Visual Studio, open a terminal (ctrl+`) and run npm run sass.
7. To view code in browser, open the index.html file in Visual Studio, right-click mouse and select 'Open with LiveServer'
8. Make required changes to the website. .Any changes to the code will be refllected immedietley on the browser due to the script settings in the package.json file.

# To Launch Website via Github pages:
1. Update the latest changes to your code to your github repository.
2. Make sure that the gh-pages node module dependencies are installed. If not, run 
npm install gh-pages
3. If not set up, install the following line in your package.json file, just above the "scripts" line:
"homepage": "https://<your github username>.github.io/<name of the repository> (e.g. https://AustinOsti.github.io/selfprojects_myprofile)
4. Set up the deploy code under within the "scripts" section, as follows:
"deploy": "gh-pages -d dist"
5. Within the code folder, run the command below to publish the website:
npm run deploy  
6. On your browser, navigate to the 'homepage' (e.g. https://AustinOsti.github.io/selfprojects_myprofile) to access your website.

# To Launch Website via Netlify:
1. Update the latest changes to your code to your github repository.
2. Make sure that you have the Netlify cli installed globally. To Install, run:
npm install netlify-cli -g
3. Change directory to code folder
4. Run netlify deploy

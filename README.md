Build Your Own AI Website Lab
Course: Beginning Web Development
Time: 1 hour 15 minutes
Goal: Use AI to help create a simple website, edit the HTML/CSS yourself, and publish it on GitHub Pages.
What you will learn
By the end of this activity, you should be able to:
•	use AI as a coding helper
•	generate a basic website layout
•	identify and edit HTML content
•	identify and edit CSS styles
•	test changes locally
•	upload a project to GitHub
•	deploy a live website with GitHub Pages
________________________________________
Part 1: What you are building
Today you will create a simple personal website with help from AI.
Your website should include:
•	a title or name
•	a short welcome message
•	an “About Me” section
•	a list of interests, hobbies, or favorite technologies
•	at least one image
•	at least one link
•	custom colors and styling using CSS
You will first ask ChatGPT to generate the code. Then you will download or copy that code into your own files, edit it yourself, and publish it online.
________________________________________
Part 2: Before you start
Make sure you have:
•	a GitHub account
•	a folder on your computer for this project
•	a code editor such as VS Code
•	access to a browser
•	access to ChatGPT
Create a project folder named something like:
ai-website-lab
Inside that folder, create these files:
index.html
style.css
If you want an image folder too, create:
images
________________________________________
Part 3: Ask AI to generate your website
Go to ChatGPT and use a prompt like this:
Create a simple beginner-friendly personal website using only HTML and CSS.

Requirements:
- One file called index.html
- One file called style.css
- Include a header with my name
- Include an About Me section
- Include a list of hobbies or interests
- Include a favorite websites section with links
- Include a footer
- Use beginner-friendly code with comments
- Do not use JavaScript
- Keep the code simple enough for a freshman web development student
If you want, you can make it more personal:
Create a simple beginner-friendly personal website using only HTML and CSS.

My name is [Your Name].
My interests are [music, gaming, dogs, AI, sports, etc.].
My favorite color is [blue].
I want a clean, modern design.

Requirements:
- separate HTML and CSS
- comments explaining the main parts
- no JavaScript
- beginner-friendly structure
Important
Do not just leave the AI output untouched. The point of the activity is to:
•	understand what the code is doing
•	edit it yourself
•	personalize it
•	deploy it
________________________________________
Part 4: Put the code into your files
Take the HTML code from ChatGPT and paste it into:
index.html
Take the CSS code from ChatGPT and paste it into:
style.css
Save both files.
Your HTML should include a line like this inside the <head> section:
<link rel="stylesheet" href="style.css">
That line connects your HTML file to your CSS file.
________________________________________
Part 5: Open the site on your computer
Open index.html in your browser.
You should now see your website.
If it does not look styled, check:
•	did you save both files?
•	is the CSS file named exactly style.css?
•	is the link tag correct?
•	are index.html and style.css in the same folder?
________________________________________
Part 6: Edit the website yourself
Now you must make changes manually.
Required edits
Make at least 5 changes to your site.
Examples:
•	change the page title
•	change the heading text
•	change the background color
•	change the font color
•	add your own hobbies
•	add a new section
•	replace placeholder text
•	add a real image
•	change button or link colors
•	round corners on a box
•	center text
•	change spacing or margins
Minimum expectations
You must change at least:
•	2 HTML items
•	2 CSS items
•	1 extra personalization of your choice
________________________________________
Part 7: Suggested starter structure
A simple site might include sections like this:
<header>
  <h1>Your Name</h1>
  <p>Welcome to my website</p>
</header>

<main>
  <section>
    <h2>About Me</h2>
    <p>I am a student learning web development.</p>
  </section>

  <section>
    <h2>My Interests</h2>
    <ul>
      <li>Music</li>
      <li>AI</li>
      <li>Dogs</li>
    </ul>
  </section>

  <section>
    <h2>Favorite Links</h2>
    <p><a href="https://github.com" target="_blank">Visit GitHub</a></p>
  </section>
</main>

<footer>
  <p>Created by Your Name</p>
</footer>
And CSS like this:
body {
  font-family: Arial, sans-serif;
  background-color: #f4f7fb;
  color: #222;
  margin: 0;
  padding: 0;
}

header {
  background-color: #4a90e2;
  color: white;
  text-align: center;
  padding: 30px;
}

main {
  padding: 20px;
}

section {
  background-color: white;
  margin: 20px auto;
  padding: 20px;
  max-width: 800px;
  border-radius: 10px;
}

a {
  color: #4a90e2;
}
________________________________________
Part 8: Add an image
You may use either:
•	an online image URL
•	or a local image saved in your images folder
Example using an online image
<img src="https://via.placeholder.com/300" alt="Placeholder image">
Example using a local image
<img src="images/myphoto.jpg" alt="My photo">
If you use a local image, make sure:
•	the image is actually inside the images folder
•	the spelling matches exactly
•	the extension matches exactly (.jpg, .png, etc.)
________________________________________
Part 9: Push your project to GitHub
Step 1: Create a repository on GitHub
Go to GitHub and create a new repository.
Suggested repository name:
ai-website-lab
You may make it public.
Step 2: Upload your files
You can do this either through the GitHub website or with Git commands.
Option A: Easiest method for beginners
Upload index.html, style.css, and any images directly on GitHub using Add file → Upload files.
Option B: Git commands
If Git is installed, open a terminal in your project folder and run:
git init
git add .
git commit -m "Initial website commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ai-website-lab.git
git push -u origin main
Replace YOUR-USERNAME with your actual GitHub username.
________________________________________
Part 10: Deploy with GitHub Pages
Once your files are on GitHub:
1.	Open your repository
2.	Click Settings
3.	Click Pages
4.	Under Build and deployment
o	Source: Deploy from a branch
o	Branch: main
o	Folder: /root
5.	Click Save
After a minute or two, GitHub will give you a live link.
It will usually look something like:
https://yourusername.github.io/ai-website-lab/
Open the link and test your site.
________________________________________
Part 11: Make one more change after deployment
After your site is live, make one more visible change.
Examples:
•	change the background color
•	add a sentence
•	add a border
•	change the footer text
•	add another list item
Then push or upload the updated file(s) again and refresh the live site.
This shows that deployment updates the published website.
________________________________________
Troubleshooting guide
Problem: My CSS is not working
Check:
•	is the CSS file named style.css?
•	is this line in your HTML?
<link rel="stylesheet" href="style.css">
•	are both files in the same folder?
Problem: My image is broken
Check:
•	is the file path correct?
•	is the image in the right folder?
•	did you spell the filename correctly?
•	does the extension match?
Problem: GitHub Pages shows a 404
Check:
•	did you name the main page index.html?
•	did you enable Pages in Settings?
•	did you choose the main branch?
•	did you wait a minute and refresh?
Problem: My changes are not showing online
Check:
•	did you save the file?
•	did you upload/push the updated version?
•	did you refresh the live page?
________________________________________
Rules for using AI today
You may use AI to help generate code, but you still need to understand and edit the project yourself.
You should be able to explain:
•	what HTML file holds the content
•	what CSS file controls the styling
•	what you changed manually
•	how the website got from your computer to GitHub Pages
Do not submit a site that is completely AI-generated with no personal edits.
________________________________________
Challenge mode
If you finish early, try one or more of these:
•	add a navigation bar
•	add a second page
•	add cards for hobbies or projects
•	add a hover effect to links or buttons
•	add a gradient background
•	add a contact section
•	add a photo gallery
•	improve spacing and alignment
•	make the site look better on mobile
________________________________________
Sample reflection template
AI helped me create the starter structure and some of the CSS styling.

I personally changed the colors, updated the About Me section, added my own image, and edited the list of interests.

The hardest part was getting GitHub Pages to work and making sure my file names matched.

I learned that HTML controls the structure of the page, CSS controls the design, and GitHub Pages can publish a website directly from a repository.



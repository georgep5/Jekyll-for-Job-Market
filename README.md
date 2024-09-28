# Jekyll Job Market Site Setup and Configuration

Welcome to the guide for setting up your professional economics job market website. This template was adapted for NIU Graduate Students by [AdamBougher](https://github.com/adambougher) and [drklis](https://github.com/drklis/) based on the design used by [pwills.com](http://www.pwills.com), which is hosted on GitHub Pages and utilizes the elegant [Minimal Mistakes template](https://github.com/mmistakes/minimal-mistakes).

The site is built using Jekyll, a powerful static site generator, providing a clean and professional layout for showcasing your academic profile. This setup allows for easy customization while maintaining a polished appearance suitable for the economics job market. You may wish to complete the [Microsoft Learn tutorial](https://learn.microsoft.com/en-us/training/modules/create-host-web-sites-github-pages/) and associated [GitHub interactive exercise](https://github.com/skills/github-pages) in order to go over the basics prior to setting up your website with this template.

### Purpose of a Job Market Profile Website

In the competitive landscape of the economics PhD job market, having a professional online presence is crucial, regardless of your target (academia, government, industry/tech). A well-designed personal website serves multiple purposes:
1. It showcases your research, teaching experience, and professional background in one centralized location.
2. It provides easy access to your CV, job market paper, and other relevant documents for potential employers.
3. It can demonstrate your technical skills and attention to detail, qualities that are valued in the field of economics.
4. It offers a platform to share your academic interests, ongoing projects, and professional goals.

### Why This Template?

This template offers several advantages for students going on the job market:

- **Clean and Professional Design**: The Minimal Mistakes theme provides a simple, modern look that works well for academic profiles.
- **Cost-Effective**: Hosted on GitHub Pages, this solution is completely free, allowing you to allocate your resources elsewhere in your life/job search.
- **Customizable**: While maintaining a professional appearance, the template is flexible enough to reflect your individual academic identity.
- **Easy to Implement**: The following instructions are detailed and user-friendly, making it accessible even for those with limited web development experience while also improving your coding skills.

## Getting Started

The instructions that follow will guide you step-by-step through the process of setting up your own professional economics job market website. Whether you're tech-savvy or new to web development, these detailed instructions will help you create a polished online presence to support your job market journey. *Let's get building!*

### Step 0: Sign up for GitHub

If you do not yet have a GitHub account, sign up for one. An easy guide to doing so is available [here](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).
- Make sure to choose a professional sounding username! Stay away from silly words and numbers. Consider something simple and identifiable, such as JaneDoe, mkowal, or JSmithNIU. *You can change your username; please see instructions for doing so [here](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-user-account-settings/changing-your-github-username).*
- Use your university email address in making your account to be eligible for GitHub Education, which has numerous benefits. Follow [these instructions on applying to GitHub Education](https://docs.github.com/en/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-education-for-students/apply-to-github-education-as-a-student) as a student.

### Step 1: Clone this Repository

1. Click the green "Use this template" button.
2. In the dropdown menu, right-click "Create new repository" and open it in a new tab.
3. Name your repository professionally, e.g., "Jane-Doe-Profile" or "John-Smith-Academic".
4. You can leave description blank, or you can write a meaningful phrase like "My Jekyll job market profile".
5. Make sure the repository is set to "Public".
6. Click "Create repository".
7. Keep these instructions open in a separate tab. If you accidentally close the tab, the instructions will automatically be included in your new repo as the README.md file.

### Step 2: Upload Your Documents

1. In your new repository, navigate to the `assets/images` folder.
2. Click "Add file" > "Upload files".
3. Upload your professional headshot(s) and an image of your email address that is slightly warped.
    - Resize your headshot before uploading: Aim for a width of around 300-500 pixels. This ensures fast loading times without sacrificing image quality.
    - You may want two headshots -- one for the author profile in the sidebar and another for the landing page.
    - Create a warped email address[^1] image: Aim for a width of around 150-200 pixels.  
        - *Option 1 (Photoshop/Illustrator)*: Type your email address, then use the warp tool to slightly distort it.  
        - *Option 2 (AI-generated)*: Use an AI image generator with a prompt like "A slightly warped email address on a white background, black text, email: `youremail@example.com`".  
        - *Option 3 (Online tools)*: Use free online image editors like Canva or Pixlr to create and warp text.  
4. Navigate to the `assets/docs` folder.
5. Click "Add file" > "Upload files".
6. Upload your CV and job market paper in PDF format.

### Step 3: Update _config.yml

1. In your repository, find and click on the `_config.yml` file.
2. Click the pencil icon to edit the file.
3. Update the following fields:
   - Find `title:` in the code and change "Jekyll Profile" to your full name (e.g. "Jane Smith"). *Make sure you keep the quotation marks around your entry here and in the following details in this file!*
   - Find `name:` and replace "A Free Job Market Profile in Jekyll" with "Jekyll Website for [Your Full Name]" or "Profile for [Your Full Name]".
       - Note: the square brackets here and in the following steps indicate a blank to fill in. Remove the square brackets when you put in your information (e.g. "Jekyll Website for Jane Smith").
   - Update `email:` with your professional email address.
   - Update `url:` to "https://[yourgithubusername].github.io".
   - Update `baseurl:` to "/[your-repo-name]" (e.g., "/Jane-Doe-Profile") for the name of the repo you're working in with this website.
   - Change `repository:` to "[yourgithubusername]/[your-repo-name]".
   - Scroll down to `# settings for author profile`. Under `author:`
     - Update `name:` with your full name in quotation marks.
     - Change `avatar:` to "/assets/images/[your-image-filename]".
     - Update `bio:` with a brief professional description of yourself.
     - Update `github:` with your GitHub username (if applicable).
     - Update `linkedin:` with your LinkedIn profile URL.
4. Click "Commit changes".  
    - You can choose either "Commit directly to the `master` branch" or "Create a **new branch** for this commit and start a pull request." If you work slowly, follow these instructions carefully, and do not touch other settings, you can have some confidence in committing directly to the master branch.

### Step 4: Set Up GitHub Pages

1. Go to your repository's "Settings" tab.
2. Click on "Pages" in the left sidebar.
3. Under "**Source**", leave the option "Deploy from a branch" in place. Below that, under "**Branch**" select the branch you want to deploy (usually "main" or "master").
4. Leave "/(root)" for the folder.
5. Click "Save".
6. Go back to your repo's "Code" tab. On the right-side, find "**About**" and click the setting gear wheel next to it.
7. Check the box next to "**Use your GitHub Pages website**" which should immediately update the Website field to your "https://[yourgithubusername].github.io/[your-repo-name]/".
8. Click "Save changes".
9. Wait a few minutes for your site to be published.
10. Right-click the link now for your profile and open it in a new tab.

Now, every time you click "Commit changes" and commit directly to the master branch, you should be able to see your updates happen on your profile. You will need to hit refresh, and you may need to wait for a moment, even up to a few minutes. 

Hopefully, by following this guide, we limit any issues with page build. However, if your changes are not showing up, make sure to look at your code page and scroll down to **Deployments**. If you see a 🟢 (green circle) with a checkmark, then github-pages has been successful. If you see a 🟠 (orange/yellow circle), it is still building and deploying. If you see a red ❌, you will need to troubleshoot the deployment. Search for answers online, in the GitHub forums/documentation, or consulting with an AI like Claude.

### Step 5: Update index.md

1. In your repository, find and open the `index.md` file.
2. Click the pencil icon to edit.
3. Update the image link:


[^1]: The warped email image is a simple yet effective measure to protect your email address from automated scraping. Web crawlers and bots often harvest email addresses from websites for spam lists. By presenting your email as a slightly distorted image, it remains easily readable for human visitors while being much more difficult for automated systems to recognize and collect. This small step can prevent an increase in the amount of unwanted emails and spam that would come from putting up your email address directly.

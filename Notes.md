# Publish npm Project on GitHub with GitHub Pages

Follow these steps to publish your npm project on GitHub with a GitHub Pages site.

1. **Create a GitHub Repository:**
   - Log in to GitHub and create a new repository for your project.

2. **Clone the Repository: or connect it to your local git repo**
   - Clone the GitHub repository to your local machine using:
     ```
     git clone https://github.com/your-username/your-repo.git
     ```

4. **Install Dependencies:**
   - Install dependencies for your project using `npm install`.


5. **commit changes and push it to the repo**


6. **add this ` "homepage":"https://username.github.io/name-of-your-repository"  ` to `package.json`


7. **Build Your Project: (creating build folder)**
   - `npm run build`
   

8. **Deploy and publish it in gh-pages:**
   - `npm run publish`



9. **congradulations its published :):**
- visit the link that you added to package json (`https://your-username.github.io/your-repo`.)
   - In repository settings, under "GitHub Pages," select the `gh-pages` branch as the source.

10.  **from now on every changes you do locally , you can commit changes and `npm run build` and then `npm run publish` will update your website :)**
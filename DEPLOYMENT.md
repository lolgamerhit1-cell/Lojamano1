# DEPLOYMENT.md

## Deployment Instructions for Netlify

To deploy the Lojamano1 project on Netlify, follow the steps below:

### 1. Create a Netlify Account
- Go to [Netlify](https://www.netlify.com/) and sign up for a free account if you don’t already have one.

### 2. Connect Your GitHub Repository
- Once logged in, click on the **New site from Git** button.
- Select **GitHub** from the options.
- Authorize Netlify to access your GitHub account.

### 3. Find the Repository
- In the repository selection screen, find and select the `Lojamano1` repository from your list of GitHub repositories.

### 4. Configure Your Settings
- **Branch to deploy:** Ensure that the `main` branch is selected.
- **Build command:** If your project uses a build tool, specify the build command (for example, `npm run build`). If not, you can leave this blank.
- **Publish directory:** Specify the directory that contains the compiled output. This is usually `dist` or `build`, depending on the project setup.

### 5. Deploy Your Site
- Click the **Deploy Site** button.
- Netlify will start the deployment process, and upon completion, you will be assigned a temporary URL for your site.

### 6. Update Domain Settings (Optional)
- If you wish to use a custom domain, go to the domain settings in the Netlify dashboard and add your custom domain.
- Follow the instructions given by Netlify for domain verification and DNS setup.

### 7. Continuous Deployment
- With GitHub integration, every time you push updates to the `main` branch, Netlify will automatically rebuild and deploy your site.

### 8. Troubleshooting
- If the deployment fails, check the logs provided by Netlify to identify the issues and resolve them accordingly.

### Conclusion
Your Lojamano1 project should now be deployed on Netlify! Enjoy your website!
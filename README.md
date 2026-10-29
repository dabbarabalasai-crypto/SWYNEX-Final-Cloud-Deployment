# SWYNEX Final Cloud Deployment

## 1. Project Overview

This project presents a final cloud deployment case study for a simple static website. It combines cloud architecture, deployment steps, monitoring procedures, cost awareness, security practices, and lessons learned.

**Project Name:** Basic Cloud Deployment  
**Hosting Platform:** GitHub Pages  
**Technologies Used:** HTML, CSS, GitHub, GitHub Pages

**Live Website:** https://dabbarabalasai-crypto.github.io/SWYNEX-Cloud-Architecture-Outline/

**Task 2 Repository:** https://github.com/dabbarabalasai-crypto/SWYNEX-Cloud-Architecture-Outline

**Task 3 Repository:** https://github.com/dabbarabalasai-crypto/SWYNEX-Monitoring-and-Cost-Awareness

## 2. Cloud Architecture

The website uses a simple static hosting architecture.

### Architecture Components

- **Frontend:** HTML provides the webpage structure.
- **Styling:** CSS controls the webpage appearance.
- **Source Code Repository:** GitHub stores the website files.
- **Cloud Hosting:** GitHub Pages publishes the static website.
- **Monitoring:** Browser checks and GitHub Actions deployment status.
- **Security:** HTTPS, account protection, and repository access controls.

### Architecture Flow

Developer → GitHub Repository → GitHub Pages Deployment → Live Website → User's Browser

### Architecture Explanation

The developer uploads HTML and CSS files to GitHub. GitHub Pages publishes the website using the repository's configured deployment source. Users access the published website through its HTTPS URL.

This project uses GitHub Pages for static hosting. It does not currently deploy a separate backend API or database.

## 3. Deployment Procedure

1. Create a GitHub repository for the website.
2. Upload `index.html` and `style.css`.
3. Add a `README.md` file describing the project.
4. Open the repository's Settings.
5. Select Pages under the repository settings.
6. Choose **Deploy from a branch** as the publishing source.
7. Select the `main` branch and the `/(root)` folder.
8. Save the settings.
9. Wait for GitHub Pages to publish the website.
10. Open the published URL and verify that the website loads correctly.

### Deployment Verification

- Confirm that the live URL opens.
- Check that HTML content is displayed.
- Check that CSS styling works correctly.
- Check the GitHub Actions deployment status.
- Review workflow logs if deployment fails.

## 4. Monitoring and Status Checks

Monitoring helps identify website availability issues and deployment failures.

### Monitoring Procedure

1. Open the live website in a browser.
2. Check whether the page loads successfully.
3. Verify the content and styling.
4. Open the repository's Actions tab.
5. Check the latest Pages deployment workflow.
6. Review logs if the workflow reports a failure.

### Simple Alert Idea

Check the website and deployment status daily. If the website becomes unavailable or deployment fails, investigate the issue and correct it.

This is a proposed manual monitoring procedure; automated uptime alerts have not been configured in this project.

## 5. Cost Awareness

Cost awareness helps prevent unexpected expenses when using cloud services.

### Cost Management Checklist

- Identify the hosting services used by the project.
- Review current pricing and usage limits.
- Set budget notifications when supported by the provider.
- Review billing and usage information regularly.
- Remove unused cloud resources.
- Monitor storage and data transfer charges where applicable.

GitHub Pages is the hosting platform used in this project. No additional AWS services are claimed as deployed. Always check the current provider terms and account billing information rather than assuming every service is free.

## 6. Security and Access Control

The following practices help protect the project:

- Enable two-factor authentication for the GitHub account.
- Use a strong, unique password.
- Never upload passwords, API keys, or access tokens to the repository.
- Review repository visibility and collaborator permissions.
- Grant only the access that collaborators require.
- Use HTTPS to access the live website.
- Review files before publishing them publicly.
- Keep development tools and dependencies updated where applicable.

## 7. Testing and Results

The deployment is verified by checking the published website and reviewing the GitHub Pages deployment status.

### Expected Results

- The static website opens using its published URL.
- HTML content is visible.
- CSS styling is applied.
- GitHub provides a deployment status and workflow logs.
- Monitoring, cost awareness, and security procedures are documented.

Actual test results should be confirmed by opening the live website and checking the latest deployment status.

## 8. Challenges and Solutions

**Challenge 1: Publishing the website**

Solution: Configure GitHub Pages to publish from the `main` branch and root folder.

**Challenge 2: Verifying deployment**

Solution: Open the live URL and inspect the latest deployment workflow.

**Challenge 3: Understanding cloud costs**

Solution: Identify the services actually used and review their current pricing and limits.

**Challenge 4: Protecting project resources**

Solution: Use account security features, HTTPS, and appropriate repository access permissions.

## 9. Lessons Learned

Through this project, I learned:

- How to organize source code in a GitHub repository.
- How to deploy a static website using GitHub Pages.
- How HTML and CSS work together in a website.
- How to check deployment status and review workflow logs.
- Why monitoring and cost awareness matter in cloud computing.
- How security and access-control practices help protect projects.
- How to document a cloud deployment case study.

## 10. Future Improvements

- Configure automated website uptime monitoring.
- Set up notifications for deployment failures.
- Improve accessibility and mobile responsiveness.
- Add a backend API and database if the application requires dynamic functionality.
- Add automated testing before deployment.
- Review security and cost practices regularly.

## 11. Conclusion

This project demonstrates the basic deployment of a static website using GitHub Pages. It brings together the deployment process, cloud architecture, monitoring procedures, cost awareness, security practices, and lessons learned in a single case study.

The project provides a foundation for understanding cloud hosting and for developing more advanced cloud applications in the future.

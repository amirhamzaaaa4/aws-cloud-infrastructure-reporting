# GitHub publishing and LinkedIn guide

## Repository metadata

**Name:** aws-cloud-infrastructure-reporting

**Description:** Academic cloud portfolio: AWS S3 hosting, RDS MariaDB, Lambda reporting and SNS notifications, with security group controls and a Google App Engine companion project.

**Suggested topics:** aws, amazon-s3, aws-lambda, amazon-rds, amazon-sns, mariadb, serverless, cloud-computing, cloud-networking, security-groups, python, google-cloud, google-app-engine, flask, academic-project, portfolio

## Upload using the GitHub website

1. Extract the ZIP. Open the inner aws-cloud-infrastructure-reporting folder.
2. Sign in to GitHub and create a repository using the name and description above. Choose Public for recruiter access; leave the generated README, licence and gitignore options unchecked.
3. In the empty repository, use the uploading an existing file link. In an existing repository, choose Add file, then Upload files.
4. Drag the contents of the inner folder into the upload area, including docs, images, src, config, README.md, .gitignore and .gitattributes. Upload the contents, not the ZIP or its enclosing folder.
5. Check that README.md will be at the root and images will be under images/aws and images/gcp. Commit with a message such as Add academic cloud portfolio and sanitised evidence.
6. Open the repository homepage and review the rendered README and screenshots. Confirm folders retained their names and paths.
7. Use the About settings gear to enter the description and suggested topics, then save.
8. Copy the repository URL into your CV, GitHub profile and LinkedIn project entry. Replace the URL placeholder in the LinkedIn copy below.

These steps follow GitHub's [file upload guidance](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) and [topic guidance](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics). This package has fewer than 100 files and no file approaching the browser's 25 MiB limit.

Only upload the prepared repository folder. Keep original reports and work files outside GitHub. No licence is added because the reports do not establish rights to redistribute all original academic assets; choose a licence later only for material you have authority to license.

## Optional Git upload

Create an empty repository on GitHub first, authenticate Git, and open a terminal inside the extracted repository folder. Replace YOUR-USERNAME with your account name before running:

```sh
git init
git branch -M main
git add .
git commit -m "Add academic cloud portfolio and sanitised evidence"
git remote add origin https://github.com/YOUR-USERNAME/aws-cloud-infrastructure-reporting.git
git push -u origin main
```

This alternative follows GitHub's [locally hosted code guidance](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github). There is no remote URL configured in the ZIP, and no account token is required inside repository files.

## LinkedIn project description

**Title:** AWS Cloud Infrastructure & Serverless Reporting System

Hands-on academic project completed during my Bachelor of Information Technology at CQUniversity Australia. I deployed an S3-hosted cafe website, configured RDS MariaDB network access through security groups, and tested Python Lambda reporting with SNS email notifications. The portfolio includes captured test results, troubleshooting, security considerations and a separate Google App Engine deployment exercise. It demonstrates practical cloud configuration, networking and technical documentation skills relevant to IT and cloud support internships.

Repository: PASTE-YOUR-GITHUB-REPOSITORY-URL

Use the actual GitHub URL after uploading. Add this under Projects rather than employment experience. A public repository URL is the only required change to this LinkedIn copy; the repository README needs no account-specific edits.

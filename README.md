# AWS Solutions Architect Associate — SAA-C03 Notes

Mobile-friendly HTML cheat sheets for revising AWS architecture trade-offs, choosing services, and recognizing exam traps.

## Website

After GitHub Pages is enabled: **https://skuntla.github.io/aws-solutions-architect-associate/**

## Setup GitHub Pages (one-time)

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source → GitHub Actions**.
3. If GitHub says Pages is not available, note that this repository is currently **private**. Publishing a private repository's Pages site depends on your GitHub plan. You may need an eligible paid plan or to make the repository public if you want the site public.
4. Open **Actions → Deploy AWS SAA notes to GitHub Pages** and choose **Run workflow** if it did not start automatically.
5. Once the deployment succeeds, open the website above.

The workflow is `.github/workflows/pages.yml`. The website itself is a standalone `index.html`, so no build tools are needed.

## Current sections

- S3 storage classes, minimum retention charges, 24-hour staging example
- Aurora, read replicas, RDS Proxy, Global Database, DynamoDB Global Tables
- SQS, SNS, EC2 Auto Scaling and ElastiCache architecture clues
- IAM, security groups, NACLs and monitoring tools
- Networking, load balancers, Route 53, CloudFront and containers
- Disaster recovery patterns, RPO/RTO and exam traps
- Expandable rapid-recall practice prompts

## Extend notes

Edit `index.html` on `main` to add content. Changes will automatically deploy once Pages is enabled.

These are unofficial study notes. Confirm current product details and limits in [AWS documentation](https://docs.aws.amazon.com/).

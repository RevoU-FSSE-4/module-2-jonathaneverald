[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-vSzXkEt)

# Dota 2

This is a website about what is Dota 2

![Dota-2-Logo](./img/dota-2-logo.png)

Dota 2 is a 2013 multiplayer online battle arena (MOBA) video game by Valve. The game is a sequel to Defense of the Ancients (DotA), a community-created mod for Blizzard Entertainment's Warcraft III: Reign of Chaos. Dota 2 is played in matches between two teams of five players, with each team occupying and defending their own separate base on the map. Each of the ten players independently controls a powerful character known as a "hero" that all have unique abilities and differing styles of play. During a match players collect experience points and items for their heroes to defeat the opposing team's heroes in player versus player combat. A team wins by being the first to destroy the other team's "Ancient", a large structure located within their base. Dota 2 is a multiplayer online battle arena (MOBA) video game in which two teams of five players compete to destroy a large structure defended by the opposing team known as the "Ancient" whilst defending their own. As in Defense of the Ancients, the game is controlled using standard real-time strategy controls, and is presented on a single map in a three-dimensional isometric perspective. Ten players each control one of the game's 124 playable characters, known as "heroes", with each having their own design, strengths, and weaknesses. Heroes are divided into two primary roles, known as the core and support.

You can access module 2 checkpoint website with this [link!](https://jonathanportfolio.site/)

# Module 2 Assignment

## Netlify Sign up process & connect Netlify to GitHub project

### Log in or Sign Up for a Netlify Account

- First, go to the Netlify website: https://www.netlify.com/.
- Click the Log in button if you already have an account, or Sign Up to create a new one.
- In this guide, we will log in using a GitHub account.

### Import Your Project

- Once logged in, select Sites from the sidebar menu.
- Click the Add new site button and choose Import an existing project.

  ![Import Project](./img/import-project.png)

- You will be directed to a page to choose the source of your project deployment.
- Click the Deploy with GitHub button to connect your GitHub project to Netlify.

  ![Deploy Github](./img/deploy-github.png)

### Connect Your GitHub Account

- Enter your GitHub credentials if you haven't logged in to Netlify using GitHub.
- Select the RevoU-FSSE-4 repository since the module 2 project is located there.

  ![Connect GitHub](./img/connect-github.png)

### Make Sure Your Project is Public

- Before selecting the project you want to connect, make sure it is set to public so it can be accessed.
- If it is still private, you can change the project settings in GitHub.

### Deploy Your Project

- Select the project you want to connect and click the Deploy (project name) button.
- Wait until the project finishes deploying through Netlify.

### Check Your Website

- Once the project has been successfully deployed, click the deployed website page to check your website.

  ![Check Website](./img/check-website.png)

## Auto Deployment on GitHub with Netlify

### Verify the Website Connection to GitHub

- To check if auto deployment is working, first make sure the website you deployed is connected to the GitHub repository.
- You can see this in the Site Overview menu on Netlify.

  ![Check Website Connected to Github](./img/auto-deploy-1.png)

### Make Changes to the Website Code

- Next, open the website of the project that is already connected to GitHub and try to make changes to the website through the project's code content.
- In this case, we will try to change the background color of the website.
- Then, do git add, git commit, and git push to the main branch of the project in GitHub.

  #### Website Pages Before Changes

  ![Website before changes](./img/auto-deploy-2.png)

### Check for Auto Deployment on Netlify & Verify the Website Updates

- After pushing to the main branch, you can check on Netlify if your project has been automatically deployed through the Production Deploys menu.
- If the production status is Published, you can open the website to check if it has been updated according to what you pushed to the main branch.

  ![Production Deploys Status](./img/auto-deploy-4.png)

### Confirm Successful Auto Deployment

- If the website has changed, then the auto deployment process from GitHub through Netlify has been successful.
  #### Website Pages After Changes
  ![Website after changes](./img/auto-deploy-3.png)

## How to connect custom domain and DNS

### Purchasing a Domain on Niagahoster:

- Open the Niagahoster website: Go to https://www.niagahoster.co.id/ and click "Cari & Cek Domain" (Search & Check Domain) on the main page.
  ![Check Domain](./img/domain-1.png)
- Enter your desired domain name: For example, type in dota2byjonathan.site. Then click the "Cek Sekarang" (Check Now) button.
  ![Enter Domain Name](./img/domain-2.png)
- Select your domain: If the domain is available, click the "Pilih" (Choose) button.
  ![Domain Name Availability](./img/domain-3.png)
- Complete the payment: Choose a suitable payment method and complete the purchase.
- Finish domain registration: Complete the registration process for your new domain.
- Wait for review: Please wait while your newly created domain is being reviewed.
  ![Domain Review](./img/domain-4.png)

### Connecting the Domain to Netlify:

- Open your Netlify project: Access your project on the Netlify platform. Click "Set up a custom domain" and enter the domain name you purchased.
  ![Set up Domain Netlify](./img/domain-5.png)
- Copy DNS records: Open the DNS configuration section on Netlify and copy all the DNS records provided.
  ![Netlify DNS Config](./img/domain-6.png)
- Open Niagahoster domain settings: Go back to the domain overview page on Niagahoster and click the "Change" button in the nameservers section.
  ![Change Nameservers](./img/domain-7.png)
- Paste DNS records: Paste the DNS records you copied from Netlify into the Niagahoster nameservers section. Click "Save".
  ![Change Nameservers with Netlify DNS](./img/domain-8.png)
- Wait for DNS update: Allow time for the external DNS on Netlify to update (this can take up to 24 hours).
- Access your website: Once the external DNS update is complete, your website should be accessible through the domain you entered.
  ![Access website with domain](./img/domain-9.png)

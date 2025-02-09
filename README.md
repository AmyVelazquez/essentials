# Essentials 

Updated February 9. 2025 by Amy Velazquez

This repo contains all the code for the 2 essential forms
- Contact Us
- Team Access

Along with the code, it provides explanations and resources on how all backend logic works.

## forms
The forms were recreated using the Zendesk API. The Contact Us and Team Access forms.
We no longer use the Need a Receipt form since Amy Velazquez updated the Zaps to collect all the data needed for the forms.


## Zapier
Zaps created in the backend handle purchasing essential products and handing form submission data for all three forms. You can find all zaps associated with essentials [here](https://zapier.com/app/zaps/folder/1804846)

## Podia
The main page (essentials.centercentre.com) is *not* hosted on our sites. It is hosted on Podia [here](https://app.podia.com/dashboard). The purpose of this page is to sell the essential products and handle payments.


## Servers
We host our code on [Plesk](https://dopractice.uie.com/smb/web/view). To update the code shown on the site, go down to the essentialscontact.centercentre.com subdomain on the list and click the git option. The git repo connected to this server is this repo. Push new code to this repo, pull the code in Plesk, then click deploy at the bottom of plesk page to update the website. Remember, these pages are different than our Podia page.

Web Developers: [@AmyVelazquez](https://github.com/AmyVelazquez)
Website: [https://essentials.centercentre.com/](https://essentials.centercentre.com/)
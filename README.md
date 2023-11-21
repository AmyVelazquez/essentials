# Essentials 

This repo contains all the code for the 3 essential forms
- Contact Us
- Request a receipts
- Team Access

Along with the code, it provides explanations and resources on how all backend logic works.

## formcrafts
[Formcrafts](https://formcrafts.com/dashboard/forms) was used to build the custom forms for all three contact pages above. You can log in and find each form on our dashboard page. The HTML code for the forms injects a form into the page with an external script from Formcrafts.

## Zapier
Zaps created in the backend handle purchasing essential products and handing form submission data for all three forms. You can find all zaps associated with essentials [here](https://zapier.com/app/zaps/folder/1804846)

## Podia
The main page (essentials.centercentre.com) is *not* hosted on our sites. It is hosted on Podia [here](https://app.podia.com/dashboard). The purpose of this page is to sell the essential products and handle payments.

When someone purchases a product on our podia page, the name of that product is sent to Zapier. **The name of this product must match EXACTLY what the condition flow names in Zapier are**

## Servers
We host our code on [Plesk](https://dopractice.uie.com/smb/web/view). To update the code shown on the site, go down to the essentialscontact.centercentre.com subdomain on the list and click the git option. The git repo connected to this server is this repo. Push new code to this repo, pull the code in Plesk, then click deploy at the bottom of plesk page to update the website. Remember, these pages are different than our Podia page.

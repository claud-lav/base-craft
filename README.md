# Craft CMS - base

## Installation Craft
1. Follow instructions in documentation to install craft https://craftcms.com/docs/5.x/install.html 
2. Add the folders and documents from above to your base installation

## Required Plugins 

Installations dashboard: 
- Craft Pro

Installations project terminal:
- SEO Matic -> ddev composer require "nystudio107/craft-seomatic:^5.1.2" -w && ddev craft plugin/install seomatic
- Formie -> ddev composer require "verbb/formie:^3.0.3" -w && ddev craft plugin/install formie
- Retour -> ddev composer require "nystudio107/craft-retour:^5.0.3" -w && ddev craft plugin/install retour
- ImagerX -> ddev composer require "spacecatninja/imager-x:^5.0.2" -w && ddev craft plugin/install imager-x
- Postmark adaptor -> ddev composer require "craftcms/postmark:^3.1.0" -w && ddev craft plugin/install postmark
- CKEditor -> ddev composer require "craftcms/ckeditor:^4.2.0" -w && ddev craft plugin/install ckeditor
- Vite -> ddev composer require "nystudio107/craft-vite:^5.0.1" -w && ddev craft plugin/install vite
- Sprig -> ddev composer require "putyourlightson/craft-sprig:^3.4.0" -w && ddev craft plugin/install sprig 

## Styling with live changes

1. Make sure vite is already installed 
2. Install sass -> npm install sass 
3. Install vite -> npm install vite
4. Install vite plugin --> npm install vite-plugin-restart
5. npm run dev
6. Check if in config/vite.php devServerPublic is same as current localhost endpoint

## Database

1. Install phpmyadmin for ddev ->  ddev get ddev/ddev-phpmyadmin
2. Restart ddev -> ddev restart
3. Open database -> ddev phpmyadmin 

## Templates 

- components -> reusable items such as buttons
- emails -> email templates 
- layouts -> html layouts 
- pages -> pages ans settings 
- partials -> sections 

## Web/assets 
files that client cannot add or remove 


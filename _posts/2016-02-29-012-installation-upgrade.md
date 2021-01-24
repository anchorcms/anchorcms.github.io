---
title: '0.12.* - Installation & upgrade'
excerpt: "Oh hey there! I'm guessing you want to know how to install the latest version of Anchor? No? Maybe you need to know how to update an existing Anchor blog? Well look no further than this post."
---

# 0.12.\* - Installation & Upgrade

_Oh hey there! I'm guessing you want to know how to install the latest version of Anchor? No? Maybe you need to know how to update an existing Anchor blog? Well look no further than this post._

**Installing 0.12.\***

This version of Anchor included many updates which make installation super easy. You have many options to choose from:

-   Download the release `.zip` [here](https://github.com/anchorcms/anchor-cms/releases)
    -   Requires you to run `composer install` in the root of the project.
-   Download the built release `.zip` here **(Coming soon)**
    -   This download does not require you to have composer installed on your machine.
-   Use composer to create a new project
    -   `composer create-project anchorcms/anchor-cms anchor 0.12.1` (Omit version for latest release)
-   Clone / Fork the [repository](https://github.com/anchorcms/anchor-cms)
    -   Requires you to run `composer install` in the root of the project.

Once you've got the Anchor folders setup, visit the installation via your browser and follow the install steps. Et Voila! You're set to go! If you had any problems installing this version of Anchor, please do not hesitate to submit an issue to our [repository.](https://github.com/anchorcms/anchor-cms/issues).

**Upgrading to 0.12.\***

Quite a few changes have been made since the last most stable release; `0.9.2`, especially in terms of the database. So it's best to ensure you've got everything backed up before you get started, and I certainly wouldn't recommend updating on a live site without testing first.

Download the latest release [here](https://github.com/anchorcms/anchor-cms/releases). Then copy all folders and files from the download except the `/content`, `/anchor/config` and `/themes` contents to replace your existing project. If you've added different languages, then be sure to not override those folders. Then copy `/anchor/config/migrations.php` from the download to your existing project. This will ensure Anchor updates your database to meet the required schema.

You will then need to go into your terminal, change your directory to the root of the anchor install and run `composer install`. If you do not have composer then please you will need to install it. Documentation can be found [here](https://getcomposer.org/doc/).

Visit your updated installation of Anchor in the browser; if everything went smoothly then your site should be functioning as normal. If you encounter any problems, then Anchor will log errors in `/anchor/errors.log`. If you're unable to resolve the issue and think it's a fault of Anchor's then please do not hesitate to submit an issue to the [repository](https://github.com/anchorcms/anchor-cms/issues).

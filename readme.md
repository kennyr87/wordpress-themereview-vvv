# A WordPress Theme Reviewers VVV

This is an [auto-sitesetup](https://github.com/Varying-Vagrant-Vagrants/VVV/wiki/Auto-site-Setup) designed to be used with [Varying Vagrants Vagrant](https://github.com/Varying-Vagrant-Vagrants/VVV) for reviewing WordPress.org themes.

## To get started:

1. Clone this branch of this repo into the `www` directory of your Vagrant as `www/theme-review`
2. If your Vagrant is running, from the Vagrant directory run `vagrant halt`
3. Followed by `vagrant up --provision`.  Perhaps a cup of tea or coffee now? The provisioning may take a while

Then you can visit [http://themereview.wordpress.dev](http://themereview.wordpress.dev) to start developing or reviewing themes.

## Dependencies
- [Varying Vagrants Vagrant](https://github.com/Varying-Vagrant-Vagrants/VVV) - [Installation guide](https://github.com/Varying-Vagrant-Vagrants/VVV#the-first-vagrant-up)
- [vagrant-hostsupdater](https://github.com/cogitatio/vagrant-hostsupdater) - Install with `vagrant plugin install vagrant-hostsupdater`

## What will happen?
- Install WordPress and import "Theme Unit Test Data"
- Install & activate "Developer"
- Install & activate "Theme Check"
- Install & activate "Theme Mentor"
- Install & activate "Theme Checklist"
- Install & activate "What The File"
- Install & activate "VIP Scanner"
- Install & activate "WordPress Database Reset"
- Install & activate "Toolbar Theme Switcher"
- Install "RTL Tester"
- Install "Pig Latin"

## Credentials and Such

### Theme Review
* Username: `admin`
* Password: `password`
* Login: [login](http://themereview.wordpress.dev/wp-admin)

### MySQL Root
* User: `root`
* Pass: `root`
* See: [Connecting to MySQL](https://github.com/varying-vagrant-vagrants/vvv/wiki/Connecting-to-MySQL) from your local machine

## Themes

If you drop a theme's `.zip` file into the root folder (not htdocs) provisioning will automatically install the theme ready for activation.

Yes, drop six zip files and all six themes will install automagically.
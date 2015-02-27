# Wordpress on Heroku

using with PHP/nginx + PostgreSQL + Memcached + Cloudinary + Sendgrid

[![Deploy](https://blog.logentries.com/wp-content/uploads/2014/09/deploy-to-heroku.png)](https://heroku.com/deploy?template=https://github.com/ya-s-u/wp-on-heroku/tree/production)


## One Click Installation *Totally Free
Register [Heroku account](https://signup.heroku.com/www-header) and [Verify your credit info](https://devcenter.heroku.com/articles/account-verification#verification-requirement), then Click this button:point_down:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/ya-s-u/wp-on-heroku/tree/production)

done...finish! :tada::tada::tada:


## Installation for Developers
Clone the repository

```
$ git clone git://github.com/ya-s-u/wp-on-heroku.git
```

Checkout branch

```
$ git checkout production
```

Remove ``wp-content/mu-plugins/force.php``

```
$ rm wp-content/mu-plugins/force.php
```

Develop!

Set config to Heroku, use [generator](https://api.wordpress.org/secret-key/1.1/salt/)

```
AUTH_KEY:                   xxxxxxxxxx
AUTH_SALT:                  xxxxxxxxxx
LOGGED_IN_KEY:              xxxxxxxxxx
LOGGED_IN_SALT:             xxxxxxxxxx
NONCE_KEY:                  xxxxxxxxxx
NONCE_SALT:                 xxxxxxxxxx
SECURE_AUTH_KEY:            xxxxxxxxxx
SECURE_AUTH_SALT:           xxxxxxxxxx
WP_CACHE:                   True
```

Deploy to Heroku

```
$ git push heroku production:master
```


## Contains

### 8-Addons
- Heroku Postgres
- PG Backups
- PostgreSQL Studio
- Sendgrid
- Cloudinary
- Memcached Cloud
- Newrelic
- Papertrail


### 25-Plugins
Default:Enable

- Batcache Manager
- Cloudinary
- Disable WordPress Core Updates
- Disable WordPress Plugin Updates
- Gigaom New Relic
- Google Analytics Dashboard for WP
- JP Markdown
- Memcached Cloud
- Resize images before upload
- SendGrid
- WordPress Gzip Compression
- WordPress HTTPS
- WordPress Importer

Default:Disable

- Acunetix Secure WordPress
- Akismet
- All In One SEO Pack
- Category Order and Taxonomy Terms Order
- Contact Form 7
- Google XML Sitemaps
- PuSHPress
- SyntaxHighlighter Evolved
- Ultimate TinyMCE
- WordPress Popular Posts
- WP-Optimize
- WP Social Bookmarking Light


### 10-Themes
- Hueman(http://alxmedia.se/themes/hueman/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/hueman/screenshot.png)

- Fukasawa(http://www.andersnoren.se/teman/fukasawa-wordpress-theme/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/fukasawa/screenshot.png)

- PORTFOLIO WORDPRESS THEME(https://www.gavick.com/wordpress-themes/portfolio,174)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/gk-portfolio/screenshot.png)

- Griffin(https://wordpress.org/themes/griffin/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/griffin/screenshot.png)

- Pure(http://www.gt3themes.com/wordpress-themes/pure/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/gt3-wp-pure/screenshot.png)

- Clippy(http://www.s5themes.com/theme/clippy/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/clippy/screenshot.jpg)

- DW Minion(http://www.designwall.com/wordpress/themes/dw-minion/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/dw-minion/screenshot.png)

- DW Timeline(http://www.designwall.com/wordpress/themes/dw-timeline/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/dw-timeline/screenshot.png)

- Bushwick(https://wordpress.org/themes/bushwick/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/bushwick/screenshot.png)

- ARCHITEKT(http://dessign.net/architekt-theme/)

![](https://raw.githubusercontent.com/ya-s-u/wp-on-heroku/production/wp-content/themes/architekttheme/screenshot.jpg)

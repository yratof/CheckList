# Coding Checklist

### So you think you've finished your website? Well, that might be the case, but just run through this list to make sure you've covered everything. And I mean everything.

---

## Bit by Bit

---

### Header

#### Desktop

- **Main Elements**
	- Does the header match the design on a desktop computer?
	- Is the logo .svg? Does it have a .png fallback?

- **Navigation**
	- Does the navigation fit inline?
	- Do links have a :hover state?
	- Did you check the :visited state?
	- Do the Drop Downs

#### Tablet

	Does the header match the design on a Tablet?


#### Mobile

	Does the header match the design on a Mobile?


### Footer



### Copy


---

## Responsive Design
If you've been given the designs, they should match almost exactly. The exceptions would come with font-rendering.

---

### Test for Desktop Layout

	Desktop view is roughly 1040px and higher in width

### Test for Tablet Layout, Both Orientations

	Test the code against the layout, move the browser ~100px+- each direction

### Test for Mobile Layout, Both Orientations

	Check everything is lined up.

### Test for height issues

	Sometimes, height can be an issue, make sure that fonts and line-heights are accommodated for when the browser isn't tall.
	
---

## Browser Testing

---

Browser testing needs to span from Mac to PC, as both render differently.

* Does it seem right in Chrome?
* Does it seem right in Firefox?
* Does it seem right in Safari?
* Does it seem right in Internet Explorer 8 / 9 / 10 / 11?
* Does it seem right in Opera?

## Device Testing

* Does it seem right on iPhone 5/5s - 3gs?
* Does it seem right on iPad / Mini?
* Does it seem right on Samsung Galaxy?
* Does it seem right on Nexus?

---

## Crawling the site for errors

---

[Feed The Bot](http://www.feedthebot.com/) - This will highlight any SEO and crawling issue that you might have relating to the site.

[Nibbler](http://nibbler.silktide.com/) - This will rate your site

[Facebook Debug](https://developers.facebook.com/tools/debug) - Check what Facebook sees when a page is shared
---

## Optimize
The server has PageSpeed built into it now, so your assets will be served as a compressed / cached version of itself. If you run into any issues, put this [PageSpeed off Gist](https://gist.githubusercontent.com/yratof/11248706/raw/82decc84cd960fcf7bcf425a8386b679f514ed63/.htaccess) in your **.htaccess** file.

---

* Check load times

	- [Pagespeed](http://developers.google.com/speed/pagespeed/insights/), [Yslow](https://developer.yahoo.com/yslow/) and [GTmetrix](http://gtmetrix.com/) are great places to start


* Reduce HTTP requests by combining assets

		You don't need to call 20 style sheets on your site when you can use just the one stylesheet. The same goes with Google Webfonts. You don't need to call them all individually when you can call them all together as one.

* Optimise images with **ImageMagick Plugin**
* Compress JS and SCSS with CodeKit 2

		Ideally, Strip out comments and line breaks using the compression methods in CodeKit 2. Compressed is the ideal output from CK2. 


---

## Website Properties and Assets

---

### Favicon

	<link rel="icon" type="image/x-icon" href="/favicon.ico" />
	<link rel="icon" type="image/x-icon" href="/favicon.png" />

### Apple touch icon

	<link rel="apple-touch-icon" href="/favicon.png" />

### Windows 8 Tile

	<meta name="msapplication-TileImage" content="pics/logowin8pin.png"/>
	<meta name="msapplication-TileColor" content="#ffffff"/>

---

## Pre-Search Engine Optimisation 

---

### Different Title on every page

	<title>10 Things To Consider When Choosing The Perfect CMS | How-To | Smashing Magazine</title>

### Meta Description on every page

	<meta name="description" content="By Paul Boag Choosing a content management system can be tricky. Without a clearly defined set of requirements, you will be seduced by fancy functionality that you will never use. What then should you look" />

---

## Copywriting + Content

---

* Proofread spelling and capitalisations
* Check spellings
# ### * Search for Demo Text like Lorum Ipsum.

---


Check Links Work

http://www.screamingfrog.co.uk/seo-spider/
Test Contact Forms

Test with javascript turned off

Test valid html

http://validator.w3.org
Common issues

<!--[if (IE 8)&!(IEMobile)]><meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"><![endif]-->

RSS link for blog

Place between tags
<link rel="alternate" type="application/rss+xml" title="Site or RSS title" href="link-to-feed" />

Check xml site map in root

http://www.xml-sitemaps.com/ for static sites, ensure url is www.mydomain.com/sitemap.xml.
For wordpress install a plugin
Check analytics and webmaster tools are installed and linked and that you have submitted your site map.

http://www.bing.com/toolbox/submit-site-url Defensive design
404 Page with a link to homepage or other page suggestions
Error handling on forms, give the user enough information to fix their own problems.


### Backups + IWP Plugin

* backupbuddy
* Security

bad behaviour plugin
SSL certificate
Print Style Sheet

<link rel="stylesheet" type="text/css" href="print.css" media="print" /> Ensure no test content

* lorem ipsum
* test links
* tagline (WordPress Mainly)
* Alt tags on images

* Blank if no wording or a decorative image but needs to be there.
* Canonical domain issues
* Only one H1 tag on each page
* Social media links
* Check non designed pages look ok, such as author pages and category pages if using wordpress
* Check dates represented are in english format

* Check padding on forms
sitemap-xml-for-github
======================

If you host your jekyll based website/blog in GitHub, this sitemap would be useful to you.  

I don't need to re-iterate the importance of having a sitemap xml for your website. There are lot of jekyll plugins out there, which generates the sitemap xml for your jekyll website. However, custom plugins are disabled in GitHub.  

This repo has an xml file "sitemap.xml". Simply copy this file to your github repo. That's all is needed to have a sitemap.xml for your website.  

This xml uses Liquid Tags to generate the sitemap.xml (supported in GitHub)  

### Pre-requisites

You may have to add the date tags to all the pages in your website (basically any page that you need to be present in this xml file).  

### Example

<div>
---<br/>
layout: default<br/>
date: 2013-12-12 00:00:00 +0530<br/>
---<br/>
</div>

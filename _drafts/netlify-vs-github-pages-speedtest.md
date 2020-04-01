---
layout: post
title: Netlify vs Github Pages Speedtest
author: Rahul
categories: blogging
comments: false
image: assets/images/webdesign.jpg
---
Netlify one of the most popular choice among those looking to host a static website. Github pages is a free static site hosting service offered by the largest git service Github. Both are popular among those looking to host a static site. Both are excellent and responsive and provide a great hosting solution. Today we are going to find out among the two which is the fastest. Speed is one of the factors considered by the search engine on ranking. And also it is said that a large number of people will exit the site if the site does not load under 3 seconds. In this article we are going to compare both Github pages and Netlify on the basis of their speed.

<h3>Our Test Conditions</h3>

We set up a two identical websites on github pages and netlify. In fact both of them were deployed from the same github repository. The site was built using the static site generation Jekyll. We installed the mediumish theme on our test site. The theme already had a few posts built in complete with images. This helped us to simulate a real word scenario. The size of the webpage was around 1.9 MB. So the average size. There was a good number of css and js files on the webpage. We took multiple runs to minimize error and also to give the cdn time to cache resources. Because usually the first one or two requests will be cache miss as the cdn cache will be probably expired. But after a few visits everything will start to get served from the cdn.

Services we used for the speed test are given below. 

<ul>
  <li> Inspect option in Google Chrome</li>
  <li> <a href="https://tools.pingdom.com">Pingdom Tools</a> </li>
  <li> <a href="https://gtmetrix.com">GTmetrix</a></li>
  <li> <a href="https://www.dotcom-monitor.com">dotcom-monitor</a>  </li>
  <li> <a href="https://www.dareboost.com/en/tool/website-speed-test">Dareboost</a></li>
  <li> <a href="https://www.webpagetest.org/">Webpage Test</a></li>
  <li> <a href="https://tools.keycdn.com/speed">Keycdn Speed Test</a></li>
  
</ul>







<img src='{{site.baseurl}}/assets/images/plugin.jpg'>


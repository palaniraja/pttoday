pttoday (Paper)
===============

It is very rare I follow local news. But I usually have a phase where I interested in news for about a week. And everytime, I tried to read online daily news from my region, I always hate their website. 

There are about only few variety of CMS sold to every news organizations. And they all suck, very old technology like people still require flash to be installed to read their news paper. And the layout is always a mess. Remember [Flipboard] (https://en.wikipedia.org/wiki/Flipboard) has been released in Jul'2010 and still the local newspapers layouts are mess.

After in about two days I start to check their backend from the page navigations and wondered if someone can build a nicer/easier way to read the news. And this happens **everytime**.

I'm grouping this project to list all my related stuff


---
####27-Jan-2014


###புதிய தலைமுறை இன்று

http://palaniraja.com/pttoday

A simple HTML page to list all their high-res jpg images of their _daily_ in one page; without any Flash plugin so you can read from mobile. 

**Update (2017):** This project does **not** work anymore, as those pages require a signin. And I don't follow them anymore. 

---
####07-Feb-2017
###Dinakaran - தினகரன்

React Native based android app which lets you browse their _daiy_.

## Demo (video):

[![Android app demo](https://img.youtube.com/vi/A2Z24uHMNVA/0.jpg)](https://www.youtube.com/watch?v=A2Z24uHMNVA)


<iframe width="560" height="315" src="https://www.youtube.com/embed/A2Z24uHMNVA" frameborder="0" allowfullscreen></iframe>

[Download APK](https://goo.gl/xNgkAJ )

---


### Dinamalar

<a href="javascript:(function()%7Bvar%20imgs%20%3D%20%5B%5D%3B%24('%23newslider%20li.animated%20%20div%5Bonclick*%3D%22openArticle(%5C'AT').each(function(e%2C%20i)%7Bvar%20mthd%20%3D%20%24(this).attr('onclick')%3Bconsole.log(mthd)%3Bvar%20mthd2%20%3D%20mthd.split(%22%2C%22)%3Bconsole.log(mthd2)%3Bconsole.log(mthd2.length)%3Bvar%20aId%20%3D%20mthd2%5B1%5D.replace(%22'%22%2C%20%22%22)%3Bconsole.log(aId)%3B%2F*%2F%2F%20console.log(typeof%20aId)%3B%2F%2F%20var%20rg%3D%20%2F%5E(%5Cd%7B2%7D)(%5Cd%7B2%7D)(%5Cd%7B4%7D)(%5Cd%7B3%7D)(%5Cd%7B3%7D)%24%2Fg%3B%2F%2F%20var%20assetComponent%20%3D%20rg.exec(aId)%3B%2F%2F%20console.log(assetComponent)%3B%2F%2FassetComponent%5B1%5D%3B%2F%2FassetComponent%5B2%5D%3B%2F%2FassetComponent%5B3%5D%3B%2F%2FassetComponent%5B4%5D%3B%2F%2FassetComponent%5B5%5D%3B*%2Fvar%20dt%20%3D%20aId.substr(0%2C2)%3Bvar%20mn%20%3D%20aId.substr(2%2C2)%3Bvar%20yr%20%3D%20aId.substr(4%2C4)%3Bvar%20pg%20%3D%20aId.substr(8%2C3)%3Bvar%20at%20%3D%20aId.substr(11%2C3)%3Bvar%20url%20%3D%20'http%3A%2F%2Fepaper.dinamalar.com%2FPUBLICATIONS%2FDM%2FDINAMALAR%2F'%2Byr%2B'%2F'%2Bmn%2B'%2F'%2Bdt%2B'%2FArticle%2F%2F'%2Bpg%2B'%2F'%2Bdt%2B'_'%2Bmn%2B'_'%2Byr%2B'_'%2Bpg%2B'_'%2Bat%2B'.jpg'%3Bimgs.push(url)%3Bconsole.log(url)%3B%7D)%3Bfunction%20srcToImgTag(src)%7Breturn%20'%3Cimg%20src%3D%22'%2Bsrc%2B'%22%20%2F%3E%3Chr%20%2F%3E'%3B%7Dvar%20imgtag%20%3D%20imgs.map(srcToImgTag)%3Bconsole.log(imgtag)%3Bvar%20wnd%20%3D%20window.open(%22about%3Ablank%22%2C%20%22%22%2C%20%22_blank%22)%3Bwnd.document.write(imgtag)%7D)()"/> Dinamalar Bookmarklet</a>

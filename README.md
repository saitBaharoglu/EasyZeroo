# EasyZeroo
In Turkey, and some other countries, **wikipedia.org** is prohibited, a simple JS code can solve the problem by redirecting to **wikizeroo.org**.

# HOW IT WORKS?
This solution uses chrome bookmark to create a bookmark which executes a **JS** code.
- Go **google** any subject, with ending your search with "**Wiki**" keyword
- Click **EasyZero** bookmark, it will find the first wikipedia.org in the page, redirecting it to wikizeroo.org, 
- Please find the page :)

# HOW TO INSTALL?
1) There is two simple way to get EasyZero: 
2) create a new bookmark in Google Chrome, (simply by clicking on the start symbole on the right of the link bar)
3) click '**more**' option
4) Name our Bookmark: "**EasyZeroo**"
5) write the following in the **URL** field:
```js
javascript: !function(){let e=document.getElementsByTagName("a");for(let i of e){let e=i.getAttribute("href");if(e&&e.includes("wikipedia.org")){window.location.replace(e.replace("wikipedia","0wikipedia"));break}}}();
```
6) Click "**done**"

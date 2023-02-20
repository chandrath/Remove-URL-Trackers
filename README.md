<h1 align="center">
  <br>
  <a href="https://github.com/chandrath/Remove-Tracking-Parameters-Bookmarklet"><img src="https://cdn-icons-png.flaticon.com/512/2899/2899445.png" alt="Markdownify" width="200"></a>
  <br>
  Remove Tracking Parameters
  <br>
</h1>

<h5 align="center">This bookmarklet removes tracking parameters from URLs, which can be useful if you want to share a link without the tracking parameters. Please note that the bookmarklet requires user interaction to remove the parameters. After the webpage has loaded, you can simply click on the bookmarklet, and it will remove the tracking parameters from the URL.</h5>

 

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://raw.githubusercontent.com/chandrath/Remove-Tracking-Parameters-Bookmarklet/src)

## Key Features

* Removes tracking parameters from URL
  - This bookmarklet removes tracking parameters from URLs, which can be useful if you want to share a link without the tracking parameters. 
  
  Please note that the bookmarklet requires user interaction to remove the parameters. After the webpage has loaded, you can simply click on the bookmarklet, and it will remove the tracking parameters from the URL.
  
  For example, if you encounter a URL like this:
```
https://www.example.com/?utm_source=google&utm_medium=cpc&utm_campaign=summer_sale
```
You can click on the bookmarklet, and it will remove the tracking parameters like this:
```
https://www.example.com/
```

## How To Use

1. Open your web browser and create a new bookmark by pressing Ctrl + D (Windows) or Command + D (Mac).

2. Edit the name of the bookmark to something like "Remove Tracking Parameters".

3. In the URL or location field of the bookmark, copy and paste the following code:

```
javascript:location.href=location.href.replace(/[?&]utm_[^&]+/gi,"");

```
- or You just drag the bellow button to the bookmark bar of your browser.

<a href='javascript:(function(){location.href=location.href.replace(/[?&]utm_[^&]+/gi,"");})();' style='padding: 8px 12px; border: 1px solid #24292e; border-radius: 4px; background: linear-gradient(45deg, #405de6, #5851db, #833ab4, #c13584, #e1306c, #fd1d1d); color: #fff; text-decoration: none;'>Remove Tracking Parameters</a>






> **Note**
> Please note that some websites may require these parameters to function properly, so use this bookmarklet with caution. If you have any feedback or suggestions, please let me know!



## You may also like...

- [Collection](https://github.com/chandrath?tab=repositories) -

## License

MIT

---

> GitHub [@chandrath](https://github.com/chandrath) &nbsp;&middot;&nbsp;
> Twitter [@chandrath](https://twitter.com/chandrath)


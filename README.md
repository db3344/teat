---
Title: Set Wallpaper For C2 Projects
Description: Set an image within the application cordova as wallpaper.
---


##Usage
###Function(s)
####setImage
Sets image under given path as systems background image:
```javascript
window.plugins.wallpaper.setImage(string /* image path */);
```

#####Notes
 - path must not start with bar
 - path has not to start with backslash

#####Example
```javascript
window.plugins.wallpaper.setImage("img/mybackground.jpg");
```

---

####setImageHttp
Sets image from url as background image:
```javascript
window.plugins.wallpaper.setImageHttp(string /* url */);
```

#####Example
```javascript
window.plugins.wallpaper.setImageHttp("https://example.com/image.jpg");
```

---

####setImageBase64
Sets image contained in Base64 string as systems background image:
```javascript
window.plugins.wallpaper.setImageBase64(string /* Base64 string */);
```

#####Example
```javascript
window.plugins.wallpaper.setImageBase64(base64);
```

##License
The plugin is licensed under Apache 2.0.
The Apache 2.0 license can be found in the root directory of this project as well as the projects NOTICE.

##Supported Platforms
- Android

# **[r00m.chat](https://r00m.chat)** for developer


## Basic Usage
```html
<body>
  ...
  
  <script src="https://r00m.chat/plugin/web/v1.0/bundle.js"></script>
  <script>
    r00m.chat();
  </script>
</body>
```
[demo](https://r00m.chat/static/developer/demo/basic-usage.html)


## Methods
```javascript
r00m.open();

r00m.close();

r00m.toggle();
```
[demo](/test/index.html)


## Options
```html
<body>
  ...
  
  <script src="https://r00m.chat/plugin/web/v1.0/bundle.js"></script>
  <script>
    r00m.chat({
      nickname: '',
      room: '',
      secretKey: '',
      theme: 'dark',
      width: '340px',
      height: '520px',
      zIndex: 5,
      position: 'bottom-right',
      mobileFullSize: true,
    });
  </script>
</body>
```
[demo](https://r00m.chat/static/developer/demo/basic-usage-options.html)


## Custom iframe
```html
<body>
  ...
  
  <iframe id="my-iframe"></iframe>
  
  <script src="https://r00m.chat/plugin/web/v1.0/bundle.js"></script>
  <script>
    r00m.chat({
      iframe:{
        id: "my-iframe",  //required!!!
        theme: 'dark',
        backgroundColor: '',
        nickname: '',
        room: '',
        secretKey: '',
      }
    });
  </script>
</body>
```
[demo 1](https://r00m.chat/static/developer/demo/custom-iframe-1.html)

[demo 2](https://r00m.chat/static/developer/demo/custom-iframe-2.html)

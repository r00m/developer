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

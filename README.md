# cso-fe
 
## build
```sh
npm run build
git add .
git commit -m "add v1.1.3"
git push
git tag 1.1.3
git push origin --tags  
```

```html
    <link rel="stylesheet" 
      href="https://cdn.jsdelivr.net/gh/puyab/cso-fe@main/dist/1.1.4/csoeventi-ui-style.min.css">

      <div id="csoeventi-ui"></div>
       <script src="https://cdn.jsdelivr.net/gh/puyab/cso-fe@main/dist/1.1.4/csoeventi-ui.min.js"></script>
      <script>
        window?.addEventListener("load", function () {
          CsoeventiUi.init({
            version: 'latest',
            url:"https://api.csoeventi.com",
            debug: true,
            id:"csoeventi-ui",
            siteKey: 'GPhSg9FOpFaxS2Sg9yogFaxMrT2KSd3ed',
          });
        });
      </script>

```
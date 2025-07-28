# cso-fe
 
## build
```sh
npm run build
git add .
git commit -m "add v1.0.9"
git push
git tag 1.0.9
git push origin --tags  
```

```html
    <link rel="stylesheet" 
      href="https://cdn.jsdelivr.net/gh/puyab/cso-fe@main/dist/1.0.9/csoeventi-ui-style.min.css">

      <div id="csoeventi-ui"></div>
       <script src="https://cdn.jsdelivr.net/gh/puyab/cso-fe@main/dist/1.0.9/csoeventi-ui.min.js"></script>
      <script>
        window?.addEventListener("load", function () {
          CsoeventiUi.init({
            version: 'latest',
            debug: true,
            id:"csoeventi-ui",
            siteKey: 'VOSxaOmK-2025-NlQF-XRPe-0117175813311',
          });
        });
      </script>

```
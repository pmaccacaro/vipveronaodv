# Runbook

Doc Template Ananke: https://themes.gohugo.io/themes/gohugo-theme-ananke/

```bash
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
```

Check that you have checkout the ```themes/ananke```

Folder is set as submodule in ``` .gitsubmodules ```

Checkout the code in the submodule from the root of the project:
``` 
git submodule  update --init --recursive
```

Build the site with:
```
HUGO_ENV="production" hugo
```

Upload the content of the generated folder ```public``` to the ```root``` folder on aruba hosting
inside the folder ```www.vipverona.org```

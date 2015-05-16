![alt text](https://github.com/zemiotic/swan/blob/master/images/logo.png "Swan - User Interface")

Experimental UI framework based on Genomic Design methodology. Work in progress... 


```
Genomic Design System
–––––––––––––––––––––––––––––
core -> modules -> layout
–––––––––––––––––––––––––––––

Sass Architecture v0.2 (Alpha)

sass/
|
|– core/
|   |– native/             # Native libraries
|   |– vendor/             # Vendor libraries
|   |– _core.scss          # CORE Package
|
|– modules/
|   |– url-manager/        # Url Manager Module
|   |– color-manager/      # Color Manager Module
|   |– typo-manager/       # Typo Manager Module
|   |– icon-manager/       # Icon Manager Module
|   |– button-manager/     # Button Manager Module
|   |– scroll-manager/     # Scroll Manager Module
|   |– your-module/        # Your custom module
|   |– _modules.scss       # MODULES package
|
|– layout/
|   |– patterns/           # Common layout Patterns
|   |– templates/          # Final Templates
|   |– _layout.scss        # LAYOUT Package
|
| -------------------------------------------------
`– styles.scss             # SWAN Package
  -------------------------------------------------
```



# Build project docs with MkDocs

- Learn & Build project documentations with [MkDocs](https://www.mkdocs.org/) 

- Hey ya, visit my [First Docs](https://laithoura.github.io/learn-mkdocs/) if you have no task to do :rofl:   

  ![Page Not Found](readme/home.png)

## Prerequisite
- [Download Python](https://www.python.org/)
- [Install Python Guide](https://www.mkdocs.org/user-guide/installation/)
- [Install MkDocs Guide](https://www.mkdocs.org/getting-started/)

## Installation:
1. `git@github.com:laithoura/learn-mkdocs.git` - clone the project to your local
2. `cd learn-mkdocs` - go to root project
3. `mkdocs serve` -  Start the live-reloading docs server
4. `mkdocs build` - Build the documentation site
5. `mkdocs gh-deploy` - build & push your project docs into gh-pages branch and deploy it to [GitHub Pages](https://pages.github.com/).

## Configuration
- Before we deploy the project on local or [GitHub Pages](https://pages.github.com/), we need to change below configuration accordingly.
1. Configure Site URL:
    - open `mkdocs.yml`
   1. DEV
      ```
      site_url: http://127.0.0.1:8000/
      ```
   2. PROD
      ```
      site_url: https://laithoura.github.io/learn-mkdocs/
      ```
2. Configure Custom Resources Relative Path:  
   - Open `mkdocs.yml`
   1. DEV
      ```markdown
      extra:
          version: 0.13.0
          contextPath: "/"
      ```
   2. PROD
      ```markdown
      extra:
          version: 0.13.0
          contextPath: "/learn-mkdocs/"
      ```
   -  **Result:** 
      ```markdown
      extra:
          version: 0.13.0
          contextPath: "/learn-mkdocs/" # Dev="/"; PRD="/learn-mkdocs/"
      ```
3. Configure extra css/js version

- Whenever you modify any line of code within `docs/css` or `docs/js`, you have to increase its version in `mkdocs.yml` file to avoid css/js caching issue on client browsers.
- Open `mkdocs.yml`
  ```markdown
  extra_css:
      - css/custom.css?v=1.0.0 # Eg: v=1.0.1; v=1.0.2
      - ...
      - ...
  
  extra_javascript:
      - js/custom.js?v=1.0.0 # Eg: v=1.0.1; v=1.0.2
      - ...
      - ...
  ```

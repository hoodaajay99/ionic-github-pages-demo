# Demo of Hosting or Deploying ionic 4 app on GitHub pages

> Github pages allows you to host static websites and web apps for free using the same workflow you use to host repositories, you just commit and push. Build and Deploying of static website to GitHub Pages can be automated. You can even associate a custom top level domain name to your website or web app by adding a CNAME file.

# Prerequisites

- Ionic requires latest Node.js version
  - To check your version, run node -v in a terminal/console window.
  - To get Node.js, go to https://nodejs.org
- npm package manager
  - To check your version run npm -v in a terminal/console window
  - Install npm client - https://docs.npmjs.com/cli/install
  
# Install Ionic

```
npm install -g ionic
```
> The -g option means install globally.

# Start an app

Create an Ionic app using one of the pre-made app templates, or a blank one to start fresh. 

```
$ ionic start ionic-github-pages-demo tabs
✔ Preparing directory ./ionic-github-pages-demo - done!
✔ Downloading and extracting tabs starter - done!
...
```

# Run the App

```
$ cd ionic-github-pages-demo/
$ ionic serve

> ng run app:serve --host=localhost --port=8100
[INFO] Development server running!
       Local: http://localhost:8100
```










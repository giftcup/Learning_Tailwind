# TailwindCSS

## Installation

- To install tailwind, firstly we need to download node. This can be done on ubuntu using the following command:

```
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -

sudo apt-get install -y nodejs
```
The different version and different installation processes can be found here: <a> https://github.com/nodesource/distributions/blob/master/README.md </a>

- Next up, install tailwindcss, the postcss plugin and autoprefixer which adds vendor prefixes automatically to the css. Use the command

```
npm install -d tailwindcss@latest postcss@latest autoprefixer@latest
```

This creates a <i>node_modules</i> folder, <i>package.json</i> and <i>package-lock.json</i>

- Create the configuration file using

```
npx tailwindcss init
```

This creates a tailwind.config.js file.
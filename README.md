# Blank plugin template

To create your own plugin, you can fork this template.

Then run

```
npm install
```

and start coding in src/index.js :wink:

When you're ready to publish, change `beloader_blank` in package.json
and webpack.conf/build.js (optionnaly in webpack.conf/dev.js) to your
plugin name.

Then run

```
npm run prepub
```

That will trigger build, tests and documentation.

You can then publish to NPM or configure Travis CI and semantic-release to auto-publish.
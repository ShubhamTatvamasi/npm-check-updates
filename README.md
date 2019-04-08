# npm-check-updates

To update to a new major version all the packages, install the npm-check-updates package globally:
```
npm install -g npm-check-updates
```

then run it:
```
ncu -u
```

this will upgrade all the version hints in the package.json file, to dependencies and devDependencies, so npm can install the new major version.

You are now ready to run the update:
```
npm update
```

If you just downloaded the project without the node_modules dependencies and you want to install the shiny new versions first, just run
```
npm install
```

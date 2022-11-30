# node-ir Intermmediate Result
A NodeJS CLI implementation using some new concepts to test them in the wild and see if developers like it. 

It is NodeJS + Rollup + Typescript + Atomic Sync ESM Loader Workers + npm exec / npm install / npm workspaces + PNP Packages 

It mainly allows you to run and compose software without creation of additional package.json and entrypoint.js files
while you can easy if all works create such files. 

It is also usefull for all kind of fast install operations that depend on conditional packages. 


## Usage
Load and run something
```
noder -p npm:specifier -p npm:specifierOther -i specifierOther/entry-inject.js my-entry-from-unmodified-3th.js 
```


## Build

## Bootstrap 3 for Meteor
Modular, configurable, customizable.

## How to use
In your Meteor project, create a file named `bootstrap-settings.json` and place it in any client folder.

The package will automatically populate the file if it is empty.

### bootstrap-settings.json
#### `less`
`customVariables` **Boolean** (default: *false*)  Enable this to expose a custom bootstrap variables file you can edit.  
`exposeMixins` **Boolean** (default: *false*)  Enable this to expose an importable less file with the bootstrap mixins for your use.  
`compile` **Boolean** (default: *true*)  Disable this to expose the raw bootstrap less and leave it to the less package to compile.  
`modules` **Object**  Enable or disable specific bootstrap less modules. *(The listed order of these is unimportant)*

#### `javascript`
`expose` **Boolean** (default: *false*)  Enable to expose the raw bootstrap javascript.  
`modules` **Object**  Enable or disable specific bootstrap js modules. *(The listed order of these is unimportant)*

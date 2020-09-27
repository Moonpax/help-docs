# TypeScript Commands

`tsc --init` init with tsconfig.json files

`tsc` compile all typescript files

`tsc app.ts` compile typescript file

`tsc -w` watch typescript files is changed

`tsc -v` show typescript version

### tsconfig.json

`"outDir": "./dist"`

> Redirect output structure to the directory.

`"rootDir": "./src"`

> Specify the root directory of input files. Use to control the output directory structure with --outDir.

`"removeComments": true`

> Do not emit comments to output.

###### COMPILER: exclude | include | files

"exclude": [
"./module.ts"
]

"include": [
"./src/**/*"
]

"files": [
"./module.ts"
]

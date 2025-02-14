How to use *watch mode* on your entire Typescript project (not just your app.js file),
we can navigate to the project directory (in the terminal) and enter: 

`tsc --init`

This will create a tsconfig.json file

Then we can run:

`tsc`

Which will compile .js files for all our .ts files

Now, we can run:

`tsc --watch` OR (for short) `tsc -w`

This means that every time we make a change in any of our .ts files, when we save the file, it will recompile and run all the javascript.

### In this section we also cover:
- Compiling the entire project (multiple files)
- Setting a compilation target
- Understanding Typescript Core Libs
- Working with source maps
- rootDir and outDir
- Stop emitting files on compilation errors
- Strict compilation
- Code quality options
- Debugging with VS Code

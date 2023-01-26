**1. What is NPM? What does it do? Why is it an important tool?**

NPM stands for Node Package Manager. It is an open-source software registry that contains JavaScript code packages. Developers can use it to install packages, which are collections of code, to use in their projects. It is the largest software registry in the world, and many applications have been built with the help of NPM. 

**2. What problems does NPM solve?**

It allows developers to easily manage dependencies in their projects. It also helps with reusability, since developers can easily share and reuse code by publishing packages to the npm registry. It also clearly 

**3. Describe the 3 main parts of NPM.**

- NPM is a command line tool. It can be used in the terminal to install and uninstall packages as well as run scripts.
- NPM is a registry. It is a database of JavaScript software.
- NPM is a website. You can use the website the browse packages and customize your npm experience. 


**4. What is the package.json file?**

When you install an npm package, a package.json file will generate. It contains some metadata about the project such as name and version. It also lists the dependencies and their versions needed for the project, and scripts that can be run in the command line. 

**5. What is the scripts section of the package.json file? How do you use it? What are the default commands, and how do you use your own?**

The scripts section is a field that lists scripts that can be run in the command line. The default commands are "test" and "start." Running "npm test" in your terminal will run your project through test cases. Running "npm start" in the terminal starts the project. 

All these scripts can be customized to fit your needs, and you can also write your own custom scripts. You can run these scripts by running "npm run" and the name of your custom script.

**6. What are dependencies? What does this section define? What are dev dependencies? Why is it important to define dev dependencies vs dependencies?**

In the package.json file, there is a section for dependencies, which are the packages that the project relies on to run. There are two types of dependencies: The dependencies are the packages that the project requires in order to run, and the dev dependencies are the packages that are only needed when developing the project. These can be build tools, test frameworks, etc.

**7. How do you install dependencies? Where do dependencies get installed?**

One way to install a dependency is to run "npm install" in the terminal. When that command is run, it will install all the dependenices listed in the package.json file. If you want to install a specific dependency, you can run "npm install <package_name>" in the terminal. 

The files for the downloaded dependecies will be installed in the node_modules folder.

**8. When running scripts with NPM, where does NPM look (path) for the dependencies of those scripts?**

NPM will look for the dependencies of the scripts in the nodes_modules folder. If it doesn't find it there, it will look in its parent directory, and will keep going up the directories until it is found. If its not found, it will install the package in the node_modules directory.

**9. Name 3 NPM commands, and why they are important.**

- "npm init": It creates a new package.json file and prompts you provide information about the project such as your project name, version, description, etc. 

- "npm update": updates all the dependencies listed in the package.json file to their lastest version. Important to keep things up to date.

- "npm run <script_name>": runs a specific script defined in the package.json file.



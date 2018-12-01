# Project Struction

## Introction

> `FETP` need to follow project struction rules。

`FETP` project contain a subfolder：

* `src`: source code directory, all source code in current project 

So, ensure our source code not be modified in Development and Production Mode.

Then, `FETP` contains other files (order by importance):

* `.gitignore`：Git repo ingore list. (necessary)
* `README.md`：project descrption file. (necessary)
* `.editorconfig`：editor format config
* `FETP.config.js`：FETP configuration file
* `package.json`：node modules manager file
* `eslintConfig`：ESLint configuration file. config in `package.json` 
* `eslintIgnore`：ESLint ingore list file. config in `package.json`

## Project Struction


````
project/                   // root path
├── node_modules/          // node local modules
├── src/                   // source code (necessary)
├── .gitignore             // git ignore list (necessary)
├── .editorconfig          // editor format config
├── fetp.config.js         // FETP config file
├── package.json           // node modules manager file
└── README.md              // project descrption file (necessary)
````


## Source Code（src/） Directory Struction


````
src/                   // src directory
├── component/         // Component directory, storage common components
├── css/               // Style directory, storage *.scss style files 
├── html/              // Page directory, storage static html files
├── img/               // Image directory, storage static resource files
├── module/            // Module directory, storage project modules
└── index.js           // entry point
````

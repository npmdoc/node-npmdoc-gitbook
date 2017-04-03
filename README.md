# api documentation for  [gitbook (v3.2.2)](https://www.gitbook.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-gitbook.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gitbook) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gitbook.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gitbook)
#### Library and cmd utility to generate GitBooks

[![NPM](https://nodei.co/npm/gitbook.png?downloads=true)](https://www.npmjs.com/package/gitbook)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gitbook/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gitbook_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gitbook/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gitbook/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gitbook/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "FriendCode Inc.",
        "email": "contact@gitbook.com"
    },
    "bin": {
        "gitbook": "./bin/gitbook.js"
    },
    "browser": "./lib/browser.js",
    "bugs": {
        "url": "https://github.com/GitbookIO/gitbook/issues"
    },
    "contributors": [
        {
            "name": "Aaron O'Mullan",
            "email": "aaron@gitbook.com"
        },
        {
            "name": "Samy Pessé",
            "email": "samy@gitbook.com"
        }
    ],
    "dependencies": {
        "bash-color": "0.0.4",
        "cheerio": "0.20.0",
        "chokidar": "1.5.0",
        "cp": "0.2.0",
        "cpr": "1.1.1",
        "crc": "3.4.0",
        "destroy": "1.0.4",
        "direction": "0.1.5",
        "dom-serializer": "0.1.0",
        "error": "7.0.2",
        "escape-html": "^1.0.3",
        "escape-string-regexp": "1.0.5",
        "extend": "^3.0.0",
        "fresh-require": "1.0.3",
        "front-matter": "^2.1.0",
        "gitbook-asciidoc": "1.2.2",
        "gitbook-markdown": "1.3.2",
        "gitbook-plugin-fontsettings": "2.0.0",
        "gitbook-plugin-highlight": "2.0.2",
        "gitbook-plugin-livereload": "0.0.1",
        "gitbook-plugin-lunr": "1.2.0",
        "gitbook-plugin-search": "2.2.1",
        "gitbook-plugin-sharing": "1.0.2",
        "gitbook-plugin-theme-default": "1.0.6",
        "github-slugid": "1.0.1",
        "graceful-fs": "4.1.4",
        "i18n-t": "1.0.1",
        "ignore": "3.1.2",
        "immutable": "^3.8.1",
        "is": "^3.1.0",
        "js-yaml": "^3.6.1",
        "json-schema-defaults": "0.1.1",
        "jsonschema": "1.1.0",
        "juice": "2.0.0",
        "mkdirp": "0.5.1",
        "moment": "2.13.0",
        "npm": "3.9.2",
        "npmi": "2.0.1",
        "nunjucks": "2.5.2",
        "nunjucks-do": "1.0.0",
        "object-path": "^0.9.2",
        "omit-keys": "^0.1.0",
        "open": "0.0.5",
        "q": "1.4.1",
        "read-installed": "^4.0.3",
        "request": "2.72.0",
        "resolve": "1.1.7",
        "rmdir": "1.2.0",
        "semver": "5.1.0",
        "send": "0.13.2",
        "spawn-cmd": "0.0.2",
        "tiny-lr": "0.2.1",
        "tmp": "0.0.28",
        "urijs": "1.18.0"
    },
    "description": "Library and cmd utility to generate GitBooks",
    "devDependencies": {
        "eslint": "2.10.2",
        "expect": "^1.20.1",
        "mocha": "^2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "2b5157d358777a95f916499f385d859ccea0bf25",
        "tarball": "https://registry.npmjs.org/gitbook/-/gitbook-3.2.2.tgz"
    },
    "gitHead": "ad425b9772c73df297cfe9c024e7dd99e9bc4c75",
    "homepage": "https://www.gitbook.com",
    "keywords": [
        "git",
        "book",
        "gitbook"
    ],
    "license": "Apache-2.0",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "aarono",
            "email": "aaron.omullan@gmail.com"
        },
        {
            "name": "jpreynat",
            "email": "johan.preynat@gmail.com"
        },
        {
            "name": "samypesse",
            "email": "samypesse@gmail.com"
        }
    ],
    "name": "gitbook",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/GitbookIO/gitbook.git"
    },
    "scripts": {
        "lint": "eslint .",
        "test": "mocha ./testing/setup.js \"./lib/**/*/__tests__/*.js\" --bail --reporter=list --timeout=10000"
    },
    "version": "3.2.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gitbook](#apidoc.module.gitbook)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Book (values)](#apidoc.element.gitbook.Book)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Config (values)](#apidoc.element.gitbook.Config)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>FS (values)](#apidoc.element.gitbook.FS)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>File (values)](#apidoc.element.gitbook.File)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Glossary (values)](#apidoc.element.gitbook.Glossary)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Page (values)](#apidoc.element.gitbook.Page)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>PluginDependency (values)](#apidoc.element.gitbook.PluginDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Summary (values)](#apidoc.element.gitbook.Summary)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>createNodeFS (root)](#apidoc.element.gitbook.createNodeFS)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>initBook (rootFolder)](#apidoc.element.gitbook.initBook)
1.  object <span class="apidocSignatureSpan"></span>gitbook
1.  object <span class="apidocSignatureSpan">gitbook.</span>Book.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>CONFIG_FILES
1.  object <span class="apidocSignatureSpan">gitbook.</span>Config.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>ConfigModifier
1.  object <span class="apidocSignatureSpan">gitbook.</span>DEFAULT_PLUGINS
1.  object <span class="apidocSignatureSpan">gitbook.</span>EXTENSIONS_ASCIIDOC
1.  object <span class="apidocSignatureSpan">gitbook.</span>EXTENSIONS_MARKDOWN
1.  object <span class="apidocSignatureSpan">gitbook.</span>FS.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>FS.prototype._defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.</span>File.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>Glossary.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>IGNORE_FILES
1.  object <span class="apidocSignatureSpan">gitbook.</span>Output
1.  object <span class="apidocSignatureSpan">gitbook.</span>Page.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>Parse
1.  object <span class="apidocSignatureSpan">gitbook.</span>PluginDependency.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>Summary.prototype
1.  object <span class="apidocSignatureSpan">gitbook.</span>SummaryModifier
1.  object <span class="apidocSignatureSpan">gitbook.</span>browser
1.  object <span class="apidocSignatureSpan">gitbook.</span>commands
1.  object <span class="apidocSignatureSpan">gitbook.</span>parsers

#### [module gitbook.Book](#apidoc.module.gitbook.Book)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Book (values)](#apidoc.element.gitbook.Book.Book)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.</span>createForFS (fs)](#apidoc.element.gitbook.Book.createForFS)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.</span>createFromParent (parent, language)](#apidoc.element.gitbook.Book.createFromParent)

#### [module gitbook.Book.prototype](#apidoc.module.gitbook.Book.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>addLanguageBook (language, book)](#apidoc.element.gitbook.Book.prototype.addLanguageBook)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>constructor (values)](#apidoc.element.gitbook.Book.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getBooks ()](#apidoc.element.gitbook.Book.prototype.getBooks)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getConfig ()](#apidoc.element.gitbook.Book.prototype.getConfig)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getContentFS ()](#apidoc.element.gitbook.Book.prototype.getContentFS)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getContentRoot ()](#apidoc.element.gitbook.Book.prototype.getContentRoot)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultExt ()](#apidoc.element.gitbook.Book.prototype.getDefaultExt)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultGlossaryPath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultGlossaryPath)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultReadmePath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultReadmePath)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultSummaryPath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultSummaryPath)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getFS ()](#apidoc.element.gitbook.Book.prototype.getFS)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getGlossary ()](#apidoc.element.gitbook.Book.prototype.getGlossary)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getIgnore ()](#apidoc.element.gitbook.Book.prototype.getIgnore)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguage ()](#apidoc.element.gitbook.Book.prototype.getLanguage)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguageBook (language)](#apidoc.element.gitbook.Book.prototype.getLanguageBook)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguages ()](#apidoc.element.gitbook.Book.prototype.getLanguages)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLogger ()](#apidoc.element.gitbook.Book.prototype.getLogger)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getPage (ref)](#apidoc.element.gitbook.Book.prototype.getPage)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getReadme ()](#apidoc.element.gitbook.Book.prototype.getReadme)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getRoot ()](#apidoc.element.gitbook.Book.prototype.getRoot)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getSummary ()](#apidoc.element.gitbook.Book.prototype.getSummary)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isContentFileIgnored (filename)](#apidoc.element.gitbook.Book.prototype.isContentFileIgnored)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isFileIgnored (filename)](#apidoc.element.gitbook.Book.prototype.isFileIgnored)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isLanguageBook ()](#apidoc.element.gitbook.Book.prototype.isLanguageBook)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isMultilingual ()](#apidoc.element.gitbook.Book.prototype.isMultilingual)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setConfig (config)](#apidoc.element.gitbook.Book.prototype.setConfig)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setIgnore (ignore)](#apidoc.element.gitbook.Book.prototype.setIgnore)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setLogLevel (level)](#apidoc.element.gitbook.Book.prototype.setLogLevel)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setReadme (readme)](#apidoc.element.gitbook.Book.prototype.setReadme)
1.  [function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setSummary (summary)](#apidoc.element.gitbook.Book.prototype.setSummary)
1.  number <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>_keys

#### [module gitbook.Config](#apidoc.module.gitbook.Config)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Config (values)](#apidoc.element.gitbook.Config.Config)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.</span>create (file, values)](#apidoc.element.gitbook.Config.create)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.</span>createWithValues (values)](#apidoc.element.gitbook.Config.createWithValues)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.</span>keyToKeyPath (keyPath)](#apidoc.element.gitbook.Config.keyToKeyPath)

#### [module gitbook.Config.prototype](#apidoc.module.gitbook.Config.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>constructor (values)](#apidoc.element.gitbook.Config.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getFile ()](#apidoc.element.gitbook.Config.prototype.getFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getPluginDependencies ()](#apidoc.element.gitbook.Config.prototype.getPluginDependencies)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getPluginDependency (name)](#apidoc.element.gitbook.Config.prototype.getPluginDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getValue (keyPath, def)](#apidoc.element.gitbook.Config.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getValues ()](#apidoc.element.gitbook.Config.prototype.getValues)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>mergeValues (values)](#apidoc.element.gitbook.Config.prototype.mergeValues)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setFile (file)](#apidoc.element.gitbook.Config.prototype.setFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setPluginDependencies (deps)](#apidoc.element.gitbook.Config.prototype.setPluginDependencies)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setValue (keyPath, value)](#apidoc.element.gitbook.Config.prototype.setValue)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>toReducedVersion ()](#apidoc.element.gitbook.Config.prototype.toReducedVersion)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>toText ()](#apidoc.element.gitbook.Config.prototype.toText)
1.  [function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>updateValues (values)](#apidoc.element.gitbook.Config.prototype.updateValues)
1.  number <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>_keys
1.  string <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>_name

#### [module gitbook.ConfigModifier](#apidoc.module.gitbook.ConfigModifier)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>addPlugin (config, pluginName, version)](#apidoc.element.gitbook.ConfigModifier.addPlugin)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>editPlugin (config, pluginName, pluginConfig)](#apidoc.element.gitbook.ConfigModifier.editPlugin)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>getPluginConfig (config, pluginName)](#apidoc.element.gitbook.ConfigModifier.getPluginConfig)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>hasPlugin (deps, pluginName, version)](#apidoc.element.gitbook.ConfigModifier.hasPlugin)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>isDefaultPlugin (pluginName, version)](#apidoc.element.gitbook.ConfigModifier.isDefaultPlugin)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>removePlugin (config, pluginName)](#apidoc.element.gitbook.ConfigModifier.removePlugin)
1.  [function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>togglePlugin (config, pluginName, state)](#apidoc.element.gitbook.ConfigModifier.togglePlugin)

#### [module gitbook.FS](#apidoc.module.gitbook.FS)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>FS (values)](#apidoc.element.gitbook.FS.FS)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.</span>create (def)](#apidoc.element.gitbook.FS.create)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.</span>reduceScope (fs, scope)](#apidoc.element.gitbook.FS.reduceScope)

#### [module gitbook.FS.prototype](#apidoc.module.gitbook.FS.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>constructor (values)](#apidoc.element.gitbook.FS.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>exists (filename)](#apidoc.element.gitbook.FS.prototype.exists)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>findFile (dirname, filename)](#apidoc.element.gitbook.FS.prototype.findFile)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>getRoot ()](#apidoc.element.gitbook.FS.prototype.getRoot)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>isInScope (filename)](#apidoc.element.gitbook.FS.prototype.isInScope)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>listAllFiles (dirName, filterFn)](#apidoc.element.gitbook.FS.prototype.listAllFiles)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>listFiles (dirname)](#apidoc.element.gitbook.FS.prototype.listFiles)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>loadAsObject (filename)](#apidoc.element.gitbook.FS.prototype.loadAsObject)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>read (filename)](#apidoc.element.gitbook.FS.prototype.read)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readAsStream (filename)](#apidoc.element.gitbook.FS.prototype.readAsStream)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readAsString (filename, encoding)](#apidoc.element.gitbook.FS.prototype.readAsString)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readDir (dirname)](#apidoc.element.gitbook.FS.prototype.readDir)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>resolve ()](#apidoc.element.gitbook.FS.prototype.resolve)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>statFile (filename)](#apidoc.element.gitbook.FS.prototype.statFile)
1.  number <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>_keys

#### [module gitbook.FS.prototype._defaultValues](#apidoc.module.gitbook.FS.prototype._defaultValues)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsExists ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsExists)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsReadDir ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsReadDir)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsReadFile ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsReadFile)
1.  [function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsStatFile ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsStatFile)
1.  object <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsLoadObject
1.  object <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsReadAsStream
1.  string <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>root

#### [module gitbook.File](#apidoc.module.gitbook.File)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>File (values)](#apidoc.element.gitbook.File.File)
1.  [function <span class="apidocSignatureSpan">gitbook.File.</span>createFromStat (filepath, stat)](#apidoc.element.gitbook.File.createFromStat)
1.  [function <span class="apidocSignatureSpan">gitbook.File.</span>createWithFilepath (filepath)](#apidoc.element.gitbook.File.createWithFilepath)

#### [module gitbook.File.prototype](#apidoc.module.gitbook.File.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>constructor (values)](#apidoc.element.gitbook.File.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>exists ()](#apidoc.element.gitbook.File.prototype.exists)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getExtension ()](#apidoc.element.gitbook.File.prototype.getExtension)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getMTime ()](#apidoc.element.gitbook.File.prototype.getMTime)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getParser ()](#apidoc.element.gitbook.File.prototype.getParser)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getPath ()](#apidoc.element.gitbook.File.prototype.getPath)
1.  [function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getType ()](#apidoc.element.gitbook.File.prototype.getType)
1.  number <span class="apidocSignatureSpan">gitbook.File.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.File.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.File.prototype.</span>_keys

#### [module gitbook.Glossary](#apidoc.module.gitbook.Glossary)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Glossary (values)](#apidoc.element.gitbook.Glossary.Glossary)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.</span>addEntry (glossary, entry)](#apidoc.element.gitbook.Glossary.addEntry)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.</span>addEntryByName (glossary, name, description)](#apidoc.element.gitbook.Glossary.addEntryByName)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.</span>createFromEntries (file, entries)](#apidoc.element.gitbook.Glossary.createFromEntries)

#### [module gitbook.Glossary.prototype](#apidoc.module.gitbook.Glossary.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>constructor (values)](#apidoc.element.gitbook.Glossary.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getEntries ()](#apidoc.element.gitbook.Glossary.prototype.getEntries)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getEntry (name)](#apidoc.element.gitbook.Glossary.prototype.getEntry)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getFile ()](#apidoc.element.gitbook.Glossary.prototype.getFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>toText (parser)](#apidoc.element.gitbook.Glossary.prototype.toText)
1.  number <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>_keys

#### [module gitbook.Output](#apidoc.module.gitbook.Output)
1.  [function <span class="apidocSignatureSpan">gitbook.Output.</span>generate (generator, book, options)](#apidoc.element.gitbook.Output.generate)
1.  [function <span class="apidocSignatureSpan">gitbook.Output.</span>getGenerator (name)](#apidoc.element.gitbook.Output.getGenerator)

#### [module gitbook.Page](#apidoc.module.gitbook.Page)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Page (values)](#apidoc.element.gitbook.Page.Page)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.</span>createForFile (file)](#apidoc.element.gitbook.Page.createForFile)

#### [module gitbook.Page.prototype](#apidoc.module.gitbook.Page.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>constructor (values)](#apidoc.element.gitbook.Page.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getAttributes ()](#apidoc.element.gitbook.Page.prototype.getAttributes)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getContent ()](#apidoc.element.gitbook.Page.prototype.getContent)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getDir ()](#apidoc.element.gitbook.Page.prototype.getDir)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getFile ()](#apidoc.element.gitbook.Page.prototype.getFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getPath ()](#apidoc.element.gitbook.Page.prototype.getPath)
1.  [function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>toText ()](#apidoc.element.gitbook.Page.prototype.toText)

#### [module gitbook.Parse](#apidoc.module.gitbook.Parse)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>listAssets (book, pages)](#apidoc.element.gitbook.Parse.listAssets)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>lookupStructureFile (book, type)](#apidoc.element.gitbook.Parse.lookupStructureFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseBook (book)](#apidoc.element.gitbook.Parse.parseBook)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseConfig (book)](#apidoc.element.gitbook.Parse.parseConfig)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseGlossary (book)](#apidoc.element.gitbook.Parse.parseGlossary)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseIgnore (book)](#apidoc.element.gitbook.Parse.parseIgnore)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseLanguages (book)](#apidoc.element.gitbook.Parse.parseLanguages)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePage (book, page)](#apidoc.element.gitbook.Parse.parsePage)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePageFromString (page, content)](#apidoc.element.gitbook.Parse.parsePageFromString)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePagesList (book)](#apidoc.element.gitbook.Parse.parsePagesList)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseReadme (book)](#apidoc.element.gitbook.Parse.parseReadme)
1.  [function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseSummary (book)](#apidoc.element.gitbook.Parse.parseSummary)

#### [module gitbook.PluginDependency](#apidoc.module.gitbook.PluginDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>PluginDependency (values)](#apidoc.element.gitbook.PluginDependency.PluginDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>create (name, version, enabled)](#apidoc.element.gitbook.PluginDependency.create)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>createFromString (s)](#apidoc.element.gitbook.PluginDependency.createFromString)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listFromArray (arr)](#apidoc.element.gitbook.PluginDependency.listFromArray)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listFromString (s)](#apidoc.element.gitbook.PluginDependency.listFromString)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listToArray (list)](#apidoc.element.gitbook.PluginDependency.listToArray)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>nameToNpmID (s)](#apidoc.element.gitbook.PluginDependency.nameToNpmID)

#### [module gitbook.PluginDependency.prototype](#apidoc.module.gitbook.PluginDependency.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>constructor (values)](#apidoc.element.gitbook.PluginDependency.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getName ()](#apidoc.element.gitbook.PluginDependency.prototype.getName)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getNpmID ()](#apidoc.element.gitbook.PluginDependency.prototype.getNpmID)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getVersion ()](#apidoc.element.gitbook.PluginDependency.prototype.getVersion)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>isEnabled ()](#apidoc.element.gitbook.PluginDependency.prototype.isEnabled)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>isGitDependency ()](#apidoc.element.gitbook.PluginDependency.prototype.isGitDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>toggle (state)](#apidoc.element.gitbook.PluginDependency.prototype.toggle)
1.  number <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>_keys
1.  string <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>_name

#### [module gitbook.Summary](#apidoc.module.gitbook.Summary)
1.  [function <span class="apidocSignatureSpan">gitbook.</span>Summary (values)](#apidoc.element.gitbook.Summary.Summary)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.</span>createFromParts (file, parts)](#apidoc.element.gitbook.Summary.createFromParts)

#### [module gitbook.Summary.prototype](#apidoc.module.gitbook.Summary.prototype)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>constructor (values)](#apidoc.element.gitbook.Summary.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getArticle (iter, partIter)](#apidoc.element.gitbook.Summary.prototype.getArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getArticlesAsList ()](#apidoc.element.gitbook.Summary.prototype.getArticlesAsList)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getByLevel (level)](#apidoc.element.gitbook.Summary.prototype.getByLevel)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getByPath (filePath)](#apidoc.element.gitbook.Summary.prototype.getByPath)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getFile ()](#apidoc.element.gitbook.Summary.prototype.getFile)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getFirstArticle ()](#apidoc.element.gitbook.Summary.prototype.getFirstArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getNextArticle (current)](#apidoc.element.gitbook.Summary.prototype.getNextArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getParent (level)](#apidoc.element.gitbook.Summary.prototype.getParent)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getPart (i)](#apidoc.element.gitbook.Summary.prototype.getPart)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getParts ()](#apidoc.element.gitbook.Summary.prototype.getParts)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getPrevArticle (current)](#apidoc.element.gitbook.Summary.prototype.getPrevArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>toText (parseExt)](#apidoc.element.gitbook.Summary.prototype.toText)
1.  number <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>size
1.  object <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>_defaultValues
1.  object <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>_keys
1.  string <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>_name

#### [module gitbook.SummaryModifier](#apidoc.module.gitbook.SummaryModifier)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editArticleRef (summary, level, newRef)](#apidoc.element.gitbook.SummaryModifier.editArticleRef)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editArticleTitle (summary, level, newTitle)](#apidoc.element.gitbook.SummaryModifier.editArticleTitle)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editPartTitle (summary, index, newTitle)](#apidoc.element.gitbook.SummaryModifier.editPartTitle)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>insertArticle (summary, article, level)](#apidoc.element.gitbook.SummaryModifier.insertArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>insertPart (summary, part, index)](#apidoc.element.gitbook.SummaryModifier.insertPart)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>moveArticle (summary, origin, target)](#apidoc.element.gitbook.SummaryModifier.moveArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>moveArticleAfter (summary, origin, afterTarget)](#apidoc.element.gitbook.SummaryModifier.moveArticleAfter)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>removeArticle (summary, level)](#apidoc.element.gitbook.SummaryModifier.removeArticle)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>removePart (summary, index)](#apidoc.element.gitbook.SummaryModifier.removePart)
1.  [function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>unshiftArticle (summary, article)](#apidoc.element.gitbook.SummaryModifier.unshiftArticle)

#### [module gitbook.browser](#apidoc.module.gitbook.browser)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>Book (values)](#apidoc.element.gitbook.browser.Book)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>Config (values)](#apidoc.element.gitbook.browser.Config)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>FS (values)](#apidoc.element.gitbook.browser.FS)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>File (values)](#apidoc.element.gitbook.browser.File)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>Glossary (values)](#apidoc.element.gitbook.browser.Glossary)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>Page (values)](#apidoc.element.gitbook.browser.Page)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>PluginDependency (values)](#apidoc.element.gitbook.browser.PluginDependency)
1.  [function <span class="apidocSignatureSpan">gitbook.browser.</span>Summary (values)](#apidoc.element.gitbook.browser.Summary)
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>CONFIG_FILES
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>ConfigModifier
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>DEFAULT_PLUGINS
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>EXTENSIONS_ASCIIDOC
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>EXTENSIONS_MARKDOWN
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>IGNORE_FILES
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>Parse
1.  object <span class="apidocSignatureSpan">gitbook.browser.</span>SummaryModifier

#### [module gitbook.gitbook](#apidoc.module.gitbook.gitbook)
1.  [function <span class="apidocSignatureSpan">gitbook.gitbook.</span>satisfies (condition)](#apidoc.element.gitbook.gitbook.satisfies)
1.  object <span class="apidocSignatureSpan">gitbook.gitbook.</span>START_TIME
1.  string <span class="apidocSignatureSpan">gitbook.gitbook.</span>version

#### [module gitbook.parsers](#apidoc.module.gitbook.parsers)
1.  [function <span class="apidocSignatureSpan">gitbook.parsers.</span>get (name)](#apidoc.element.gitbook.parsers.get)
1.  [function <span class="apidocSignatureSpan">gitbook.parsers.</span>getByExt (ext)](#apidoc.element.gitbook.parsers.getByExt)
1.  [function <span class="apidocSignatureSpan">gitbook.parsers.</span>getForFile (filename)](#apidoc.element.gitbook.parsers.getForFile)
1.  object <span class="apidocSignatureSpan">gitbook.parsers.</span>extensions



# <a name="apidoc.module.gitbook"></a>[module gitbook](#apidoc.module.gitbook)

#### <a name="apidoc.element.gitbook.Book"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Book (values)](#apidoc.element.gitbook.Book)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Config (values)](#apidoc.element.gitbook.Config)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS"></a>[function <span class="apidocSignatureSpan">gitbook.</span>FS (values)](#apidoc.element.gitbook.FS)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File"></a>[function <span class="apidocSignatureSpan">gitbook.</span>File (values)](#apidoc.element.gitbook.File)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Glossary (values)](#apidoc.element.gitbook.Glossary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Page (values)](#apidoc.element.gitbook.Page)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency"></a>[function <span class="apidocSignatureSpan">gitbook.</span>PluginDependency (values)](#apidoc.element.gitbook.PluginDependency)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Summary (values)](#apidoc.element.gitbook.Summary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.createNodeFS"></a>[function <span class="apidocSignatureSpan">gitbook.</span>createNodeFS (root)](#apidoc.element.gitbook.createNodeFS)
- description and source-code
```javascript
function createNodeFS(root) {
    return FS.create({
        root: root,

        fsExists: fs.exists,
        fsReadFile: fs.readFile,
        fsStatFile: fs.stat,
        fsReadDir: fsReadDir,
        fsLoadObject: fsLoadObject,
        fsReadAsStream: fs.readStream
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.initBook"></a>[function <span class="apidocSignatureSpan">gitbook.</span>initBook (rootFolder)](#apidoc.element.gitbook.initBook)
- description and source-code
```javascript
function initBook(rootFolder) {
    var extension = '.md';

    return fs.mkdirp(rootFolder)

    // Parse the summary and readme
    .then(function() {
        var fs = createNodeFS(rootFolder);
        var book = Book.createForFS(fs);

        return Parse.parseReadme(book)

        // Setup default readme if doesn't found one
        .fail(function() {
            var readmeFile = File.createWithFilepath('README' + extension);
            var readme = Readme.create(readmeFile);
            return book.setReadme(readme);
        });
    })
    .then(Parse.parseSummary)

    .then(function(book) {
        var logger = book.getLogger();
        var summary = book.getSummary();
        var summaryFile = summary.getFile();
        var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

        var articles = summary.getArticlesAsList();

        // Write pages
        return Promise.forEach(articles, function(article) {
            var articlePath = article.getPath();
            var filePath = articlePath? path.join(rootFolder, articlePath) : null;
            if (!filePath) {
                return;
            }

            return fs.assertFile(filePath, function() {
                return fs.ensureFile(filePath)
                .then(function() {
                    logger.info.ln('create', article.getPath());
                    return fs.writeFile(filePath, '# ' + article.getTitle() + '\n\n');
                });
            });
        })

        // Write summary
        .then(function() {
            var filePath = path.join(rootFolder, summaryFilename);

            return fs.ensureFile(filePath)
            .then(function() {
                logger.info.ln('create ' + path.basename(filePath));
                return fs.writeFile(filePath, summary.toText(extension));
            });
        })

        // Log end
        .then(function() {
            logger.info.ln('initialization is finished');
        });
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Book"></a>[module gitbook.Book](#apidoc.module.gitbook.Book)

#### <a name="apidoc.element.gitbook.Book.Book"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Book (values)](#apidoc.element.gitbook.Book.Book)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.createForFS"></a>[function <span class="apidocSignatureSpan">gitbook.Book.</span>createForFS (fs)](#apidoc.element.gitbook.Book.createForFS)
- description and source-code
```javascript
function createForFS(fs) {
    return new Book({
        fs: fs
    });
}
```
- example usage
```shell
...
    var extension = '.md';

    return fs.mkdirp(rootFolder)

    // Parse the summary and readme
    .then(function() {
var fs = createNodeFS(rootFolder);
var book = Book.createForFS(fs);

return Parse.parseReadme(book)

// Setup default readme if doesn't found one
.fail(function() {
    var readmeFile = File.createWithFilepath('README' + extension);
    var readme = Readme.create(readmeFile);
...
```

#### <a name="apidoc.element.gitbook.Book.createFromParent"></a>[function <span class="apidocSignatureSpan">gitbook.Book.</span>createFromParent (parent, language)](#apidoc.element.gitbook.Book.createFromParent)
- description and source-code
```javascript
function createFromParent(parent, language) {
    var ignore = parent.getIgnore();
    var config = parent.getConfig();

    // Set language in configuration
    config = config.setValue('language', language);

    return new Book({
        // Inherits config. logegr and list of ignored files
        logger: parent.getLogger(),
        config: config,
        ignore: ignore,

        language: language,
        fs: FS.reduceScope(parent.getContentFS(), language)
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Book.prototype"></a>[module gitbook.Book.prototype](#apidoc.module.gitbook.Book.prototype)

#### <a name="apidoc.element.gitbook.Book.prototype.addLanguageBook"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>addLanguageBook (language, book)](#apidoc.element.gitbook.Book.prototype.addLanguageBook)
- description and source-code
```javascript
addLanguageBook = function (language, book) {
    var books = this.getBooks();
    books = books.set(language, book);

    return this.set('books', books);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>constructor (values)](#apidoc.element.gitbook.Book.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getBooks"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getBooks ()](#apidoc.element.gitbook.Book.prototype.getBooks)
- description and source-code
```javascript
getBooks = function () {
    return this.get('books');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getConfig"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getConfig ()](#apidoc.element.gitbook.Book.prototype.getConfig)
- description and source-code
```javascript
getConfig = function () {
    return this.get('config');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getContentFS"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getContentFS ()](#apidoc.element.gitbook.Book.prototype.getContentFS)
- description and source-code
```javascript
getContentFS = function () {
    var fs = this.getFS();
    var config = this.getConfig();
    var rootFolder = config.getValue('root');

    if (rootFolder) {
        return FS.reduceScope(fs, rootFolder);
    }

    return fs;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getContentRoot"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getContentRoot ()](#apidoc.element.gitbook.Book.prototype.getContentRoot)
- description and source-code
```javascript
getContentRoot = function () {
    var fs = this.getContentFS();
    return fs.getRoot();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getDefaultExt"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultExt ()](#apidoc.element.gitbook.Book.prototype.getDefaultExt)
- description and source-code
```javascript
getDefaultExt = function () {
    // Inferring sources
    var clues = [
        this.getReadme(),
        this.getSummary(),
        this.getGlossary()
    ];

    // List their extensions
    var exts = clues.map(function (clue) {
        var file = clue.getFile();
        if (file.exists()) {
            return file.getParser().getExtensions().first();
        } else {
            return null;
        }
    });
    // Adds the general default extension
    exts.push('.md');

    // Choose the first non null
    return exts.find(function (e) { return e !== null; });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getDefaultGlossaryPath"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultGlossaryPath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultGlossaryPath)
- description and source-code
```javascript
getDefaultGlossaryPath = function (absolute) {
    var defaultPath = 'GLOSSARY'+this.getDefaultExt();
    if (absolute) {
        return path.join(this.getContentRoot(), defaultPath);
    } else {
        return defaultPath;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getDefaultReadmePath"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultReadmePath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultReadmePath)
- description and source-code
```javascript
getDefaultReadmePath = function (absolute) {
    var defaultPath = 'README'+this.getDefaultExt();
    if (absolute) {
        return path.join(this.getContentRoot(), defaultPath);
    } else {
        return defaultPath;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getDefaultSummaryPath"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getDefaultSummaryPath (absolute)](#apidoc.element.gitbook.Book.prototype.getDefaultSummaryPath)
- description and source-code
```javascript
getDefaultSummaryPath = function (absolute) {
    var defaultPath = 'SUMMARY'+this.getDefaultExt();
    if (absolute) {
        return path.join(this.getContentRoot(), defaultPath);
    } else {
        return defaultPath;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getFS"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getFS ()](#apidoc.element.gitbook.Book.prototype.getFS)
- description and source-code
```javascript
getFS = function () {
    return this.get('fs');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getGlossary"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getGlossary ()](#apidoc.element.gitbook.Book.prototype.getGlossary)
- description and source-code
```javascript
getGlossary = function () {
    return this.get('glossary');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getIgnore"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getIgnore ()](#apidoc.element.gitbook.Book.prototype.getIgnore)
- description and source-code
```javascript
getIgnore = function () {
    return this.get('ignore');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getLanguage"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguage ()](#apidoc.element.gitbook.Book.prototype.getLanguage)
- description and source-code
```javascript
getLanguage = function () {
    return this.get('language');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getLanguageBook"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguageBook (language)](#apidoc.element.gitbook.Book.prototype.getLanguageBook)
- description and source-code
```javascript
getLanguageBook = function (language) {
    var books = this.getBooks();
    return books.get(language);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getLanguages"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLanguages ()](#apidoc.element.gitbook.Book.prototype.getLanguages)
- description and source-code
```javascript
getLanguages = function () {
    return this.get('languages');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getLogger"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getLogger ()](#apidoc.element.gitbook.Book.prototype.getLogger)
- description and source-code
```javascript
getLogger = function () {
    return this.get('logger');
}
```
- example usage
```shell
...
    var readme = Readme.create(readmeFile);
    return book.setReadme(readme);
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
...
```

#### <a name="apidoc.element.gitbook.Book.prototype.getPage"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getPage (ref)](#apidoc.element.gitbook.Book.prototype.getPage)
- description and source-code
```javascript
getPage = function (ref) {
    return this.getPages().get(ref);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getReadme"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getReadme ()](#apidoc.element.gitbook.Book.prototype.getReadme)
- description and source-code
```javascript
getReadme = function () {
    return this.get('readme');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getRoot"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getRoot ()](#apidoc.element.gitbook.Book.prototype.getRoot)
- description and source-code
```javascript
getRoot = function () {
    var fs = this.getFS();
    return fs.getRoot();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.getSummary"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>getSummary ()](#apidoc.element.gitbook.Book.prototype.getSummary)
- description and source-code
```javascript
getSummary = function () {
    return this.get('summary');
}
```
- example usage
```shell
...
    return book.setReadme(readme);
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
...
```

#### <a name="apidoc.element.gitbook.Book.prototype.isContentFileIgnored"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isContentFileIgnored (filename)](#apidoc.element.gitbook.Book.prototype.isContentFileIgnored)
- description and source-code
```javascript
isContentFileIgnored = function (filename) {
    var config = this.getConfig();
    var rootFolder = config.getValue('root');

    if (rootFolder) {
        filename = path.join(rootFolder, filename);
    }

    return this.isFileIgnored(filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.isFileIgnored"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isFileIgnored (filename)](#apidoc.element.gitbook.Book.prototype.isFileIgnored)
- description and source-code
```javascript
isFileIgnored = function (filename) {
    var ignore = this.getIgnore();
    var language = this.getLanguage();

    // Ignore is always relative to the root of the main book
    if (language) {
        filename = path.join(language, filename);
    }

    return ignore.isFileIgnored(filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.isLanguageBook"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isLanguageBook ()](#apidoc.element.gitbook.Book.prototype.isLanguageBook)
- description and source-code
```javascript
isLanguageBook = function () {
    return Boolean(this.getLanguage());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.isMultilingual"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>isMultilingual ()](#apidoc.element.gitbook.Book.prototype.isMultilingual)
- description and source-code
```javascript
isMultilingual = function () {
    return (this.getLanguages().getCount() > 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.setConfig"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setConfig (config)](#apidoc.element.gitbook.Book.prototype.setConfig)
- description and source-code
```javascript
setConfig = function (config) {
    return this.set('config', config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.setIgnore"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setIgnore (ignore)](#apidoc.element.gitbook.Book.prototype.setIgnore)
- description and source-code
```javascript
setIgnore = function (ignore) {
    return this.set('ignore', ignore);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.setLogLevel"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setLogLevel (level)](#apidoc.element.gitbook.Book.prototype.setLogLevel)
- description and source-code
```javascript
setLogLevel = function (level) {
    this.getLogger().setLevel(level);
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Book.prototype.setReadme"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setReadme (readme)](#apidoc.element.gitbook.Book.prototype.setReadme)
- description and source-code
```javascript
setReadme = function (readme) {
    return this.set('readme', readme);
}
```
- example usage
```shell
...

    return Parse.parseReadme(book)

    // Setup default readme if doesn't found one
    .fail(function() {
        var readmeFile = File.createWithFilepath('README' + extension);
        var readme = Readme.create(readmeFile);
        return book.setReadme(readme);
    });
})
.then(Parse.parseSummary)

.then(function(book) {
    var logger = book.getLogger();
    var summary = book.getSummary();
...
```

#### <a name="apidoc.element.gitbook.Book.prototype.setSummary"></a>[function <span class="apidocSignatureSpan">gitbook.Book.prototype.</span>setSummary (summary)](#apidoc.element.gitbook.Book.prototype.setSummary)
- description and source-code
```javascript
setSummary = function (summary) {
    return this.set('summary', summary);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Config"></a>[module gitbook.Config](#apidoc.module.gitbook.Config)

#### <a name="apidoc.element.gitbook.Config.Config"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Config (values)](#apidoc.element.gitbook.Config.Config)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.create"></a>[function <span class="apidocSignatureSpan">gitbook.Config.</span>create (file, values)](#apidoc.element.gitbook.Config.create)
- description and source-code
```javascript
create = function (file, values) {
    return new Config({
        file: file,
        values: Immutable.fromJS(values)
    });
}
```
- example usage
```shell
...
    var book = Book.createForFS(fs);

    return Parse.parseReadme(book)

    // Setup default readme if doesn't found one
    .fail(function() {
        var readmeFile = File.createWithFilepath('README' + extension);
        var readme = Readme.create(readmeFile);
        return book.setReadme(readme);
    });
})
.then(Parse.parseSummary)

.then(function(book) {
    var logger = book.getLogger();
...
```

#### <a name="apidoc.element.gitbook.Config.createWithValues"></a>[function <span class="apidocSignatureSpan">gitbook.Config.</span>createWithValues (values)](#apidoc.element.gitbook.Config.createWithValues)
- description and source-code
```javascript
createWithValues = function (values) {
    return new Config({
        values: Immutable.fromJS(values)
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.keyToKeyPath"></a>[function <span class="apidocSignatureSpan">gitbook.Config.</span>keyToKeyPath (keyPath)](#apidoc.element.gitbook.Config.keyToKeyPath)
- description and source-code
```javascript
keyToKeyPath = function (keyPath) {
    if (is.string(keyPath)) keyPath = keyPath.split('.');
    return keyPath;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Config.prototype"></a>[module gitbook.Config.prototype](#apidoc.module.gitbook.Config.prototype)

#### <a name="apidoc.element.gitbook.Config.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>constructor (values)](#apidoc.element.gitbook.Config.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.getFile"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getFile ()](#apidoc.element.gitbook.Config.prototype.getFile)
- description and source-code
```javascript
getFile = function () {
    return this.get('file');
}
```
- example usage
```shell
...
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
...
```

#### <a name="apidoc.element.gitbook.Config.prototype.getPluginDependencies"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getPluginDependencies ()](#apidoc.element.gitbook.Config.prototype.getPluginDependencies)
- description and source-code
```javascript
getPluginDependencies = function () {
    var plugins = this.getValue('plugins');

    if (is.string(plugins)) {
        return PluginDependency.listFromString(plugins);
    } else {
        return PluginDependency.listFromArray(plugins);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.getPluginDependency"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getPluginDependency (name)](#apidoc.element.gitbook.Config.prototype.getPluginDependency)
- description and source-code
```javascript
getPluginDependency = function (name) {
    var plugins = this.getPluginDependencies();

    return plugins.find(function(dep) {
        return dep.getName() === name;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getValue (keyPath, def)](#apidoc.element.gitbook.Config.prototype.getValue)
- description and source-code
```javascript
getValue = function (keyPath, def) {
    var values = this.getValues();
    keyPath = Config.keyToKeyPath(keyPath);

    if (!values.hasIn(keyPath)) {
        return Immutable.fromJS(def);
    }

    return values.getIn(keyPath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.getValues"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>getValues ()](#apidoc.element.gitbook.Config.prototype.getValues)
- description and source-code
```javascript
getValues = function () {
    return this.get('values');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.mergeValues"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>mergeValues (values)](#apidoc.element.gitbook.Config.prototype.mergeValues)
- description and source-code
```javascript
mergeValues = function (values) {
    var currentValues = this.getValues();
    values = Immutable.fromJS(values);

    currentValues = currentValues.mergeDeep(values);

    return this.set('values', currentValues);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.setFile"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setFile (file)](#apidoc.element.gitbook.Config.prototype.setFile)
- description and source-code
```javascript
setFile = function (file) {
    return this.set('file', file);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.setPluginDependencies"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setPluginDependencies (deps)](#apidoc.element.gitbook.Config.prototype.setPluginDependencies)
- description and source-code
```javascript
setPluginDependencies = function (deps) {
    var plugins = PluginDependency.listToArray(deps);

    return this.setValue('plugins', plugins);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.setValue"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>setValue (keyPath, value)](#apidoc.element.gitbook.Config.prototype.setValue)
- description and source-code
```javascript
setValue = function (keyPath, value) {
    keyPath = Config.keyToKeyPath(keyPath);

    value = Immutable.fromJS(value);

    var values = this.getValues();
    values = values.setIn(keyPath, value);

    return this.set('values', values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.toReducedVersion"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>toReducedVersion ()](#apidoc.element.gitbook.Config.prototype.toReducedVersion)
- description and source-code
```javascript
toReducedVersion = function () {
    return reducedObject(configDefault, this.getValues());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Config.prototype.toText"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>toText ()](#apidoc.element.gitbook.Config.prototype.toText)
- description and source-code
```javascript
toText = function () {
    return JSON.stringify(this.toReducedVersion().toJS(), null, 4);
}
```
- example usage
```shell
...
// Write summary
.then(function() {
    var filePath = path.join(rootFolder, summaryFilename);

    return fs.ensureFile(filePath)
    .then(function() {
        logger.info.ln('create ' + path.basename(filePath));
        return fs.writeFile(filePath, summary.toText(extension));
    });
})

// Log end
.then(function() {
    logger.info.ln('initialization is finished');
});
...
```

#### <a name="apidoc.element.gitbook.Config.prototype.updateValues"></a>[function <span class="apidocSignatureSpan">gitbook.Config.prototype.</span>updateValues (values)](#apidoc.element.gitbook.Config.prototype.updateValues)
- description and source-code
```javascript
updateValues = function (values) {
    values = Immutable.fromJS(values);

    return this.set('values', values);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.ConfigModifier"></a>[module gitbook.ConfigModifier](#apidoc.module.gitbook.ConfigModifier)

#### <a name="apidoc.element.gitbook.ConfigModifier.addPlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>addPlugin (config, pluginName, version)](#apidoc.element.gitbook.ConfigModifier.addPlugin)
- description and source-code
```javascript
function addPlugin(config, pluginName, version) {
    // For default plugin, we only ensure it is enabled
    if (isDefaultPlugin(pluginName, version)) {
        return togglePlugin(config, pluginName, true);
    }

    var deps = config.getPluginDependencies();
    var dep = PluginDependency.create(pluginName, version);

    deps = deps.push(dep);
    return config.setPluginDependencies(deps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.editPlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>editPlugin (config, pluginName, pluginConfig)](#apidoc.element.gitbook.ConfigModifier.editPlugin)
- description and source-code
```javascript
function editPlugin(config, pluginName, pluginConfig) {
    return config.setValue('pluginsConfig.'+pluginName, pluginConfig);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.getPluginConfig"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>getPluginConfig (config, pluginName)](#apidoc.element.gitbook.ConfigModifier.getPluginConfig)
- description and source-code
```javascript
function getPluginConfig(config, pluginName) {
    var pluginsConfig = config.getValues().get('pluginsConfig');
    if (pluginsConfig === undefined) {
        return {};
    }
    var pluginConf = pluginsConfig.get(pluginName);
    if (pluginConf === undefined) {
        return {};
    } else {
        return pluginConf.toJS();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.hasPlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>hasPlugin (deps, pluginName, version)](#apidoc.element.gitbook.ConfigModifier.hasPlugin)
- description and source-code
```javascript
function hasPlugin(deps, pluginName, version) {
    return !!deps.find(function(dep) {
        return dep.getName() === pluginName && (!version || dep.getVersion() === version);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.isDefaultPlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>isDefaultPlugin (pluginName, version)](#apidoc.element.gitbook.ConfigModifier.isDefaultPlugin)
- description and source-code
```javascript
function isDefaultPlugin(pluginName, version) {
    return hasPlugin(DEFAULT_PLUGINS, pluginName, version);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.removePlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>removePlugin (config, pluginName)](#apidoc.element.gitbook.ConfigModifier.removePlugin)
- description and source-code
```javascript
function removePlugin(config, pluginName) {
    var deps = config.getPluginDependencies();

    // For default plugin, we have to disable it instead of removing from the list
    if (isDefaultPlugin(pluginName)) {
        return togglePlugin(config, pluginName, false);
    }

    // Remove the dependency from the list
    deps = deps.filterNot(function(dep) {
        return dep.getName() === pluginName;
    });
    return config.setPluginDependencies(deps);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.ConfigModifier.togglePlugin"></a>[function <span class="apidocSignatureSpan">gitbook.ConfigModifier.</span>togglePlugin (config, pluginName, state)](#apidoc.element.gitbook.ConfigModifier.togglePlugin)
- description and source-code
```javascript
function togglePlugin(config, pluginName, state) {
    var deps = config.getPluginDependencies();

    // For default plugin, we should ensure it's listed first
    if (isDefaultPlugin(pluginName) && !hasPlugin(deps, pluginName)) {
        deps = deps.push(PluginDependency.create(pluginName));
    }

    deps = deps.map(function(dep) {
        if (dep.getName() === pluginName) {
            return dep.toggle(state);
        }

        return dep;
    });

    return config.setPluginDependencies(deps);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.FS"></a>[module gitbook.FS](#apidoc.module.gitbook.FS)

#### <a name="apidoc.element.gitbook.FS.FS"></a>[function <span class="apidocSignatureSpan">gitbook.</span>FS (values)](#apidoc.element.gitbook.FS.FS)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.create"></a>[function <span class="apidocSignatureSpan">gitbook.FS.</span>create (def)](#apidoc.element.gitbook.FS.create)
- description and source-code
```javascript
function create(def) {
    return new FS(def);
}
```
- example usage
```shell
...
    var book = Book.createForFS(fs);

    return Parse.parseReadme(book)

    // Setup default readme if doesn't found one
    .fail(function() {
        var readmeFile = File.createWithFilepath('README' + extension);
        var readme = Readme.create(readmeFile);
        return book.setReadme(readme);
    });
})
.then(Parse.parseSummary)

.then(function(book) {
    var logger = book.getLogger();
...
```

#### <a name="apidoc.element.gitbook.FS.reduceScope"></a>[function <span class="apidocSignatureSpan">gitbook.FS.</span>reduceScope (fs, scope)](#apidoc.element.gitbook.FS.reduceScope)
- description and source-code
```javascript
function reduceScope(fs, scope) {
    return fs.set('root', path.join(fs.getRoot(), scope));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.FS.prototype"></a>[module gitbook.FS.prototype](#apidoc.module.gitbook.FS.prototype)

#### <a name="apidoc.element.gitbook.FS.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>constructor (values)](#apidoc.element.gitbook.FS.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.exists"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>exists (filename)](#apidoc.element.gitbook.FS.prototype.exists)
- description and source-code
```javascript
exists = function (filename) {
    var that = this;

    return Promise()
    .then(function() {
        filename = that.resolve(filename);
        var exists = that.get('fsExists');

        return exists(filename);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.findFile"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>findFile (dirname, filename)](#apidoc.element.gitbook.FS.prototype.findFile)
- description and source-code
```javascript
findFile = function (dirname, filename) {
    return this.listFiles(dirname)
    .then(function(files) {
        return files.find(function(file) {
            return (file.toLowerCase() == filename.toLowerCase());
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.getRoot"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>getRoot ()](#apidoc.element.gitbook.FS.prototype.getRoot)
- description and source-code
```javascript
getRoot = function () {
    return this.get('root');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.isInScope"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>isInScope (filename)](#apidoc.element.gitbook.FS.prototype.isInScope)
- description and source-code
```javascript
isInScope = function (filename) {
    var rootPath = this.getRoot();
    filename = path.join(rootPath, filename);

    return PathUtil.isInRoot(rootPath, filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.listAllFiles"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>listAllFiles (dirName, filterFn)](#apidoc.element.gitbook.FS.prototype.listAllFiles)
- description and source-code
```javascript
listAllFiles = function (dirName, filterFn) {
    var that = this;
    dirName = dirName || '.';

    return this.readDir(dirName)
    .then(function(files) {
        return Promise.reduce(files, function(out, file) {
            var isDirectory = pathIsFolder(file);
            var newDirName = path.join(dirName, file);

            if (filterFn && filterFn(newDirName) === false) {
                return out;
            }

            if (!isDirectory) {
                return out.push(newDirName);
            }

            return that.listAllFiles(newDirName, filterFn)
            .then(function(inner) {
                return out.concat(inner);
            });
        }, Immutable.List());
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.listFiles"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>listFiles (dirname)](#apidoc.element.gitbook.FS.prototype.listFiles)
- description and source-code
```javascript
listFiles = function (dirname) {
    return this.readDir(dirname)
    .then(function(files) {
        return files.filterNot(pathIsFolder);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.loadAsObject"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>loadAsObject (filename)](#apidoc.element.gitbook.FS.prototype.loadAsObject)
- description and source-code
```javascript
loadAsObject = function (filename) {
    var that = this;
    var fsLoadObject = this.get('fsLoadObject');

    return this.exists(filename)
    .then(function(exists) {
        if (!exists) {
            var err = new Error('Module doesn\'t exist');
            err.code = 'MODULE_NOT_FOUND';

            throw err;
        }

        if (fsLoadObject) {
            return fsLoadObject(that.resolve(filename));
        } else {
            return that.readAsString(filename)
            .then(function(str) {
                return JSON.parse(str);
            });
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.read"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>read (filename)](#apidoc.element.gitbook.FS.prototype.read)
- description and source-code
```javascript
read = function (filename) {
    var that = this;

    return Promise()
    .then(function() {
        filename = that.resolve(filename);
        var read = that.get('fsReadFile');

        return read(filename);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.readAsStream"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readAsStream (filename)](#apidoc.element.gitbook.FS.prototype.readAsStream)
- description and source-code
```javascript
readAsStream = function (filename) {
    var that = this;
    var filepath = that.resolve(filename);
    var fsReadAsStream = this.get('fsReadAsStream');

    if (fsReadAsStream) {
        return Promise(fsReadAsStream(filepath));
    }

    return this.read(filename)
    .then(function(buf) {
        var bufferStream = new stream.PassThrough();
        bufferStream.end(buf);

        return bufferStream;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.readAsString"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readAsString (filename, encoding)](#apidoc.element.gitbook.FS.prototype.readAsString)
- description and source-code
```javascript
readAsString = function (filename, encoding) {
    encoding = encoding || 'utf8';

    return this.read(filename)
    .then(function(buf) {
        return buf.toString(encoding);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.readDir"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>readDir (dirname)](#apidoc.element.gitbook.FS.prototype.readDir)
- description and source-code
```javascript
readDir = function (dirname) {
    var that = this;

    return Promise()
    .then(function() {
        var dirpath = that.resolve(dirname);
        var readDir = that.get('fsReadDir');

        return readDir(dirpath);
    })
    .then(function(files) {
        return Immutable.List(files);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.resolve"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>resolve ()](#apidoc.element.gitbook.FS.prototype.resolve)
- description and source-code
```javascript
resolve = function () {
    var rootPath = this.getRoot();
    var args = Array.prototype.slice.call(arguments);
    var filename = path.join.apply(path, [rootPath].concat(args));
    filename = path.normalize(filename);

    if (!this.isInScope(filename)) {
        throw error.FileOutOfScopeError({
            filename: filename,
            root: this.root
        });
    }

    return filename;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype.statFile"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype.</span>statFile (filename)](#apidoc.element.gitbook.FS.prototype.statFile)
- description and source-code
```javascript
statFile = function (filename) {
    var that = this;

    return Promise()
    .then(function() {
        var filepath = that.resolve(filename);
        var stat = that.get('fsStatFile');

        return stat(filepath);
    })
    .then(function(stat) {
        return File.createFromStat(filename, stat);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.FS.prototype._defaultValues"></a>[module gitbook.FS.prototype._defaultValues](#apidoc.module.gitbook.FS.prototype._defaultValues)

#### <a name="apidoc.element.gitbook.FS.prototype._defaultValues.fsExists"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsExists ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsExists)
- description and source-code
```javascript
function anonymous() {

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype._defaultValues.fsReadDir"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsReadDir ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsReadDir)
- description and source-code
```javascript
function anonymous() {

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype._defaultValues.fsReadFile"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsReadFile ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsReadFile)
- description and source-code
```javascript
function anonymous() {

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.FS.prototype._defaultValues.fsStatFile"></a>[function <span class="apidocSignatureSpan">gitbook.FS.prototype._defaultValues.</span>fsStatFile ()](#apidoc.element.gitbook.FS.prototype._defaultValues.fsStatFile)
- description and source-code
```javascript
function anonymous() {

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.File"></a>[module gitbook.File](#apidoc.module.gitbook.File)

#### <a name="apidoc.element.gitbook.File.File"></a>[function <span class="apidocSignatureSpan">gitbook.</span>File (values)](#apidoc.element.gitbook.File.File)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.createFromStat"></a>[function <span class="apidocSignatureSpan">gitbook.File.</span>createFromStat (filepath, stat)](#apidoc.element.gitbook.File.createFromStat)
- description and source-code
```javascript
function createFromStat(filepath, stat) {
    return new File({
        path: filepath,
        mtime: stat.mtime
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.createWithFilepath"></a>[function <span class="apidocSignatureSpan">gitbook.File.</span>createWithFilepath (filepath)](#apidoc.element.gitbook.File.createWithFilepath)
- description and source-code
```javascript
function createWithFilepath(filepath) {
    return new File({
        path: filepath
    });
}
```
- example usage
```shell
...
    var fs = createNodeFS(rootFolder);
    var book = Book.createForFS(fs);

    return Parse.parseReadme(book)

    // Setup default readme if doesn't found one
    .fail(function() {
        var readmeFile = File.createWithFilepath('README' + extension);
        var readme = Readme.create(readmeFile);
        return book.setReadme(readme);
    });
})
.then(Parse.parseSummary)

.then(function(book) {
...
```



# <a name="apidoc.module.gitbook.File.prototype"></a>[module gitbook.File.prototype](#apidoc.module.gitbook.File.prototype)

#### <a name="apidoc.element.gitbook.File.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>constructor (values)](#apidoc.element.gitbook.File.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.prototype.exists"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>exists ()](#apidoc.element.gitbook.File.prototype.exists)
- description and source-code
```javascript
exists = function () {
    return Boolean(this.getPath());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.prototype.getExtension"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getExtension ()](#apidoc.element.gitbook.File.prototype.getExtension)
- description and source-code
```javascript
getExtension = function () {
    return path.extname(this.getPath()).toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.prototype.getMTime"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getMTime ()](#apidoc.element.gitbook.File.prototype.getMTime)
- description and source-code
```javascript
getMTime = function () {
    return this.get('mtime');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.prototype.getParser"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getParser ()](#apidoc.element.gitbook.File.prototype.getParser)
- description and source-code
```javascript
getParser = function () {
    return parsers.getByExt(this.getExtension());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.File.prototype.getPath"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getPath ()](#apidoc.element.gitbook.File.prototype.getPath)
- description and source-code
```javascript
getPath = function () {
    return this.get('path');
}
```
- example usage
```shell
...
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
    var filePath = articlePath? path.join(rootFolder, articlePath) : null;
...
```

#### <a name="apidoc.element.gitbook.File.prototype.getType"></a>[function <span class="apidocSignatureSpan">gitbook.File.prototype.</span>getType ()](#apidoc.element.gitbook.File.prototype.getType)
- description and source-code
```javascript
getType = function () {
    var parser = this.getParser();
    if (parser) {
        return parser.getName();
    } else {
        return undefined;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Glossary"></a>[module gitbook.Glossary](#apidoc.module.gitbook.Glossary)

#### <a name="apidoc.element.gitbook.Glossary.Glossary"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Glossary (values)](#apidoc.element.gitbook.Glossary.Glossary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.addEntry"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.</span>addEntry (glossary, entry)](#apidoc.element.gitbook.Glossary.addEntry)
- description and source-code
```javascript
function addEntry(glossary, entry) {
    var id = entry.getID();
    var entries = glossary.getEntries();

    entries = entries.set(id, entry);
    return glossary.set('entries', entries);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.addEntryByName"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.</span>addEntryByName (glossary, name, description)](#apidoc.element.gitbook.Glossary.addEntryByName)
- description and source-code
```javascript
function addEntryByName(glossary, name, description) {
    var entry = new GlossaryEntry({
        name: name,
        description: description
    });

    return Glossary.addEntry(glossary, entry);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.createFromEntries"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.</span>createFromEntries (file, entries)](#apidoc.element.gitbook.Glossary.createFromEntries)
- description and source-code
```javascript
function createFromEntries(file, entries) {
    entries = entries.map(function(entry) {
        if (!(entry instanceof GlossaryEntry)) {
            entry = new GlossaryEntry(entry);
        }

        return [entry.getID(), entry];
    });

    return new Glossary({
        file: file,
        entries: Immutable.OrderedMap(entries)
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Glossary.prototype"></a>[module gitbook.Glossary.prototype](#apidoc.module.gitbook.Glossary.prototype)

#### <a name="apidoc.element.gitbook.Glossary.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>constructor (values)](#apidoc.element.gitbook.Glossary.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.prototype.getEntries"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getEntries ()](#apidoc.element.gitbook.Glossary.prototype.getEntries)
- description and source-code
```javascript
getEntries = function () {
    return this.get('entries');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.prototype.getEntry"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getEntry (name)](#apidoc.element.gitbook.Glossary.prototype.getEntry)
- description and source-code
```javascript
getEntry = function (name) {
    var entries = this.getEntries();
    var id = GlossaryEntry.nameToID(name);

    return entries.get(id);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Glossary.prototype.getFile"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>getFile ()](#apidoc.element.gitbook.Glossary.prototype.getFile)
- description and source-code
```javascript
getFile = function () {
    return this.get('file');
}
```
- example usage
```shell
...
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
...
```

#### <a name="apidoc.element.gitbook.Glossary.prototype.toText"></a>[function <span class="apidocSignatureSpan">gitbook.Glossary.prototype.</span>toText (parser)](#apidoc.element.gitbook.Glossary.prototype.toText)
- description and source-code
```javascript
toText = function (parser) {
    var file = this.getFile();
    var entries = this.getEntries();

    parser = parser? parsers.getByExt(parser) : file.getParser();

    if (!parser) {
        throw error.FileNotParsableError({
            filename: file.getPath()
        });
    }

    return parser.renderGlossary(entries.toJS());
}
```
- example usage
```shell
...
// Write summary
.then(function() {
    var filePath = path.join(rootFolder, summaryFilename);

    return fs.ensureFile(filePath)
    .then(function() {
        logger.info.ln('create ' + path.basename(filePath));
        return fs.writeFile(filePath, summary.toText(extension));
    });
})

// Log end
.then(function() {
    logger.info.ln('initialization is finished');
});
...
```



# <a name="apidoc.module.gitbook.Output"></a>[module gitbook.Output](#apidoc.module.gitbook.Output)

#### <a name="apidoc.element.gitbook.Output.generate"></a>[function <span class="apidocSignatureSpan">gitbook.Output.</span>generate (generator, book, options)](#apidoc.element.gitbook.Output.generate)
- description and source-code
```javascript
function generateBook(generator, book, options) {
    options = generator.Options(options);
    var state = generator.State? generator.State({}) : Immutable.Map();
    var start = Date.now();

    return Promise(
        new Output({
            book: book,
            options: options,
            state: state,
            generator: generator.name
        })
    )

    // Cleanup output folder
    .then(function(output) {
        var logger = output.getLogger();
        var rootFolder = output.getRoot();

        logger.debug.ln('cleanup folder "' + rootFolder + '"');
        return fs.ensureFolder(rootFolder)
            .thenResolve(output);
    })

    .then(processOutput.bind(null, generator))

    // Log duration and end message
    .then(function(output) {
        var logger = output.getLogger();
        var end = Date.now();
        var duration = (end - start)/1000;

        logger.info.ok('generation finished with success in ' + duration.toFixed(1) + 's !');

        return output;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Output.getGenerator"></a>[function <span class="apidocSignatureSpan">gitbook.Output.</span>getGenerator (name)](#apidoc.element.gitbook.Output.getGenerator)
- description and source-code
```javascript
function getGenerator(name) {
    return generators.find(function(generator) {
        return generator.name == name;
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Page"></a>[module gitbook.Page](#apidoc.module.gitbook.Page)

#### <a name="apidoc.element.gitbook.Page.Page"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Page (values)](#apidoc.element.gitbook.Page.Page)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page.createForFile"></a>[function <span class="apidocSignatureSpan">gitbook.Page.</span>createForFile (file)](#apidoc.element.gitbook.Page.createForFile)
- description and source-code
```javascript
createForFile = function (file) {
    return new Page({
        file: file
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Page.prototype"></a>[module gitbook.Page.prototype](#apidoc.module.gitbook.Page.prototype)

#### <a name="apidoc.element.gitbook.Page.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>constructor (values)](#apidoc.element.gitbook.Page.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page.prototype.getAttributes"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getAttributes ()](#apidoc.element.gitbook.Page.prototype.getAttributes)
- description and source-code
```javascript
getAttributes = function () {
    return this.get('attributes');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page.prototype.getContent"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getContent ()](#apidoc.element.gitbook.Page.prototype.getContent)
- description and source-code
```javascript
getContent = function () {
    return this.get('content');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page.prototype.getDir"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getDir ()](#apidoc.element.gitbook.Page.prototype.getDir)
- description and source-code
```javascript
getDir = function () {
    return this.get('dir');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Page.prototype.getFile"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getFile ()](#apidoc.element.gitbook.Page.prototype.getFile)
- description and source-code
```javascript
getFile = function () {
    return this.get('file');
}
```
- example usage
```shell
...
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
...
```

#### <a name="apidoc.element.gitbook.Page.prototype.getPath"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>getPath ()](#apidoc.element.gitbook.Page.prototype.getPath)
- description and source-code
```javascript
getPath = function () {
    return this.getFile().getPath();
}
```
- example usage
```shell
...
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
    var filePath = articlePath? path.join(rootFolder, articlePath) : null;
...
```

#### <a name="apidoc.element.gitbook.Page.prototype.toText"></a>[function <span class="apidocSignatureSpan">gitbook.Page.prototype.</span>toText ()](#apidoc.element.gitbook.Page.prototype.toText)
- description and source-code
```javascript
toText = function () {
    var attrs = this.getAttributes();
    var content = this.getContent();

    if (attrs.size === 0) {
        return content;
    }

    var frontMatter = '---\n' + yaml.safeDump(attrs.toJS(), { skipInvalid: true }) + '---\n\n';
    return (frontMatter + content);
}
```
- example usage
```shell
...
// Write summary
.then(function() {
    var filePath = path.join(rootFolder, summaryFilename);

    return fs.ensureFile(filePath)
    .then(function() {
        logger.info.ln('create ' + path.basename(filePath));
        return fs.writeFile(filePath, summary.toText(extension));
    });
})

// Log end
.then(function() {
    logger.info.ln('initialization is finished');
});
...
```



# <a name="apidoc.module.gitbook.Parse"></a>[module gitbook.Parse](#apidoc.module.gitbook.Parse)

#### <a name="apidoc.element.gitbook.Parse.listAssets"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>listAssets (book, pages)](#apidoc.element.gitbook.Parse.listAssets)
- description and source-code
```javascript
function listAssets(book, pages) {
    var fs = book.getContentFS();

    var summary = book.getSummary();
    var summaryFile = summary.getFile().getPath();

    var glossary = book.getGlossary();
    var glossaryFile = glossary.getFile().getPath();

    var langs = book.getLanguages();
    var langsFile = langs.getFile().getPath();

    var config = book.getConfig();
    var configFile = config.getFile().getPath();

    function filterFile(file) {
        return !(
            file === summaryFile ||
            file === glossaryFile ||
            file === langsFile ||
            file === configFile ||
            book.isContentFileIgnored(file) ||
            pages.has(file)
        );
    }

    return timing.measure(
        'parse.listAssets',
        fs.listAllFiles('.', filterFile)
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.lookupStructureFile"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>lookupStructureFile (book, type)](#apidoc.element.gitbook.Parse.lookupStructureFile)
- description and source-code
```javascript
function lookupStructureFile(book, type) {
    var config = book.getConfig();

    var fileToSearch = config.getValue(['structure', type]);

    return findParsableFile(book, fileToSearch);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseBook"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseBook (book)](#apidoc.element.gitbook.Parse.parseBook)
- description and source-code
```javascript
function parseBook(book) {
    return timing.measure(
        'parse.book',
        Promise(book)
        .then(parseIgnore)
        .then(parseConfig)
        .then(parseLanguages)
        .then(function(resultBook) {
            if (resultBook.isMultilingual()) {
                return parseMultilingualBook(resultBook);
            } else {
                return parseBookContent(resultBook);
            }
        })
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseConfig"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseConfig (book)](#apidoc.element.gitbook.Parse.parseConfig)
- description and source-code
```javascript
function parseConfig(book) {
    var fs = book.getFS();
    var config = book.getConfig();

    return Promise.some(CONFIG_FILES, function(filename) {
        // Is this file ignored?
        if (book.isFileIgnored(filename)) {
            return;
        }

        // Try loading it
        return fs.loadAsObject(filename)
        .then(function(cfg) {
            return fs.statFile(filename)
            .then(function(file) {
                return {
                    file: file,
                    values: cfg
                };
            });
        })
        .fail(function(err) {
            if (err.code != 'MODULE_NOT_FOUND') throw(err);
            else return Promise(false);
        });
    })

    .then(function(result) {
        var values = result? result.values : {};
        values = validateConfig(values);

        // Set the file
        if (result.file) {
            config = config.setFile(result.file);
        }

        // Merge with old values
        config = config.mergeValues(values);

        return book.setConfig(config);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseGlossary"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseGlossary (book)](#apidoc.element.gitbook.Parse.parseGlossary)
- description and source-code
```javascript
function parseGlossary(book) {
    var logger = book.getLogger();

    return parseStructureFile(book, 'glossary')
    .spread(function(file, entries) {
        if (!file) {
            return book;
        }

        logger.debug.ln('glossary index file found at', file.getPath());

        var glossary = Glossary.createFromEntries(file, entries);
        return book.set('glossary', glossary);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseIgnore"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseIgnore (book)](#apidoc.element.gitbook.Parse.parseIgnore)
- description and source-code
```javascript
function parseIgnore(book) {
    if (book.isLanguageBook()) {
        return Promise.reject(new Error('Ignore files could be parsed for language books'));
    }

    var fs = book.getFS();
    var ignore = book.getIgnore();

    ignore = ignore.add(DEFAULT_IGNORES);

    return Promise.serie(IGNORE_FILES, function(filename) {
        return fs.readAsString(filename)
        .then(function(content) {
            ignore = ignore.add(content.toString().split(/\r?\n/));
        }, function(err) {
            return Promise();
        });
    })

    .then(function() {
        return book.setIgnore(ignore);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseLanguages"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseLanguages (book)](#apidoc.element.gitbook.Parse.parseLanguages)
- description and source-code
```javascript
function parseLanguages(book) {
    var logger = book.getLogger();

    return parseStructureFile(book, 'langs')
    .spread(function(file, result) {
        if (!file) {
            return book;
        }

        var languages = Languages.createFromList(file, result);

        logger.debug.ln('languages index file found at', file.getPath());
        logger.info.ln('parsing multilingual book, with', languages.getList().size, 'languages');

        return book.set('languages', languages);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parsePage"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePage (book, page)](#apidoc.element.gitbook.Parse.parsePage)
- description and source-code
```javascript
function parsePage(book, page) {
    var fs = book.getContentFS();
    var file = page.getFile();

    return fs.readAsString(file.getPath())
    .then(function(content) {
        return parsePageFromString(page, content);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parsePageFromString"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePageFromString (page, content)](#apidoc.element.gitbook.Parse.parsePageFromString)
- description and source-code
```javascript
function parsePageFromString(page, content) {
    // Parse page YAML
    var parsed = fm(content);

    return page.merge({
        content:    parsed.body,
        attributes: Immutable.fromJS(parsed.attributes),
        dir:        direction(parsed.body)
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parsePagesList"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parsePagesList (book)](#apidoc.element.gitbook.Parse.parsePagesList)
- description and source-code
```javascript
function parsePagesList(book) {
    var summary = book.getSummary();
    var glossary = book.getGlossary();
    var map = Immutable.OrderedMap();

    // Parse pages from summary
    return timing.measure(
        'parse.listPages',
        walkSummary(summary, function(article) {
            if (!article.isPage()) return;

            var filepath = article.getPath();

            // Is the page ignored?
            if (book.isContentFileIgnored(filepath)) return;

            return parseFilePage(book, filepath)
            .then(function(page) {
                // file doesn't exist
                if (!page) {
                    return;
                }

                map = map.set(filepath, page);
            });
        })
    )

    // Parse glossary
    .then(function() {
        var file = glossary.getFile();

        if (!file.exists()) {
            return;
        }

        return parseFilePage(book, file.getPath())
        .then(function(page) {
            // file doesn't exist
            if (!page) {
                return;
            }

            map = map.set(file.getPath(), page);
        });
    })

    .then(function() {
        return map;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Parse.parseReadme"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseReadme (book)](#apidoc.element.gitbook.Parse.parseReadme)
- description and source-code
```javascript
function parseReadme(book) {
    var logger = book.getLogger();

    return parseStructureFile(book, 'readme')
    .spread(function(file, result) {
        if (!file) {
            throw new error.FileNotFoundError({ filename: 'README' });
        }

        logger.debug.ln('readme found at', file.getPath());

        var readme = Readme.create(file, result);
        return book.set('readme', readme);
    });
}
```
- example usage
```shell
...
    return fs.mkdirp(rootFolder)

    // Parse the summary and readme
    .then(function() {
var fs = createNodeFS(rootFolder);
var book = Book.createForFS(fs);

return Parse.parseReadme(book)

// Setup default readme if doesn't found one
.fail(function() {
    var readmeFile = File.createWithFilepath('README' + extension);
    var readme = Readme.create(readmeFile);
    return book.setReadme(readme);
});
...
```

#### <a name="apidoc.element.gitbook.Parse.parseSummary"></a>[function <span class="apidocSignatureSpan">gitbook.Parse.</span>parseSummary (book)](#apidoc.element.gitbook.Parse.parseSummary)
- description and source-code
```javascript
function parseSummary(book) {
    var readme = book.getReadme();
    var logger = book.getLogger();
    var readmeFile = readme.getFile();

    return parseStructureFile(book, 'summary')
    .spread(function(file, result) {
        var summary;

        if (!file) {
            logger.warn.ln('no summary file in this book');
            summary = Summary();
        } else {
            logger.debug.ln('summary file found at', file.getPath());
            summary = Summary.createFromParts(file, result.parts);
        }

        // Insert readme as first entry if not in SUMMARY.md
        var readmeArticle = summary.getByPath(readmeFile.getPath());

        if (readmeFile.exists() && !readmeArticle) {
            summary = SummaryModifier.unshiftArticle(summary, {
                title: 'Introduction',
                ref: readmeFile.getPath()
            });
        }

        // Set new summary
        return book.setSummary(summary);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.PluginDependency"></a>[module gitbook.PluginDependency](#apidoc.module.gitbook.PluginDependency)

#### <a name="apidoc.element.gitbook.PluginDependency.PluginDependency"></a>[function <span class="apidocSignatureSpan">gitbook.</span>PluginDependency (values)](#apidoc.element.gitbook.PluginDependency.PluginDependency)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.create"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>create (name, version, enabled)](#apidoc.element.gitbook.PluginDependency.create)
- description and source-code
```javascript
create = function (name, version, enabled) {
    if (is.undefined(enabled)) {
        enabled = true;
    }

    return new PluginDependency({
        name: name,
        version: version || DEFAULT_VERSION,
        enabled: Boolean(enabled)
    });
}
```
- example usage
```shell
...
    var book = Book.createForFS(fs);

    return Parse.parseReadme(book)

    // Setup default readme if doesn't found one
    .fail(function() {
        var readmeFile = File.createWithFilepath('README' + extension);
        var readme = Readme.create(readmeFile);
        return book.setReadme(readme);
    });
})
.then(Parse.parseSummary)

.then(function(book) {
    var logger = book.getLogger();
...
```

#### <a name="apidoc.element.gitbook.PluginDependency.createFromString"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>createFromString (s)](#apidoc.element.gitbook.PluginDependency.createFromString)
- description and source-code
```javascript
createFromString = function (s) {
    var parts = s.split('@');
    var name = parts[0];
    var version = parts.slice(1).join('@');
    var enabled = true;

    if (name[0] === '-') {
        enabled = false;
        name = name.slice(1);
    }

    return new PluginDependency({
        name: name,
        version: version || DEFAULT_VERSION,
        enabled: enabled
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.listFromArray"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listFromArray (arr)](#apidoc.element.gitbook.PluginDependency.listFromArray)
- description and source-code
```javascript
listFromArray = function (arr) {
    return Immutable.List(arr)
        .map(function(entry) {
            if (is.string(entry)) {
                return PluginDependency.createFromString(entry);
            } else {
                return PluginDependency({
                    name: entry.get('name'),
                    version: entry.get('version')
                });
            }
        })
        .filter(function(dep) {
            return Boolean(dep.getName());
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.listFromString"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listFromString (s)](#apidoc.element.gitbook.PluginDependency.listFromString)
- description and source-code
```javascript
listFromString = function (s) {
    var parts = s.split(',');
    return PluginDependency.listFromArray(parts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.listToArray"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>listToArray (list)](#apidoc.element.gitbook.PluginDependency.listToArray)
- description and source-code
```javascript
listToArray = function (list) {
    return list
        .map(function(dep) {
            var result = '';

            if (!dep.isEnabled()) {
                result += '-';
            }

            result += dep.getName();
            if (dep.getVersion() !== DEFAULT_VERSION) {
                result += '@' + dep.getVersion();
            }

            return result;
        })
        .toJS();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.nameToNpmID"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.</span>nameToNpmID (s)](#apidoc.element.gitbook.PluginDependency.nameToNpmID)
- description and source-code
```javascript
nameToNpmID = function (s) {
    return PREFIX + s;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.PluginDependency.prototype"></a>[module gitbook.PluginDependency.prototype](#apidoc.module.gitbook.PluginDependency.prototype)

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>constructor (values)](#apidoc.element.gitbook.PluginDependency.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.getName"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getName ()](#apidoc.element.gitbook.PluginDependency.prototype.getName)
- description and source-code
```javascript
getName = function () {
    return this.get('name');
}
```
- example usage
```shell
...
* Return a specific parser by its name
*
* @param {String} name
* @return {Parser|undefined}
*/
function getParser(name) {
   return parsers.find(function(parser) {
       return parser.getName() === name;
   });
}

/**
* Return a specific parser according to an extension
*
* @param {String} ext
...
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.getNpmID"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getNpmID ()](#apidoc.element.gitbook.PluginDependency.prototype.getNpmID)
- description and source-code
```javascript
getNpmID = function () {
    return PluginDependency.nameToNpmID(this.getName());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.getVersion"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>getVersion ()](#apidoc.element.gitbook.PluginDependency.prototype.getVersion)
- description and source-code
```javascript
getVersion = function () {
    return this.get('version');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.isEnabled"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>isEnabled ()](#apidoc.element.gitbook.PluginDependency.prototype.isEnabled)
- description and source-code
```javascript
isEnabled = function () {
    return this.get('enabled');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.isGitDependency"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>isGitDependency ()](#apidoc.element.gitbook.PluginDependency.prototype.isGitDependency)
- description and source-code
```javascript
isGitDependency = function () {
    return !semver.validRange(this.getVersion());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.PluginDependency.prototype.toggle"></a>[function <span class="apidocSignatureSpan">gitbook.PluginDependency.prototype.</span>toggle (state)](#apidoc.element.gitbook.PluginDependency.prototype.toggle)
- description and source-code
```javascript
toggle = function (state) {
    if (is.undef(state)) {
        state = !this.isEnabled();
    }

    return this.set('enabled', state);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Summary"></a>[module gitbook.Summary](#apidoc.module.gitbook.Summary)

#### <a name="apidoc.element.gitbook.Summary.Summary"></a>[function <span class="apidocSignatureSpan">gitbook.</span>Summary (values)](#apidoc.element.gitbook.Summary.Summary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.createFromParts"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.</span>createFromParts (file, parts)](#apidoc.element.gitbook.Summary.createFromParts)
- description and source-code
```javascript
function createFromParts(file, parts) {
    parts = parts.map(function(part, i) {
        if (part instanceof SummaryPart) {
            return part;
        }

        return SummaryPart.create(part, i + 1);
    });

    return new Summary({
        file: file,
        parts: new Immutable.List(parts)
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.Summary.prototype"></a>[module gitbook.Summary.prototype](#apidoc.module.gitbook.Summary.prototype)

#### <a name="apidoc.element.gitbook.Summary.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>constructor (values)](#apidoc.element.gitbook.Summary.prototype.constructor)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getArticle"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getArticle (iter, partIter)](#apidoc.element.gitbook.Summary.prototype.getArticle)
- description and source-code
```javascript
getArticle = function (iter, partIter) {
    var parts = this.getParts();

    return parts.reduce(function(result, part) {
        if (result) return result;

        if (partIter && partIter(part)) return part;
        return SummaryArticle.findArticle(part, iter);
    }, null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getArticlesAsList"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getArticlesAsList ()](#apidoc.element.gitbook.Summary.prototype.getArticlesAsList)
- description and source-code
```javascript
getArticlesAsList = function () {
    var accu = [];

    this.getArticle(function(article) {
        accu.push(article);
    });

    return Immutable.List(accu);
}
```
- example usage
```shell
...

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
    var filePath = articlePath? path.join(rootFolder, articlePath) : null;
    if (!filePath) {
        return;
...
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getByLevel"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getByLevel (level)](#apidoc.element.gitbook.Summary.prototype.getByLevel)
- description and source-code
```javascript
getByLevel = function (level) {
    function iterByLevel(article) {
        return (article.getLevel() === level);
    }

    return this.getArticle(iterByLevel, iterByLevel);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getByPath"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getByPath (filePath)](#apidoc.element.gitbook.Summary.prototype.getByPath)
- description and source-code
```javascript
getByPath = function (filePath) {
    return this.getArticle(function(article) {
        var articlePath = article.getPath();

        return (
            articlePath &&
            LocationUtils.areIdenticalPaths(articlePath, filePath)
        );
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getFile"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getFile ()](#apidoc.element.gitbook.Summary.prototype.getFile)
- description and source-code
```javascript
getFile = function () {
    return this.get('file');
}
```
- example usage
```shell
...
});
    })
    .then(Parse.parseSummary)

    .then(function(book) {
var logger = book.getLogger();
var summary = book.getSummary();
var summaryFile = summary.getFile();
var summaryFilename = summaryFile.getPath() || ('SUMMARY' + extension);

var articles = summary.getArticlesAsList();

// Write pages
return Promise.forEach(articles, function(article) {
    var articlePath = article.getPath();
...
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getFirstArticle"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getFirstArticle ()](#apidoc.element.gitbook.Summary.prototype.getFirstArticle)
- description and source-code
```javascript
getFirstArticle = function () {
    return this.getArticle(function(article) {
        return true;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getNextArticle"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getNextArticle (current)](#apidoc.element.gitbook.Summary.prototype.getNextArticle)
- description and source-code
```javascript
getNextArticle = function (current) {
    var level = is.string(current)? current : current.getLevel();
    var wasPrev = false;

    return this.getArticle(function(article) {
        if (wasPrev) return true;

        wasPrev = article.getLevel() == level;
        return false;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getParent"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getParent (level)](#apidoc.element.gitbook.Summary.prototype.getParent)
- description and source-code
```javascript
getParent = function (level) {
    // Coerce to level
    level = is.string(level)? level : level.getLevel();

    // Get parent level
    var parentLevel = getParentLevel(level);
    if (!parentLevel) {
        return null;
    }

    // Get parent of the position
    var parentArticle = this.getByLevel(parentLevel);
    return parentArticle || null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getPart"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getPart (i)](#apidoc.element.gitbook.Summary.prototype.getPart)
- description and source-code
```javascript
getPart = function (i) {
    var parts = this.getParts();
    return parts.get(i);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getParts"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getParts ()](#apidoc.element.gitbook.Summary.prototype.getParts)
- description and source-code
```javascript
getParts = function () {
    return this.get('parts');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.getPrevArticle"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>getPrevArticle (current)](#apidoc.element.gitbook.Summary.prototype.getPrevArticle)
- description and source-code
```javascript
getPrevArticle = function (current) {
    var level = is.string(current)? current : current.getLevel();
    var prev = undefined;

    this.getArticle(function(article) {
        if (article.getLevel() == level) {
            return true;
        }

        prev = article;
        return false;
    });

    return prev;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.Summary.prototype.toText"></a>[function <span class="apidocSignatureSpan">gitbook.Summary.prototype.</span>toText (parseExt)](#apidoc.element.gitbook.Summary.prototype.toText)
- description and source-code
```javascript
toText = function (parseExt) {
    var file = this.getFile();
    var parts = this.getParts();

    var parser = parseExt? parsers.getByExt(parseExt) : file.getParser();

    if (!parser) {
        throw error.FileNotParsableError({
            filename: file.getPath()
        });
    }

    return parser.renderSummary({
        parts: parts.toJS()
    });
}
```
- example usage
```shell
...
// Write summary
.then(function() {
    var filePath = path.join(rootFolder, summaryFilename);

    return fs.ensureFile(filePath)
    .then(function() {
        logger.info.ln('create ' + path.basename(filePath));
        return fs.writeFile(filePath, summary.toText(extension));
    });
})

// Log end
.then(function() {
    logger.info.ln('initialization is finished');
});
...
```



# <a name="apidoc.module.gitbook.SummaryModifier"></a>[module gitbook.SummaryModifier](#apidoc.module.gitbook.SummaryModifier)

#### <a name="apidoc.element.gitbook.SummaryModifier.editArticleRef"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editArticleRef (summary, level, newRef)](#apidoc.element.gitbook.SummaryModifier.editArticleRef)
- description and source-code
```javascript
function editArticleRef(summary, level, newRef) {
    return mergeAtLevel(summary, level, {
        ref: newRef
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.editArticleTitle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editArticleTitle (summary, level, newTitle)](#apidoc.element.gitbook.SummaryModifier.editArticleTitle)
- description and source-code
```javascript
function editArticleTitle(summary, level, newTitle) {
    return mergeAtLevel(summary, level, {
        title: newTitle
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.editPartTitle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>editPartTitle (summary, index, newTitle)](#apidoc.element.gitbook.SummaryModifier.editPartTitle)
- description and source-code
```javascript
function editPartTitle(summary, index, newTitle) {
    var parts = summary.getParts();

    var part = parts.get(index);
    if (!part) {
        return summary;
    }

    part = part.set('title', newTitle);
    parts = parts.set(index, part);

    return summary.set('parts', parts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.insertArticle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>insertArticle (summary, article, level)](#apidoc.element.gitbook.SummaryModifier.insertArticle)
- description and source-code
```javascript
function insertArticle(summary, article, level) {
    article = SummaryArticle(article);
    level = is.string(level)? level : level.getLevel();

    var parent = summary.getParent(level);
    if (!parent) {
        return summary;
    }

    // Find the index to insert at
    var articles = parent.getArticles();
    var index = getLeafIndex(level);

    // Insert the article at the right index
    articles = articles.insert(index, article);

    // Reindex the level from here
    parent = parent.set('articles', articles);
    parent = indexArticleLevels(parent);

    return mergeAtLevel(summary, parent.getLevel(), parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.insertPart"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>insertPart (summary, part, index)](#apidoc.element.gitbook.SummaryModifier.insertPart)
- description and source-code
```javascript
function insertPart(summary, part, index) {
    part = SummaryPart(part);

    var parts = summary.getParts().insert(index, part);
    return indexLevels(summary.set('parts', parts));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.moveArticle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>moveArticle (summary, origin, target)](#apidoc.element.gitbook.SummaryModifier.moveArticle)
- description and source-code
```javascript
function moveArticle(summary, origin, target) {
    // Coerce to level
    var originLevel = is.string(origin)? origin : origin.getLevel();
    var targetLevel = is.string(target)? target : target.getLevel();
    var article = summary.getByLevel(originLevel);

    // Remove first
    var removed = removeArticle(summary, originLevel);
    return insertArticle(removed, article, targetLevel);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.moveArticleAfter"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>moveArticleAfter (summary, origin, afterTarget)](#apidoc.element.gitbook.SummaryModifier.moveArticleAfter)
- description and source-code
```javascript
function moveArticleAfter(summary, origin, afterTarget) {
    // Coerce to level
    var originLevel = is.string(origin)? origin : origin.getLevel();
    var afterTargetLevel = is.string(afterTarget)? afterTarget : afterTarget.getLevel();
    var article = summary.getByLevel(originLevel);

    var targetLevel = increment(afterTargetLevel);

    if (targetLevel < origin) {
        // Remove first
        var removed = removeArticle(summary, originLevel);
        // Insert then
        return insertArticle(removed, article, targetLevel);
    } else {
        // Insert right after first
        var inserted = insertArticle(summary, article, targetLevel);
        // Remove old one
        return removeArticle(inserted, originLevel);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.removeArticle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>removeArticle (summary, level)](#apidoc.element.gitbook.SummaryModifier.removeArticle)
- description and source-code
```javascript
function removeArticle(summary, level) {
    // Coerce to level
    level = is.string(level)? level : level.getLevel();

    var parent = summary.getParent(level);

    var articles = parent.getArticles();
    // Find the index to remove
    var index = articles.findIndex(function(art) {
        return art.getLevel() === level;
    });
    if (index === -1) {
        return summary;
    }

    // Remove from children
    articles = articles.remove(index);
    parent = parent.set('articles', articles);

    // Reindex the level from here
    parent = indexArticleLevels(parent);

    return mergeAtLevel(summary, parent.getLevel(), parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.removePart"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>removePart (summary, index)](#apidoc.element.gitbook.SummaryModifier.removePart)
- description and source-code
```javascript
function removePart(summary, index) {
    var parts = summary.getParts().remove(index);
    return indexLevels(summary.set('parts', parts));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.SummaryModifier.unshiftArticle"></a>[function <span class="apidocSignatureSpan">gitbook.SummaryModifier.</span>unshiftArticle (summary, article)](#apidoc.element.gitbook.SummaryModifier.unshiftArticle)
- description and source-code
```javascript
function unshiftArticle(summary, article) {
    article = SummaryArticle(article);

    var parts = summary.getParts();
    var part = parts.get(0) || SummaryPart();

    var articles = part.getArticles();
    articles = articles.unshift(article);
    part = part.set('articles', articles);

    parts = parts.set(0, part);
    summary = summary.set('parts', parts);

    return indexLevels(summary);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.browser"></a>[module gitbook.browser](#apidoc.module.gitbook.browser)

#### <a name="apidoc.element.gitbook.browser.Book"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>Book (values)](#apidoc.element.gitbook.browser.Book)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.Config"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>Config (values)](#apidoc.element.gitbook.browser.Config)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.FS"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>FS (values)](#apidoc.element.gitbook.browser.FS)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.File"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>File (values)](#apidoc.element.gitbook.browser.File)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.Glossary"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>Glossary (values)](#apidoc.element.gitbook.browser.Glossary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.Page"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>Page (values)](#apidoc.element.gitbook.browser.Page)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.PluginDependency"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>PluginDependency (values)](#apidoc.element.gitbook.browser.PluginDependency)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.browser.Summary"></a>[function <span class="apidocSignatureSpan">gitbook.browser.</span>Summary (values)](#apidoc.element.gitbook.browser.Summary)
- description and source-code
```javascript
function Record(values) {
  if (values instanceof RecordType) {
    return values;
  }
  if (!(this instanceof RecordType)) {
    return new RecordType(values);
  }
  if (!hasInitialized) {
    hasInitialized = true;
    var keys = Object.keys(defaultValues);
    setProps(RecordTypePrototype, keys);
    RecordTypePrototype.size = keys.length;
    RecordTypePrototype._name = name;
    RecordTypePrototype._keys = keys;
    RecordTypePrototype._defaultValues = defaultValues;
  }
  this._map = Map(values);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gitbook.gitbook"></a>[module gitbook.gitbook](#apidoc.module.gitbook.gitbook)

#### <a name="apidoc.element.gitbook.gitbook.satisfies"></a>[function <span class="apidocSignatureSpan">gitbook.gitbook.</span>satisfies (condition)](#apidoc.element.gitbook.gitbook.satisfies)
- description and source-code
```javascript
function satisfies(condition) {
    // Test with real version
    if (semver.satisfies(VERSION, condition)) return true;

    // Test with future stable release
    return semver.satisfies(VERSION_STABLE, condition);
}
```
- example usage
```shell
...
We can't directly use samver.satisfies since it will break all plugins when gitbook version is a prerelease (beta, alpha)

@param {String} condition
@return {Boolean}
*/
function satisfies(condition) {
// Test with real version
if (semver.satisfies(VERSION, condition)) return true;

// Test with future stable release
return semver.satisfies(VERSION_STABLE, condition);
}

module.exports = {
version: pkg.version,
...
```



# <a name="apidoc.module.gitbook.parsers"></a>[module gitbook.parsers](#apidoc.module.gitbook.parsers)

#### <a name="apidoc.element.gitbook.parsers.get"></a>[function <span class="apidocSignatureSpan">gitbook.parsers.</span>get (name)](#apidoc.element.gitbook.parsers.get)
- description and source-code
```javascript
function getParser(name) {
    return parsers.find(function(parser) {
        return parser.getName() === name;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.parsers.getByExt"></a>[function <span class="apidocSignatureSpan">gitbook.parsers.</span>getByExt (ext)](#apidoc.element.gitbook.parsers.getByExt)
- description and source-code
```javascript
function getParserByExt(ext) {
    return parsers.find(function(parser) {
        return parser.matchExtension(ext);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gitbook.parsers.getForFile"></a>[function <span class="apidocSignatureSpan">gitbook.parsers.</span>getForFile (filename)](#apidoc.element.gitbook.parsers.getForFile)
- description and source-code
```javascript
function getParserForFile(filename) {
    return getParserByExt(path.extname(filename));
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

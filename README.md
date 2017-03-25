# api documentation for  [less (v2.7.2)](http://lesscss.org)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-less.svg)](https://travis-ci.org/npmdoc/node-npmdoc-less)
#### Leaner CSS

[![NPM](https://nodei.co/npm/less.png?downloads=true)](https://www.npmjs.com/package/less)

[![apidoc](https://npmdoc.github.io/node-npmdoc-less/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-less_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-less/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-less/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Alexis Sellier",
        "email": "self@cloudhead.net"
    },
    "bin": {
        "lessc": "./bin/lessc"
    },
    "browser": "./dist/less.js",
    "bugs": {
        "url": "https://github.com/less/less.js/issues"
    },
    "contributors": [
        {
            "name": "The Core Less Team"
        }
    ],
    "dependencies": {
        "errno": "^0.1.1",
        "graceful-fs": "^4.1.2",
        "image-size": "~0.5.0",
        "mime": "^1.2.11",
        "mkdirp": "^0.5.0",
        "promise": "^7.1.1",
        "request": "^2.72.0",
        "source-map": "^0.5.3"
    },
    "description": "Leaner CSS",
    "devDependencies": {
        "diff": "^2.2.2",
        "grunt": "~0.4.5",
        "grunt-browserify": "^5.0.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-connect": "^1.0.2",
        "grunt-contrib-jasmine": "^1.0.3",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-jscs": "^2.8.0",
        "grunt-saucelabs": "^8.6.2",
        "grunt-shell": "^1.3.0",
        "jit-grunt": "^0.10.0",
        "phantomjs-prebuilt": "^2.1.7",
        "time-grunt": "^1.3.0"
    },
    "directories": {
        "test": "./test"
    },
    "dist": {
        "shasum": "368d6cc73e1fb03981183280918743c5dcf9b3df",
        "tarball": "https://registry.npmjs.org/less/-/less-2.7.2.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "ceb54053e7964342e6d9be44e24dad701d818098",
    "homepage": "http://lesscss.org",
    "jam": {
        "main": "./dist/less.js"
    },
    "keywords": [
        "compile less",
        "css nesting",
        "css variable",
        "css",
        "gradients css",
        "gradients css3",
        "less compiler",
        "less css",
        "less mixins",
        "less",
        "less.js",
        "lesscss",
        "mixins",
        "nested css",
        "parser",
        "preprocessor",
        "bootstrap css",
        "bootstrap less",
        "style",
        "styles",
        "stylesheet",
        "variables in css",
        "css less"
    ],
    "license": "Apache-2.0",
    "main": "index",
    "maintainers": [
        {
            "name": "agatronic",
            "email": "luke.a.page@gmail.com"
        },
        {
            "name": "cloudhead",
            "email": "self@cloudhead.net"
        },
        {
            "name": "matthew-dean",
            "email": "matthewdean.me@gmail.com"
        },
        {
            "name": "meri",
            "email": "sommeridevel@gmail.com"
        },
        {
            "name": "seven-phases-max",
            "email": "seven.phases.max@gmail.com"
        }
    ],
    "master": {
        "url": "https://github.com/less/less.js/blob/master/",
        "raw": "https://raw.githubusercontent.com/less/less.js/master/"
    },
    "name": "less",
    "optionalDependencies": {
        "errno": "^0.1.1",
        "graceful-fs": "^4.1.2",
        "image-size": "~0.5.0",
        "mime": "^1.2.11",
        "mkdirp": "^0.5.0",
        "promise": "^7.1.1",
        "request": "^2.72.0",
        "source-map": "^0.5.3"
    },
    "rawcurrent": "https://raw.github.com/less/less.js/v",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/less/less.js.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "sourcearchive": "https://github.com/less/less.js/archive/v",
    "version": "2.7.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module less](#apidoc.module.less)
1.  [function <span class="apidocSignatureSpan">less.</span>AbstractFileManager ()](#apidoc.element.less.AbstractFileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>Environment (externalEnvironment, fileManagers)](#apidoc.element.less.Environment)
1.  [function <span class="apidocSignatureSpan">less.</span>FileManager ()](#apidoc.element.less.FileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>ImportManager (context, rootFileInfo)](#apidoc.element.less.ImportManager)
1.  [function <span class="apidocSignatureSpan">less.</span>LessError (e, importManager, currentFilename)](#apidoc.element.less.LessError)
1.  [function <span class="apidocSignatureSpan">less.</span>ParseTree (root, imports)](#apidoc.element.less.ParseTree)
1.  [function <span class="apidocSignatureSpan">less.</span>Parser (context, imports, fileInfo)](#apidoc.element.less.Parser)
1.  [function <span class="apidocSignatureSpan">less.</span>PluginLoader (less)](#apidoc.element.less.PluginLoader)
1.  [function <span class="apidocSignatureSpan">less.</span>PluginManager (less)](#apidoc.element.less.PluginManager)
1.  [function <span class="apidocSignatureSpan">less.</span>SourceMapBuilder (options)](#apidoc.element.less.SourceMapBuilder)
1.  [function <span class="apidocSignatureSpan">less.</span>SourceMapOutput (options)](#apidoc.element.less.SourceMapOutput)
1.  [function <span class="apidocSignatureSpan">less.</span>UrlFileManager ()](#apidoc.element.less.UrlFileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>contexts.Eval (options, frames)](#apidoc.element.less.contexts.Eval)
1.  [function <span class="apidocSignatureSpan">less.</span>createFromEnvironment (environment, fileManagers)](#apidoc.element.less.createFromEnvironment)
1.  [function <span class="apidocSignatureSpan">less.</span>formatError (ctx, options)](#apidoc.element.less.formatError)
1.  [function <span class="apidocSignatureSpan">less.</span>fs.ReadStream (path, options)](#apidoc.element.less.fs.ReadStream)
1.  [function <span class="apidocSignatureSpan">less.</span>fs.Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats)
1.  [function <span class="apidocSignatureSpan">less.</span>fs.WriteStream (path, options)](#apidoc.element.less.fs.WriteStream)
1.  [function <span class="apidocSignatureSpan">less.</span>functions.functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller)
1.  [function <span class="apidocSignatureSpan">less.</span>parse (input, options, callback)](#apidoc.element.less.parse)
1.  [function <span class="apidocSignatureSpan">less.</span>render (input, options, callback)](#apidoc.element.less.render)
1.  [function <span class="apidocSignatureSpan">less.</span>transformTree (root, options)](#apidoc.element.less.transformTree)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Alpha (val)](#apidoc.element.less.tree.Alpha)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Assignment (key, val)](#apidoc.element.less.tree.Assignment)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Attribute (key, op, value)](#apidoc.element.less.tree.Attribute)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Combinator (value)](#apidoc.element.less.tree.Combinator)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Dimension (value, unit)](#apidoc.element.less.tree.Dimension)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Expression (value)](#apidoc.element.less.tree.Expression)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Keyword (value)](#apidoc.element.less.tree.Keyword)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Negative (node)](#apidoc.element.less.tree.Negative)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Node ()](#apidoc.element.less.tree.Node)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Paren (node)](#apidoc.element.less.tree.Paren)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Value (value)](#apidoc.element.less.tree.Value)
1.  [function <span class="apidocSignatureSpan">less.</span>tree.Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor)
1.  [function <span class="apidocSignatureSpan">less.</span>visitors.Visitor (implementation)](#apidoc.element.less.visitors.Visitor)
1.  [function <span class="apidocSignatureSpan">less.</span>writeError (ctx, options)](#apidoc.element.less.writeError)
1.  object <span class="apidocSignatureSpan">less.</span>AbstractFileManager.prototype
1.  object <span class="apidocSignatureSpan">less.</span>Environment.prototype
1.  object <span class="apidocSignatureSpan">less.</span>FileManager.prototype
1.  object <span class="apidocSignatureSpan">less.</span>ImportManager.prototype
1.  object <span class="apidocSignatureSpan">less.</span>LessError.prototype
1.  object <span class="apidocSignatureSpan">less.</span>ParseTree.prototype
1.  object <span class="apidocSignatureSpan">less.</span>PluginLoader.prototype
1.  object <span class="apidocSignatureSpan">less.</span>PluginManager.prototype
1.  object <span class="apidocSignatureSpan">less.</span>SourceMapBuilder.prototype
1.  object <span class="apidocSignatureSpan">less.</span>SourceMapOutput.prototype
1.  object <span class="apidocSignatureSpan">less.</span>UrlFileManager.prototype
1.  object <span class="apidocSignatureSpan">less.</span>contexts
1.  object <span class="apidocSignatureSpan">less.</span>contexts.Eval.prototype
1.  object <span class="apidocSignatureSpan">less.</span>data
1.  object <span class="apidocSignatureSpan">less.</span>environment
1.  object <span class="apidocSignatureSpan">less.</span>fs
1.  object <span class="apidocSignatureSpan">less.</span>fs.ReadStream.prototype
1.  object <span class="apidocSignatureSpan">less.</span>fs.Stats.prototype
1.  object <span class="apidocSignatureSpan">less.</span>fs.WriteStream.prototype
1.  object <span class="apidocSignatureSpan">less.</span>functions
1.  object <span class="apidocSignatureSpan">less.</span>functions.functionCaller.prototype
1.  object <span class="apidocSignatureSpan">less.</span>functions.functionRegistry
1.  object <span class="apidocSignatureSpan">less.</span>lesscHelper
1.  object <span class="apidocSignatureSpan">less.</span>logger
1.  object <span class="apidocSignatureSpan">less.</span>tree
1.  object <span class="apidocSignatureSpan">less.</span>tree.Alpha.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Anonymous.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Assignment.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Attribute.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Call.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Color.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Combinator.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Comment.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Condition.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.DetachedRuleset.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Dimension.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Directive.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Element.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Expression.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Extend.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Import.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.JavaScript.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Keyword.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Media.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Negative.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Node.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Operation.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Paren.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Quoted.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Rule.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Ruleset.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.RulesetCall.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Selector.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.URL.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Unit.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Value.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.Variable.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.mixin
1.  object <span class="apidocSignatureSpan">less.</span>tree.mixin.Call.prototype
1.  object <span class="apidocSignatureSpan">less.</span>tree.mixin.Definition.prototype
1.  object <span class="apidocSignatureSpan">less.</span>utils
1.  object <span class="apidocSignatureSpan">less.</span>version
1.  object <span class="apidocSignatureSpan">less.</span>visitors
1.  object <span class="apidocSignatureSpan">less.</span>visitors.ExtendVisitor.prototype
1.  object <span class="apidocSignatureSpan">less.</span>visitors.ImportVisitor.prototype
1.  object <span class="apidocSignatureSpan">less.</span>visitors.JoinSelectorVisitor.prototype
1.  object <span class="apidocSignatureSpan">less.</span>visitors.MarkVisibleSelectorsVisitor.prototype
1.  object <span class="apidocSignatureSpan">less.</span>visitors.ToCSSVisitor.prototype
1.  object <span class="apidocSignatureSpan">less.</span>visitors.Visitor.prototype

#### [module less.AbstractFileManager](#apidoc.module.less.AbstractFileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>AbstractFileManager ()](#apidoc.element.less.AbstractFileManager.AbstractFileManager)

#### [module less.AbstractFileManager.prototype](#apidoc.module.less.AbstractFileManager.prototype)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>alwaysMakePathsAbsolute ()](#apidoc.element.less.AbstractFileManager.prototype.alwaysMakePathsAbsolute)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>extractUrlParts (url, baseUrl)](#apidoc.element.less.AbstractFileManager.prototype.extractUrlParts)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>getPath (filename)](#apidoc.element.less.AbstractFileManager.prototype.getPath)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>isPathAbsolute (filename)](#apidoc.element.less.AbstractFileManager.prototype.isPathAbsolute)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>join (basePath, laterPath)](#apidoc.element.less.AbstractFileManager.prototype.join)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>pathDiff (url, baseUrl)](#apidoc.element.less.AbstractFileManager.prototype.pathDiff)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>supportsSync ()](#apidoc.element.less.AbstractFileManager.prototype.supportsSync)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>tryAppendExtension (path, ext)](#apidoc.element.less.AbstractFileManager.prototype.tryAppendExtension)
1.  [function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>tryAppendLessExtension (path)](#apidoc.element.less.AbstractFileManager.prototype.tryAppendLessExtension)

#### [module less.Environment](#apidoc.module.less.Environment)
1.  [function <span class="apidocSignatureSpan">less.</span>Environment (externalEnvironment, fileManagers)](#apidoc.element.less.Environment.Environment)

#### [module less.Environment.prototype](#apidoc.module.less.Environment.prototype)
1.  [function <span class="apidocSignatureSpan">less.Environment.prototype.</span>addFileManager (fileManager)](#apidoc.element.less.Environment.prototype.addFileManager)
1.  [function <span class="apidocSignatureSpan">less.Environment.prototype.</span>clearFileManagers ()](#apidoc.element.less.Environment.prototype.clearFileManagers)
1.  [function <span class="apidocSignatureSpan">less.Environment.prototype.</span>getFileManager (filename, currentDirectory, options, environment, isSync)](#apidoc.element.less.Environment.prototype.getFileManager)

#### [module less.FileManager](#apidoc.module.less.FileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>FileManager ()](#apidoc.element.less.FileManager.FileManager)

#### [module less.FileManager.prototype](#apidoc.module.less.FileManager.prototype)
1.  [function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>loadFile (filename, currentDirectory, options, environment, callback)](#apidoc.element.less.FileManager.prototype.loadFile)
1.  [function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>loadFileSync (filename, currentDirectory, options, environment, encoding)](#apidoc.element.less.FileManager.prototype.loadFileSync)
1.  [function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>supports (filename, currentDirectory, options, environment)](#apidoc.element.less.FileManager.prototype.supports)
1.  [function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>supportsSync (filename, currentDirectory, options, environment)](#apidoc.element.less.FileManager.prototype.supportsSync)

#### [module less.ImportManager](#apidoc.module.less.ImportManager)
1.  [function <span class="apidocSignatureSpan">less.</span>ImportManager (context, rootFileInfo)](#apidoc.element.less.ImportManager.ImportManager)

#### [module less.ImportManager.prototype](#apidoc.module.less.ImportManager.prototype)
1.  [function <span class="apidocSignatureSpan">less.ImportManager.prototype.</span>push (path, tryAppendLessExtension, currentFileInfo, importOptions, callback)](#apidoc.element.less.ImportManager.prototype.push)

#### [module less.LessError](#apidoc.module.less.LessError)
1.  [function <span class="apidocSignatureSpan">less.</span>LessError (e, importManager, currentFilename)](#apidoc.element.less.LessError.LessError)

#### [module less.LessError.prototype](#apidoc.module.less.LessError.prototype)
1.  [function <span class="apidocSignatureSpan">less.LessError.prototype.</span>constructor (e, importManager, currentFilename)](#apidoc.element.less.LessError.prototype.constructor)

#### [module less.ParseTree](#apidoc.module.less.ParseTree)
1.  [function <span class="apidocSignatureSpan">less.</span>ParseTree (root, imports)](#apidoc.element.less.ParseTree.ParseTree)

#### [module less.ParseTree.prototype](#apidoc.module.less.ParseTree.prototype)
1.  [function <span class="apidocSignatureSpan">less.ParseTree.prototype.</span>toCSS (options)](#apidoc.element.less.ParseTree.prototype.toCSS)

#### [module less.Parser](#apidoc.module.less.Parser)
1.  [function <span class="apidocSignatureSpan">less.</span>Parser (context, imports, fileInfo)](#apidoc.element.less.Parser.Parser)
1.  [function <span class="apidocSignatureSpan">less.Parser.</span>serializeVars (vars)](#apidoc.element.less.Parser.serializeVars)

#### [module less.PluginLoader](#apidoc.module.less.PluginLoader)
1.  [function <span class="apidocSignatureSpan">less.</span>PluginLoader (less)](#apidoc.element.less.PluginLoader.PluginLoader)

#### [module less.PluginLoader.prototype](#apidoc.module.less.PluginLoader.prototype)
1.  [function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>compareVersion (aVersion, bVersion)](#apidoc.element.less.PluginLoader.prototype.compareVersion)
1.  [function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>printUsage (plugins)](#apidoc.element.less.PluginLoader.prototype.printUsage)
1.  [function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>tryLoadPlugin (name, argument)](#apidoc.element.less.PluginLoader.prototype.tryLoadPlugin)
1.  [function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>tryRequirePlugin (name)](#apidoc.element.less.PluginLoader.prototype.tryRequirePlugin)
1.  [function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>versionToString (version)](#apidoc.element.less.PluginLoader.prototype.versionToString)

#### [module less.PluginManager](#apidoc.module.less.PluginManager)
1.  [function <span class="apidocSignatureSpan">less.</span>PluginManager (less)](#apidoc.element.less.PluginManager.PluginManager)

#### [module less.PluginManager.prototype](#apidoc.module.less.PluginManager.prototype)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addFileManager (manager)](#apidoc.element.less.PluginManager.prototype.addFileManager)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPlugin (plugin)](#apidoc.element.less.PluginManager.prototype.addPlugin)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPlugins (plugins)](#apidoc.element.less.PluginManager.prototype.addPlugins)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPostProcessor (postProcessor, priority)](#apidoc.element.less.PluginManager.prototype.addPostProcessor)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPreProcessor (preProcessor, priority)](#apidoc.element.less.PluginManager.prototype.addPreProcessor)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addVisitor (visitor)](#apidoc.element.less.PluginManager.prototype.addVisitor)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getFileManagers ()](#apidoc.element.less.PluginManager.prototype.getFileManagers)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getPostProcessors ()](#apidoc.element.less.PluginManager.prototype.getPostProcessors)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getPreProcessors ()](#apidoc.element.less.PluginManager.prototype.getPreProcessors)
1.  [function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getVisitors ()](#apidoc.element.less.PluginManager.prototype.getVisitors)

#### [module less.SourceMapBuilder](#apidoc.module.less.SourceMapBuilder)
1.  [function <span class="apidocSignatureSpan">less.</span>SourceMapBuilder (options)](#apidoc.element.less.SourceMapBuilder.SourceMapBuilder)

#### [module less.SourceMapBuilder.prototype](#apidoc.module.less.SourceMapBuilder.prototype)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getCSSAppendage ()](#apidoc.element.less.SourceMapBuilder.prototype.getCSSAppendage)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getExternalSourceMap ()](#apidoc.element.less.SourceMapBuilder.prototype.getExternalSourceMap)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getInputFilename ()](#apidoc.element.less.SourceMapBuilder.prototype.getInputFilename)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getOutputFilename ()](#apidoc.element.less.SourceMapBuilder.prototype.getOutputFilename)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getSourceMapURL ()](#apidoc.element.less.SourceMapBuilder.prototype.getSourceMapURL)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>isInline ()](#apidoc.element.less.SourceMapBuilder.prototype.isInline)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>setExternalSourceMap (sourceMap)](#apidoc.element.less.SourceMapBuilder.prototype.setExternalSourceMap)
1.  [function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>toCSS (rootNode, options, imports)](#apidoc.element.less.SourceMapBuilder.prototype.toCSS)

#### [module less.SourceMapOutput](#apidoc.module.less.SourceMapOutput)
1.  [function <span class="apidocSignatureSpan">less.</span>SourceMapOutput (options)](#apidoc.element.less.SourceMapOutput.SourceMapOutput)

#### [module less.SourceMapOutput.prototype](#apidoc.module.less.SourceMapOutput.prototype)
1.  [function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>add (chunk, fileInfo, index, mapLines)](#apidoc.element.less.SourceMapOutput.prototype.add)
1.  [function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>isEmpty ()](#apidoc.element.less.SourceMapOutput.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>normalizeFilename (filename)](#apidoc.element.less.SourceMapOutput.prototype.normalizeFilename)
1.  [function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>toCSS (context)](#apidoc.element.less.SourceMapOutput.prototype.toCSS)

#### [module less.UrlFileManager](#apidoc.module.less.UrlFileManager)
1.  [function <span class="apidocSignatureSpan">less.</span>UrlFileManager ()](#apidoc.element.less.UrlFileManager.UrlFileManager)

#### [module less.UrlFileManager.prototype](#apidoc.module.less.UrlFileManager.prototype)
1.  [function <span class="apidocSignatureSpan">less.UrlFileManager.prototype.</span>loadFile (filename, currentDirectory, options, environment)](#apidoc.element.less.UrlFileManager.prototype.loadFile)
1.  [function <span class="apidocSignatureSpan">less.UrlFileManager.prototype.</span>supports (filename, currentDirectory, options, environment)](#apidoc.element.less.UrlFileManager.prototype.supports)

#### [module less.contexts](#apidoc.module.less.contexts)
1.  [function <span class="apidocSignatureSpan">less.contexts.</span>Eval (options, frames)](#apidoc.element.less.contexts.Eval)
1.  [function <span class="apidocSignatureSpan">less.contexts.</span>Parse (options)](#apidoc.element.less.contexts.Parse)

#### [module less.contexts.Eval](#apidoc.module.less.contexts.Eval)
1.  [function <span class="apidocSignatureSpan">less.contexts.</span>Eval (options, frames)](#apidoc.element.less.contexts.Eval.Eval)

#### [module less.contexts.Eval.prototype](#apidoc.module.less.contexts.Eval.prototype)
1.  [function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>inParenthesis ()](#apidoc.element.less.contexts.Eval.prototype.inParenthesis)
1.  [function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>isMathOn ()](#apidoc.element.less.contexts.Eval.prototype.isMathOn)
1.  [function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>isPathRelative (path)](#apidoc.element.less.contexts.Eval.prototype.isPathRelative)
1.  [function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>normalizePath ( path )](#apidoc.element.less.contexts.Eval.prototype.normalizePath)
1.  [function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>outOfParenthesis ()](#apidoc.element.less.contexts.Eval.prototype.outOfParenthesis)

#### [module less.environment](#apidoc.module.less.environment)
1.  [function <span class="apidocSignatureSpan">less.environment.</span>charsetLookup ()](#apidoc.element.less.environment.charsetLookup)
1.  [function <span class="apidocSignatureSpan">less.environment.</span>encodeBase64 ()](#apidoc.element.less.environment.encodeBase64)
1.  [function <span class="apidocSignatureSpan">less.environment.</span>getSourceMapGenerator ()](#apidoc.element.less.environment.getSourceMapGenerator)
1.  [function <span class="apidocSignatureSpan">less.environment.</span>mimeLookup ()](#apidoc.element.less.environment.mimeLookup)
1.  object <span class="apidocSignatureSpan">less.environment.</span>fileManagers

#### [module less.fs](#apidoc.module.less.fs)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>FileReadStream (path, options)](#apidoc.element.less.fs.FileReadStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>FileWriteStream (path, options)](#apidoc.element.less.fs.FileWriteStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>ReadStream (path, options)](#apidoc.element.less.fs.ReadStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>WriteStream (path, options)](#apidoc.element.less.fs.WriteStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>_toUnixTimestamp (time)](#apidoc.element.less.fs._toUnixTimestamp)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>access (path, mode, callback)](#apidoc.element.less.fs.access)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>accessSync (path, mode)](#apidoc.element.less.fs.accessSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>appendFile (path, data, options, cb)](#apidoc.element.less.fs.appendFile)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>appendFileSync (path, data, options)](#apidoc.element.less.fs.appendFileSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>chmod (target, mode, cb)](#apidoc.element.less.fs.chmod)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>chmodSync (target, mode)](#apidoc.element.less.fs.chmodSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>chown (target, uid, gid, cb)](#apidoc.element.less.fs.chown)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>chownSync (target, uid, gid)](#apidoc.element.less.fs.chownSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>close (fd, cb)](#apidoc.element.less.fs.close)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>closeSync (fd)](#apidoc.element.less.fs.closeSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>createReadStream (path, options)](#apidoc.element.less.fs.createReadStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>createWriteStream (path, options)](#apidoc.element.less.fs.createWriteStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>exists (path, callback)](#apidoc.element.less.fs.exists)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>existsSync (path)](#apidoc.element.less.fs.existsSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fchmod (target, mode, cb)](#apidoc.element.less.fs.fchmod)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fchmodSync (target, mode)](#apidoc.element.less.fs.fchmodSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fchown (target, uid, gid, cb)](#apidoc.element.less.fs.fchown)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fchownSync (target, uid, gid)](#apidoc.element.less.fs.fchownSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fdatasync (fd, callback)](#apidoc.element.less.fs.fdatasync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fdatasyncSync (fd)](#apidoc.element.less.fs.fdatasyncSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fstat (target, cb)](#apidoc.element.less.fs.fstat)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fstatSync (target)](#apidoc.element.less.fs.fstatSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fsync (fd, callback)](#apidoc.element.less.fs.fsync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>fsyncSync (fd)](#apidoc.element.less.fs.fsyncSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>ftruncate (fd, len, callback)](#apidoc.element.less.fs.ftruncate)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>ftruncateSync (fd, len)](#apidoc.element.less.fs.ftruncateSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>futimes (fd, atime, mtime, callback)](#apidoc.element.less.fs.futimes)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>futimesSync (fd, atime, mtime)](#apidoc.element.less.fs.futimesSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>gracefulify (fs)](#apidoc.element.less.fs.gracefulify)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lchmod (path, mode, cb)](#apidoc.element.less.fs.lchmod)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lchmodSync ()](#apidoc.element.less.fs.lchmodSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lchown (path, uid, gid, cb)](#apidoc.element.less.fs.lchown)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lchownSync ()](#apidoc.element.less.fs.lchownSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>link (existingPath, newPath, callback)](#apidoc.element.less.fs.link)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>linkSync (existingPath, newPath)](#apidoc.element.less.fs.linkSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lstat (target, cb)](#apidoc.element.less.fs.lstat)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lstatSync (target)](#apidoc.element.less.fs.lstatSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lutimes (_a, _b, _c, cb)](#apidoc.element.less.fs.lutimes)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>lutimesSync ()](#apidoc.element.less.fs.lutimesSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>mkdir (path, mode, callback)](#apidoc.element.less.fs.mkdir)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>mkdirSync (path, mode)](#apidoc.element.less.fs.mkdirSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>mkdtemp (prefix, options, callback)](#apidoc.element.less.fs.mkdtemp)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>mkdtempSync (prefix, options)](#apidoc.element.less.fs.mkdtempSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>open (path, flags, mode, cb)](#apidoc.element.less.fs.open)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>openSync (path, flags, mode)](#apidoc.element.less.fs.openSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>read (fd, buffer, offset, length, position, callback_)](#apidoc.element.less.fs.read)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readFile (path, options, cb)](#apidoc.element.less.fs.readFile)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readFileSync (path, options)](#apidoc.element.less.fs.readFileSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readSync (fd, buffer, offset, length, position)](#apidoc.element.less.fs.readSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readdir (path, options, cb)](#apidoc.element.less.fs.readdir)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readdirSync (path, options)](#apidoc.element.less.fs.readdirSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readlink (path, options, callback)](#apidoc.element.less.fs.readlink)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>readlinkSync (path, options)](#apidoc.element.less.fs.readlinkSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>realpath (p, options, callback)](#apidoc.element.less.fs.realpath)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>realpathSync (p, options)](#apidoc.element.less.fs.realpathSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>rename (oldPath, newPath, callback)](#apidoc.element.less.fs.rename)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>renameSync (oldPath, newPath)](#apidoc.element.less.fs.renameSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>rmdir (path, callback)](#apidoc.element.less.fs.rmdir)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>rmdirSync (path)](#apidoc.element.less.fs.rmdirSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>stat (target, cb)](#apidoc.element.less.fs.stat)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>statSync (target)](#apidoc.element.less.fs.statSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>symlink (target, path, type_, callback_)](#apidoc.element.less.fs.symlink)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>symlinkSync (target, path, type)](#apidoc.element.less.fs.symlinkSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>truncate (path, len, callback)](#apidoc.element.less.fs.truncate)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>truncateSync (path, len)](#apidoc.element.less.fs.truncateSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>unlink (path, callback)](#apidoc.element.less.fs.unlink)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>unlinkSync (path)](#apidoc.element.less.fs.unlinkSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>unwatchFile (filename, listener)](#apidoc.element.less.fs.unwatchFile)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>utimes (path, atime, mtime, callback)](#apidoc.element.less.fs.utimes)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>utimesSync (path, atime, mtime)](#apidoc.element.less.fs.utimesSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>watch (filename, options, listener)](#apidoc.element.less.fs.watch)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>watchFile (filename, options, listener)](#apidoc.element.less.fs.watchFile)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>write (fd, buffer, offset, length, position, callback)](#apidoc.element.less.fs.write)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>writeFile (path, data, options, cb)](#apidoc.element.less.fs.writeFile)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>writeFileSync (path, data, options)](#apidoc.element.less.fs.writeFileSync)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>writeSync (fd, buffer, offset, length, position)](#apidoc.element.less.fs.writeSync)
1.  number <span class="apidocSignatureSpan">less.fs.</span>F_OK
1.  number <span class="apidocSignatureSpan">less.fs.</span>R_OK
1.  number <span class="apidocSignatureSpan">less.fs.</span>W_OK
1.  number <span class="apidocSignatureSpan">less.fs.</span>X_OK
1.  object <span class="apidocSignatureSpan">less.fs.</span>constants

#### [module less.fs.ReadStream](#apidoc.module.less.fs.ReadStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>ReadStream (path, options)](#apidoc.element.less.fs.ReadStream.ReadStream)

#### [module less.fs.ReadStream.prototype](#apidoc.module.less.fs.ReadStream.prototype)
1.  [function <span class="apidocSignatureSpan">less.fs.ReadStream.prototype.</span>open ()](#apidoc.element.less.fs.ReadStream.prototype.open)

#### [module less.fs.Stats](#apidoc.module.less.fs.Stats)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats.Stats)

#### [module less.fs.Stats.prototype](#apidoc.module.less.fs.Stats.prototype)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>_checkModeProperty (property)](#apidoc.element.less.fs.Stats.prototype._checkModeProperty)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isBlockDevice ()](#apidoc.element.less.fs.Stats.prototype.isBlockDevice)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isCharacterDevice ()](#apidoc.element.less.fs.Stats.prototype.isCharacterDevice)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isDirectory ()](#apidoc.element.less.fs.Stats.prototype.isDirectory)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isFIFO ()](#apidoc.element.less.fs.Stats.prototype.isFIFO)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isFile ()](#apidoc.element.less.fs.Stats.prototype.isFile)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isSocket ()](#apidoc.element.less.fs.Stats.prototype.isSocket)
1.  [function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isSymbolicLink ()](#apidoc.element.less.fs.Stats.prototype.isSymbolicLink)

#### [module less.fs.WriteStream](#apidoc.module.less.fs.WriteStream)
1.  [function <span class="apidocSignatureSpan">less.fs.</span>WriteStream (path, options)](#apidoc.element.less.fs.WriteStream.WriteStream)

#### [module less.fs.WriteStream.prototype](#apidoc.module.less.fs.WriteStream.prototype)
1.  [function <span class="apidocSignatureSpan">less.fs.WriteStream.prototype.</span>open ()](#apidoc.element.less.fs.WriteStream.prototype.open)

#### [module less.functions](#apidoc.module.less.functions)
1.  [function <span class="apidocSignatureSpan">less.functions.</span>functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller)
1.  object <span class="apidocSignatureSpan">less.functions.</span>functionRegistry

#### [module less.functions.functionCaller](#apidoc.module.less.functions.functionCaller)
1.  [function <span class="apidocSignatureSpan">less.functions.</span>functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller.functionCaller)

#### [module less.functions.functionCaller.prototype](#apidoc.module.less.functions.functionCaller.prototype)
1.  [function <span class="apidocSignatureSpan">less.functions.functionCaller.prototype.</span>call (args)](#apidoc.element.less.functions.functionCaller.prototype.call)
1.  [function <span class="apidocSignatureSpan">less.functions.functionCaller.prototype.</span>isValid ()](#apidoc.element.less.functions.functionCaller.prototype.isValid)

#### [module less.functions.functionRegistry](#apidoc.module.less.functions.functionRegistry)
1.  [function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>add (name, func)](#apidoc.element.less.functions.functionRegistry.add)
1.  [function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>addMultiple (functions)](#apidoc.element.less.functions.functionRegistry.addMultiple)
1.  [function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>get (name)](#apidoc.element.less.functions.functionRegistry.get)
1.  [function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>inherit ()](#apidoc.element.less.functions.functionRegistry.inherit)
1.  object <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>_data

#### [module less.lesscHelper](#apidoc.module.less.lesscHelper)
1.  [function <span class="apidocSignatureSpan">less.lesscHelper.</span>printUsage ()](#apidoc.element.less.lesscHelper.printUsage)
1.  [function <span class="apidocSignatureSpan">less.lesscHelper.</span>stylize (str, style)](#apidoc.element.less.lesscHelper.stylize)

#### [module less.logger](#apidoc.module.less.logger)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>_fireEvent (type, msg)](#apidoc.element.less.logger._fireEvent)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>addListener (listener)](#apidoc.element.less.logger.addListener)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>debug (msg)](#apidoc.element.less.logger.debug)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>error (msg)](#apidoc.element.less.logger.error)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>info (msg)](#apidoc.element.less.logger.info)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>removeListener (listener)](#apidoc.element.less.logger.removeListener)
1.  [function <span class="apidocSignatureSpan">less.logger.</span>warn (msg)](#apidoc.element.less.logger.warn)
1.  object <span class="apidocSignatureSpan">less.logger.</span>_listeners

#### [module less.tree](#apidoc.module.less.tree)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Alpha (val)](#apidoc.element.less.tree.Alpha)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Assignment (key, val)](#apidoc.element.less.tree.Assignment)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Attribute (key, op, value)](#apidoc.element.less.tree.Attribute)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Combinator (value)](#apidoc.element.less.tree.Combinator)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Dimension (value, unit)](#apidoc.element.less.tree.Dimension)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Expression (value)](#apidoc.element.less.tree.Expression)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Keyword (value)](#apidoc.element.less.tree.Keyword)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Negative (node)](#apidoc.element.less.tree.Negative)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Node ()](#apidoc.element.less.tree.Node)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Paren (node)](#apidoc.element.less.tree.Paren)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>UnicodeDescriptor (value)](#apidoc.element.less.tree.UnicodeDescriptor)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Value (value)](#apidoc.element.less.tree.Value)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable)
1.  object <span class="apidocSignatureSpan">less.tree.</span>mixin

#### [module less.tree.Alpha](#apidoc.module.less.tree.Alpha)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Alpha (val)](#apidoc.element.less.tree.Alpha.Alpha)

#### [module less.tree.Alpha.prototype](#apidoc.module.less.tree.Alpha.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Alpha.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>eval (context)](#apidoc.element.less.tree.Alpha.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Alpha.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>type

#### [module less.tree.Anonymous](#apidoc.module.less.tree.Anonymous)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous.Anonymous)

#### [module less.tree.Anonymous.prototype](#apidoc.module.less.tree.Anonymous.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>compare (other)](#apidoc.element.less.tree.Anonymous.prototype.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>eval ()](#apidoc.element.less.tree.Anonymous.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Anonymous.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>isRulesetLike ()](#apidoc.element.less.tree.Anonymous.prototype.isRulesetLike)
1.  string <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>type

#### [module less.tree.Assignment](#apidoc.module.less.tree.Assignment)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Assignment (key, val)](#apidoc.element.less.tree.Assignment.Assignment)

#### [module less.tree.Assignment.prototype](#apidoc.module.less.tree.Assignment.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Assignment.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>eval (context)](#apidoc.element.less.tree.Assignment.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Assignment.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>type

#### [module less.tree.Attribute](#apidoc.module.less.tree.Attribute)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Attribute (key, op, value)](#apidoc.element.less.tree.Attribute.Attribute)

#### [module less.tree.Attribute.prototype](#apidoc.module.less.tree.Attribute.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>eval (context)](#apidoc.element.less.tree.Attribute.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Attribute.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Attribute.prototype.toCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>type

#### [module less.tree.Call](#apidoc.module.less.tree.Call)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call.Call)

#### [module less.tree.Call.prototype](#apidoc.module.less.tree.Call.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Call.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>eval (context)](#apidoc.element.less.tree.Call.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Call.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>type

#### [module less.tree.Color](#apidoc.module.less.tree.Color)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color.Color)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.</span>fromKeyword (keyword)](#apidoc.element.less.tree.Color.fromKeyword)

#### [module less.tree.Color.prototype](#apidoc.module.less.tree.Color.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>compare (x)](#apidoc.element.less.tree.Color.prototype.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Color.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>luma ()](#apidoc.element.less.tree.Color.prototype.luma)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>operate (context, op, other)](#apidoc.element.less.tree.Color.prototype.operate)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toARGB ()](#apidoc.element.less.tree.Color.prototype.toARGB)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toCSS (context, doNotCompress)](#apidoc.element.less.tree.Color.prototype.toCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toHSL ()](#apidoc.element.less.tree.Color.prototype.toHSL)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toHSV ()](#apidoc.element.less.tree.Color.prototype.toHSV)
1.  [function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toRGB ()](#apidoc.element.less.tree.Color.prototype.toRGB)
1.  string <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>type

#### [module less.tree.Combinator](#apidoc.module.less.tree.Combinator)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Combinator (value)](#apidoc.element.less.tree.Combinator.Combinator)

#### [module less.tree.Combinator.prototype](#apidoc.module.less.tree.Combinator.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Combinator.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Combinator.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Combinator.prototype.</span>type

#### [module less.tree.Comment](#apidoc.module.less.tree.Comment)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment.Comment)

#### [module less.tree.Comment.prototype](#apidoc.module.less.tree.Comment.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Comment.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Comment.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Comment.prototype.</span>isSilent (context)](#apidoc.element.less.tree.Comment.prototype.isSilent)
1.  string <span class="apidocSignatureSpan">less.tree.Comment.prototype.</span>type

#### [module less.tree.Condition](#apidoc.module.less.tree.Condition)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition.Condition)

#### [module less.tree.Condition.prototype](#apidoc.module.less.tree.Condition.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Condition.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Condition.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Condition.prototype.</span>eval (context)](#apidoc.element.less.tree.Condition.prototype.eval)
1.  string <span class="apidocSignatureSpan">less.tree.Condition.prototype.</span>type

#### [module less.tree.DetachedRuleset](#apidoc.module.less.tree.DetachedRuleset)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset.DetachedRuleset)

#### [module less.tree.DetachedRuleset.prototype](#apidoc.module.less.tree.DetachedRuleset.prototype)
1.  boolean <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>evalFirst
1.  [function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>accept (visitor)](#apidoc.element.less.tree.DetachedRuleset.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>callEval (context)](#apidoc.element.less.tree.DetachedRuleset.prototype.callEval)
1.  [function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>eval (context)](#apidoc.element.less.tree.DetachedRuleset.prototype.eval)
1.  string <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>type

#### [module less.tree.Dimension](#apidoc.module.less.tree.Dimension)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Dimension (value, unit)](#apidoc.element.less.tree.Dimension.Dimension)

#### [module less.tree.Dimension.prototype](#apidoc.module.less.tree.Dimension.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Dimension.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>compare (other)](#apidoc.element.less.tree.Dimension.prototype.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>convertTo (conversions)](#apidoc.element.less.tree.Dimension.prototype.convertTo)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>eval (context)](#apidoc.element.less.tree.Dimension.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Dimension.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>operate (context, op, other)](#apidoc.element.less.tree.Dimension.prototype.operate)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>toColor ()](#apidoc.element.less.tree.Dimension.prototype.toColor)
1.  [function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>unify ()](#apidoc.element.less.tree.Dimension.prototype.unify)
1.  string <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>type

#### [module less.tree.Directive](#apidoc.module.less.tree.Directive)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive.Directive)

#### [module less.tree.Directive.prototype](#apidoc.module.less.tree.Directive.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Directive.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>eval (context)](#apidoc.element.less.tree.Directive.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>find ()](#apidoc.element.less.tree.Directive.prototype.find)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Directive.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>isCharset ()](#apidoc.element.less.tree.Directive.prototype.isCharset)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>isRulesetLike ()](#apidoc.element.less.tree.Directive.prototype.isRulesetLike)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>outputRuleset (context, output, rules)](#apidoc.element.less.tree.Directive.prototype.outputRuleset)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>rulesets ()](#apidoc.element.less.tree.Directive.prototype.rulesets)
1.  [function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>variable (name)](#apidoc.element.less.tree.Directive.prototype.variable)
1.  string <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>type

#### [module less.tree.Element](#apidoc.module.less.tree.Element)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element.Element)

#### [module less.tree.Element.prototype](#apidoc.module.less.tree.Element.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Element.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>clone ()](#apidoc.element.less.tree.Element.prototype.clone)
1.  [function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>eval (context)](#apidoc.element.less.tree.Element.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Element.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Element.prototype.toCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>type

#### [module less.tree.Expression](#apidoc.module.less.tree.Expression)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Expression (value)](#apidoc.element.less.tree.Expression.Expression)

#### [module less.tree.Expression.prototype](#apidoc.module.less.tree.Expression.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Expression.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>eval (context)](#apidoc.element.less.tree.Expression.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Expression.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>throwAwayComments ()](#apidoc.element.less.tree.Expression.prototype.throwAwayComments)
1.  string <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>type

#### [module less.tree.Extend](#apidoc.module.less.tree.Extend)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend.Extend)
1.  number <span class="apidocSignatureSpan">less.tree.Extend.</span>next_id

#### [module less.tree.Extend.prototype](#apidoc.module.less.tree.Extend.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Extend.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>clone (context)](#apidoc.element.less.tree.Extend.prototype.clone)
1.  [function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>eval (context)](#apidoc.element.less.tree.Extend.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>findSelfSelectors (selectors)](#apidoc.element.less.tree.Extend.prototype.findSelfSelectors)
1.  string <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>type

#### [module less.tree.Import](#apidoc.module.less.tree.Import)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import.Import)

#### [module less.tree.Import.prototype](#apidoc.module.less.tree.Import.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Import.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>doEval (context)](#apidoc.element.less.tree.Import.prototype.doEval)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>eval (context)](#apidoc.element.less.tree.Import.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>evalForImport (context)](#apidoc.element.less.tree.Import.prototype.evalForImport)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>evalPath (context)](#apidoc.element.less.tree.Import.prototype.evalPath)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Import.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>getPath ()](#apidoc.element.less.tree.Import.prototype.getPath)
1.  [function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>isVariableImport ()](#apidoc.element.less.tree.Import.prototype.isVariableImport)
1.  string <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>type

#### [module less.tree.JavaScript](#apidoc.module.less.tree.JavaScript)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript.JavaScript)

#### [module less.tree.JavaScript.prototype](#apidoc.module.less.tree.JavaScript.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.JavaScript.prototype.</span>eval (context)](#apidoc.element.less.tree.JavaScript.prototype.eval)
1.  string <span class="apidocSignatureSpan">less.tree.JavaScript.prototype.</span>type

#### [module less.tree.Keyword](#apidoc.module.less.tree.Keyword)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Keyword (value)](#apidoc.element.less.tree.Keyword.Keyword)
1.  object <span class="apidocSignatureSpan">less.tree.Keyword.</span>False
1.  object <span class="apidocSignatureSpan">less.tree.Keyword.</span>True

#### [module less.tree.Keyword.prototype](#apidoc.module.less.tree.Keyword.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Keyword.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Keyword.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Keyword.prototype.</span>type

#### [module less.tree.Media](#apidoc.module.less.tree.Media)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media.Media)

#### [module less.tree.Media.prototype](#apidoc.module.less.tree.Media.prototype)
1.  boolean <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>allowRoot
1.  boolean <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>isRooted
1.  boolean <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>isRulesetLike
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Media.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>bubbleSelectors (selectors)](#apidoc.element.less.tree.Media.prototype.bubbleSelectors)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>eval (context)](#apidoc.element.less.tree.Media.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>evalNested (context)](#apidoc.element.less.tree.Media.prototype.evalNested)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>evalTop (context)](#apidoc.element.less.tree.Media.prototype.evalTop)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Media.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>permute (arr)](#apidoc.element.less.tree.Media.prototype.permute)
1.  string <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>type

#### [module less.tree.Negative](#apidoc.module.less.tree.Negative)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Negative (node)](#apidoc.element.less.tree.Negative.Negative)

#### [module less.tree.Negative.prototype](#apidoc.module.less.tree.Negative.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Negative.prototype.</span>eval (context)](#apidoc.element.less.tree.Negative.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Negative.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Negative.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Negative.prototype.</span>type

#### [module less.tree.Node](#apidoc.module.less.tree.Node)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Node ()](#apidoc.element.less.tree.Node.Node)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.</span>compare (a, b)](#apidoc.element.less.tree.Node.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.</span>numericCompare (a, b)](#apidoc.element.less.tree.Node.numericCompare)

#### [module less.tree.Node.prototype](#apidoc.module.less.tree.Node.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>_operate (context, op, a, b)](#apidoc.element.less.tree.Node.prototype._operate)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Node.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>addVisibilityBlock ()](#apidoc.element.less.tree.Node.prototype.addVisibilityBlock)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>blocksVisibility ()](#apidoc.element.less.tree.Node.prototype.blocksVisibility)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>copyVisibilityInfo (info)](#apidoc.element.less.tree.Node.prototype.copyVisibilityInfo)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>ensureInvisibility ()](#apidoc.element.less.tree.Node.prototype.ensureInvisibility)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>ensureVisibility ()](#apidoc.element.less.tree.Node.prototype.ensureVisibility)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>eval ()](#apidoc.element.less.tree.Node.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>fround (context, value)](#apidoc.element.less.tree.Node.prototype.fround)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Node.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>isVisible ()](#apidoc.element.less.tree.Node.prototype.isVisible)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>removeVisibilityBlock ()](#apidoc.element.less.tree.Node.prototype.removeVisibilityBlock)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Node.prototype.toCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>visibilityInfo ()](#apidoc.element.less.tree.Node.prototype.visibilityInfo)

#### [module less.tree.Operation](#apidoc.module.less.tree.Operation)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation.Operation)

#### [module less.tree.Operation.prototype](#apidoc.module.less.tree.Operation.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Operation.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>eval (context)](#apidoc.element.less.tree.Operation.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Operation.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>type

#### [module less.tree.Paren](#apidoc.module.less.tree.Paren)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Paren (node)](#apidoc.element.less.tree.Paren.Paren)

#### [module less.tree.Paren.prototype](#apidoc.module.less.tree.Paren.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Paren.prototype.</span>eval (context)](#apidoc.element.less.tree.Paren.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Paren.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Paren.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Paren.prototype.</span>type

#### [module less.tree.Quoted](#apidoc.module.less.tree.Quoted)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted.Quoted)

#### [module less.tree.Quoted.prototype](#apidoc.module.less.tree.Quoted.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>compare (other)](#apidoc.element.less.tree.Quoted.prototype.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>containsVariables ()](#apidoc.element.less.tree.Quoted.prototype.containsVariables)
1.  [function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>eval (context)](#apidoc.element.less.tree.Quoted.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Quoted.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>type

#### [module less.tree.Rule](#apidoc.module.less.tree.Rule)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule.Rule)

#### [module less.tree.Rule.prototype](#apidoc.module.less.tree.Rule.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>eval (context)](#apidoc.element.less.tree.Rule.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Rule.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>makeImportant ()](#apidoc.element.less.tree.Rule.prototype.makeImportant)
1.  string <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>type

#### [module less.tree.Ruleset](#apidoc.module.less.tree.Ruleset)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset.Ruleset)

#### [module less.tree.Ruleset.prototype](#apidoc.module.less.tree.Ruleset.prototype)
1.  boolean <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>isRuleset
1.  boolean <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>isRulesetLike
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Ruleset.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>eval (context)](#apidoc.element.less.tree.Ruleset.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>evalImports (context)](#apidoc.element.less.tree.Ruleset.prototype.evalImports)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>find (selector, self, filter)](#apidoc.element.less.tree.Ruleset.prototype.find)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Ruleset.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>joinSelector (paths, context, selector)](#apidoc.element.less.tree.Ruleset.prototype.joinSelector)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>joinSelectors (paths, context, selectors)](#apidoc.element.less.tree.Ruleset.prototype.joinSelectors)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>makeImportant ()](#apidoc.element.less.tree.Ruleset.prototype.makeImportant)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>matchArgs (args)](#apidoc.element.less.tree.Ruleset.prototype.matchArgs)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>matchCondition (args, context)](#apidoc.element.less.tree.Ruleset.prototype.matchCondition)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>prependRule (rule)](#apidoc.element.less.tree.Ruleset.prototype.prependRule)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>resetCache ()](#apidoc.element.less.tree.Ruleset.prototype.resetCache)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>rulesets ()](#apidoc.element.less.tree.Ruleset.prototype.rulesets)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>variable (name)](#apidoc.element.less.tree.Ruleset.prototype.variable)
1.  [function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>variables ()](#apidoc.element.less.tree.Ruleset.prototype.variables)
1.  string <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>type

#### [module less.tree.RulesetCall](#apidoc.module.less.tree.RulesetCall)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall.RulesetCall)

#### [module less.tree.RulesetCall.prototype](#apidoc.module.less.tree.RulesetCall.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.RulesetCall.prototype.</span>eval (context)](#apidoc.element.less.tree.RulesetCall.prototype.eval)
1.  string <span class="apidocSignatureSpan">less.tree.RulesetCall.prototype.</span>type

#### [module less.tree.Selector](#apidoc.module.less.tree.Selector)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector.Selector)

#### [module less.tree.Selector.prototype](#apidoc.module.less.tree.Selector.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>CacheElements ()](#apidoc.element.less.tree.Selector.prototype.CacheElements)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Selector.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>createDerived (elements, extendList, evaldCondition)](#apidoc.element.less.tree.Selector.prototype.createDerived)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>createEmptySelectors ()](#apidoc.element.less.tree.Selector.prototype.createEmptySelectors)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>eval (context)](#apidoc.element.less.tree.Selector.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Selector.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>getIsOutput ()](#apidoc.element.less.tree.Selector.prototype.getIsOutput)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>isJustParentSelector ()](#apidoc.element.less.tree.Selector.prototype.isJustParentSelector)
1.  [function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>match (other)](#apidoc.element.less.tree.Selector.prototype.match)
1.  string <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>type

#### [module less.tree.URL](#apidoc.module.less.tree.URL)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL.URL)

#### [module less.tree.URL.prototype](#apidoc.module.less.tree.URL.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>accept (visitor)](#apidoc.element.less.tree.URL.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>eval (context)](#apidoc.element.less.tree.URL.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.URL.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>type

#### [module less.tree.Unit](#apidoc.module.less.tree.Unit)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit.Unit)

#### [module less.tree.Unit.prototype](#apidoc.module.less.tree.Unit.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>cancel ()](#apidoc.element.less.tree.Unit.prototype.cancel)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>clone ()](#apidoc.element.less.tree.Unit.prototype.clone)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>compare (other)](#apidoc.element.less.tree.Unit.prototype.compare)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Unit.prototype.genCSS)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>is (unitString)](#apidoc.element.less.tree.Unit.prototype.is)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isEmpty ()](#apidoc.element.less.tree.Unit.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isLength ()](#apidoc.element.less.tree.Unit.prototype.isLength)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isSingular ()](#apidoc.element.less.tree.Unit.prototype.isSingular)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>map (callback)](#apidoc.element.less.tree.Unit.prototype.map)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>toString ()](#apidoc.element.less.tree.Unit.prototype.toString)
1.  [function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>usedUnits ()](#apidoc.element.less.tree.Unit.prototype.usedUnits)
1.  string <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>type

#### [module less.tree.Value](#apidoc.module.less.tree.Value)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Value (value)](#apidoc.element.less.tree.Value.Value)

#### [module less.tree.Value.prototype](#apidoc.module.less.tree.Value.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Value.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>eval (context)](#apidoc.element.less.tree.Value.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Value.prototype.genCSS)
1.  string <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>type

#### [module less.tree.Variable](#apidoc.module.less.tree.Variable)
1.  [function <span class="apidocSignatureSpan">less.tree.</span>Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable.Variable)

#### [module less.tree.Variable.prototype](#apidoc.module.less.tree.Variable.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.Variable.prototype.</span>eval (context)](#apidoc.element.less.tree.Variable.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.Variable.prototype.</span>find (obj, fun)](#apidoc.element.less.tree.Variable.prototype.find)
1.  string <span class="apidocSignatureSpan">less.tree.Variable.prototype.</span>type

#### [module less.tree.mixin](#apidoc.module.less.tree.mixin)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.</span>Call (elements, args, index, currentFileInfo, important)](#apidoc.element.less.tree.mixin.Call)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.</span>Definition (name, params, rules, condition, variadic, frames, visibilityInfo)](#apidoc.element.less.tree.mixin.Definition)

#### [module less.tree.mixin.Call.prototype](#apidoc.module.less.tree.mixin.Call.prototype)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>_setVisibilityToReplacement (replacement)](#apidoc.element.less.tree.mixin.Call.prototype._setVisibilityToReplacement)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>accept (visitor)](#apidoc.element.less.tree.mixin.Call.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>eval (context)](#apidoc.element.less.tree.mixin.Call.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>format (args)](#apidoc.element.less.tree.mixin.Call.prototype.format)
1.  string <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>type

#### [module less.tree.mixin.Definition.prototype](#apidoc.module.less.tree.mixin.Definition.prototype)
1.  boolean <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>allowRoot
1.  boolean <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>evalFirst
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>accept (visitor)](#apidoc.element.less.tree.mixin.Definition.prototype.accept)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>eval (context)](#apidoc.element.less.tree.mixin.Definition.prototype.eval)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>evalCall (context, args, important)](#apidoc.element.less.tree.mixin.Definition.prototype.evalCall)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>evalParams (context, mixinEnv, args, evaldArguments)](#apidoc.element.less.tree.mixin.Definition.prototype.evalParams)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>makeImportant ()](#apidoc.element.less.tree.mixin.Definition.prototype.makeImportant)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>matchArgs (args, context)](#apidoc.element.less.tree.mixin.Definition.prototype.matchArgs)
1.  [function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>matchCondition (args, context)](#apidoc.element.less.tree.mixin.Definition.prototype.matchCondition)
1.  object <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>_lookups
1.  string <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>type

#### [module less.utils](#apidoc.module.less.utils)
1.  [function <span class="apidocSignatureSpan">less.utils.</span>getLocation (index, inputStream)](#apidoc.element.less.utils.getLocation)

#### [module less.visitors](#apidoc.module.less.visitors)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>Visitor (implementation)](#apidoc.element.less.visitors.Visitor)

#### [module less.visitors.ExtendVisitor](#apidoc.module.less.visitors.ExtendVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor.ExtendVisitor)

#### [module less.visitors.ExtendVisitor.prototype](#apidoc.module.less.visitors.ExtendVisitor.prototype)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>checkExtendsForNonMatched (extendList)](#apidoc.element.less.visitors.ExtendVisitor.prototype.checkExtendsForNonMatched)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>doExtendChaining (extendsList, extendsListTarget, iterationCount)](#apidoc.element.less.visitors.ExtendVisitor.prototype.doExtendChaining)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>extendSelector (matches, selectorPath, replacementSelector, isVisible)](#apidoc.element.less.visitors.ExtendVisitor.prototype.extendSelector)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>findMatch (extend, haystackSelectorPath)](#apidoc.element.less.visitors.ExtendVisitor.prototype.findMatch)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>isElementValuesEqual (elementValue1, elementValue2)](#apidoc.element.less.visitors.ExtendVisitor.prototype.isElementValuesEqual)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ExtendVisitor.prototype.run)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirective)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitDirectiveOut (directiveNode)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirectiveOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMedia)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMediaOut (mediaNode)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMediaOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMixinDefinition)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitRule)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitRuleset)
1.  [function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitSelector (selectorNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitSelector)

#### [module less.visitors.ImportVisitor](#apidoc.module.less.visitors.ImportVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor.ImportVisitor)

#### [module less.visitors.ImportVisitor.prototype](#apidoc.module.less.visitors.ImportVisitor.prototype)
1.  boolean <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>isReplacing
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>_onSequencerEmpty ()](#apidoc.element.less.visitors.ImportVisitor.prototype._onSequencerEmpty)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>onImported (importNode, context, e, root, importedAtRoot, fullPath)](#apidoc.element.less.visitors.ImportVisitor.prototype.onImported)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>processImportNode (importNode, context, importParent)](#apidoc.element.less.visitors.ImportVisitor.prototype.processImportNode)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ImportVisitor.prototype.run)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitDirective)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitDirectiveOut (directiveNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitDirectiveOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitImport (importNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitImport)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMedia)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMediaOut (mediaNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMediaOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinition)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMixinDefinitionOut (mixinDefinitionNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinitionOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRule)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRuleOut (ruleNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleOut)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleset)
1.  [function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRulesetOut (rulesetNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRulesetOut)

#### [module less.visitors.JoinSelectorVisitor](#apidoc.module.less.visitors.JoinSelectorVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor.JoinSelectorVisitor)

#### [module less.visitors.JoinSelectorVisitor.prototype](#apidoc.module.less.visitors.JoinSelectorVisitor.prototype)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.run)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitDirective)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMedia)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMixinDefinition)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRule)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRuleset)
1.  [function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRulesetOut (rulesetNode)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRulesetOut)

#### [module less.visitors.MarkVisibleSelectorsVisitor](#apidoc.module.less.visitors.MarkVisibleSelectorsVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.MarkVisibleSelectorsVisitor)

#### [module less.visitors.MarkVisibleSelectorsVisitor.prototype](#apidoc.module.less.visitors.MarkVisibleSelectorsVisitor.prototype)
1.  [function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.run)
1.  [function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>visit (node)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visit)
1.  [function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>visitArray (nodes)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visitArray)

#### [module less.visitors.ToCSSVisitor](#apidoc.module.less.visitors.ToCSSVisitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor.ToCSSVisitor)

#### [module less.visitors.ToCSSVisitor.prototype](#apidoc.module.less.visitors.ToCSSVisitor.prototype)
1.  boolean <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>isReplacing
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_compileRulesetPaths (rulesetNode)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._compileRulesetPaths)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_mergeRules (rules)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._mergeRules)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_removeDuplicateRules (rules)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._removeDuplicateRules)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>checkValidNodes (rules, isRoot)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.checkValidNodes)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.run)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitAnonymous (anonymousNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitAnonymous)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitComment (commentNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitComment)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirective)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirectiveWithBody (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithBody)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirectiveWithoutBody (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithoutBody)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitExtend (extendNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitExtend)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitImport (importNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitImport)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMedia)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitMixinDefinition (mixinNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMixinDefinition)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRule)
1.  [function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRuleset)

#### [module less.visitors.Visitor](#apidoc.module.less.visitors.Visitor)
1.  [function <span class="apidocSignatureSpan">less.visitors.</span>Visitor (implementation)](#apidoc.element.less.visitors.Visitor.Visitor)

#### [module less.visitors.Visitor.prototype](#apidoc.module.less.visitors.Visitor.prototype)
1.  [function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>flatten (arr, out)](#apidoc.element.less.visitors.Visitor.prototype.flatten)
1.  [function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>visit (node)](#apidoc.element.less.visitors.Visitor.prototype.visit)
1.  [function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>visitArray (nodes, nonReplacing)](#apidoc.element.less.visitors.Visitor.prototype.visitArray)



# <a name="apidoc.module.less"></a>[module less](#apidoc.module.less)

#### <a name="apidoc.element.less.AbstractFileManager"></a>[function <span class="apidocSignatureSpan">less.</span>AbstractFileManager ()](#apidoc.element.less.AbstractFileManager)
- description and source-code
```javascript
AbstractFileManager = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.Environment"></a>[function <span class="apidocSignatureSpan">less.</span>Environment (externalEnvironment, fileManagers)](#apidoc.element.less.Environment)
- description and source-code
```javascript
Environment = function (externalEnvironment, fileManagers) {
    this.fileManagers = fileManagers || [];
    externalEnvironment = externalEnvironment || {};

    var optionalFunctions = ["encodeBase64", "mimeLookup", "charsetLookup", "getSourceMapGenerator"],
        requiredFunctions = [],
        functions = requiredFunctions.concat(optionalFunctions);

    for (var i = 0; i < functions.length; i++) {
        var propName = functions[i],
            environmentFunc = externalEnvironment[propName];
        if (environmentFunc) {
            this[propName] = environmentFunc.bind(externalEnvironment);
        } else if (i < requiredFunctions.length) {
            this.warn("missing required function in environment - " + propName);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.FileManager"></a>[function <span class="apidocSignatureSpan">less.</span>FileManager ()](#apidoc.element.less.FileManager)
- description and source-code
```javascript
FileManager = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.ImportManager"></a>[function <span class="apidocSignatureSpan">less.</span>ImportManager (context, rootFileInfo)](#apidoc.element.less.ImportManager)
- description and source-code
```javascript
ImportManager = function (context, rootFileInfo) {
    this.rootFilename = rootFileInfo.filename;
    this.paths = context.paths || [];  // Search paths, when importing
    this.contents = {};             // map - filename to contents of all the files
    this.contentsIgnoredChars = {}; // map - filename to lines at the beginning of each file to ignore
    this.mime = context.mime;
    this.error = null;
    this.context = context;
    // Deprecated? Unused outside of here, could be useful.
    this.queue = [];        // Files which haven't been imported yet
    this.files = {};        // Holds the imported parse trees.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.LessError"></a>[function <span class="apidocSignatureSpan">less.</span>LessError (e, importManager, currentFilename)](#apidoc.element.less.LessError)
- description and source-code
```javascript
function LessError(e, importManager, currentFilename) {

    Error.call(this);

    var filename = e.filename || currentFilename;

    if (importManager && filename) {
        var input = importManager.contents[filename],
            loc = utils.getLocation(e.index, input),
            line = loc.line,
            col  = loc.column,
            callLine = e.call && utils.getLocation(e.call, input).line,
            lines = input.split('\n');

        this.type = e.type || 'Syntax';
        this.filename = filename;
        this.index = e.index;
        this.line = typeof line === 'number' ? line + 1 : null;
        this.callLine = callLine + 1;
        this.callExtract = lines[callLine];
        this.column = col;
        this.extract = [
            lines[line - 1],
            lines[line],
            lines[line + 1]
        ];
    }
    this.message = e.message;
    this.stack = e.stack;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.ParseTree"></a>[function <span class="apidocSignatureSpan">less.</span>ParseTree (root, imports)](#apidoc.element.less.ParseTree)
- description and source-code
```javascript
ParseTree = function (root, imports) {
    this.root = root;
    this.imports = imports;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.Parser"></a>[function <span class="apidocSignatureSpan">less.</span>Parser (context, imports, fileInfo)](#apidoc.element.less.Parser)
- description and source-code
```javascript
function Parser(context, imports, fileInfo) {
    var parsers,
        parserInput = getParserInput();

    function error(msg, type) {
        throw new LessError(
            {
                index: parserInput.i,
                filename: fileInfo.filename,
                type: type || 'Syntax',
                message: msg
            },
            imports
        );
    }

    function expect(arg, msg, index) {
        // some older browsers return typeof 'function' for RegExp
        var result = (arg instanceof Function) ? arg.call(parsers) : parserInput.$re(arg);
        if (result) {
            return result;
        }
        error(msg || (typeof arg === 'string' ? "expected '" + arg + "' got '" + parserInput.currentChar() + "'"
                                               : "unexpected token"));
    }

    // Specialization of expect()
    function expectChar(arg, msg) {
        if (parserInput.$char(arg)) {
            return arg;
        }
        error(msg || "expected '" + arg + "' got '" + parserInput.currentChar() + "'");
    }

    function getDebugInfo(index) {
        var filename = fileInfo.filename;

        return {
            lineNumber: utils.getLocation(index, parserInput.getInput()).line + 1,
            fileName: filename
        };
    }

    //
    // The Parser
    //
    return {

        //
        // Parse an input string into an abstract syntax tree,
        // @param str A string containing 'less' markup
        // @param callback call 'callback' when done.
        // @param [additionalData] An optional map which can contains vars - a map (key, value) of variables to apply
        //
        parse: function (str, callback, additionalData) {
            var root, error = null, globalVars, modifyVars, ignored, preText = "";

            globalVars = (additionalData && additionalData.globalVars) ? Parser.serializeVars(additionalData.globalVars) + '\n' : '';
            modifyVars = (additionalData && additionalData.modifyVars) ? '\n' + Parser.serializeVars(additionalData.modifyVars) : '';

            if (context.pluginManager) {
                var preProcessors = context.pluginManager.getPreProcessors();
                for (var i = 0; i < preProcessors.length; i++) {
                    str = preProcessors[i].process(str, { context: context, imports: imports, fileInfo: fileInfo });
                }
            }

            if (globalVars || (additionalData && additionalData.banner)) {
                preText = ((additionalData && additionalData.banner) ? additionalData.banner : "") + globalVars;
                ignored = imports.contentsIgnoredChars;
                ignored[fileInfo.filename] = ignored[fileInfo.filename] || 0;
                ignored[fileInfo.filename] += preText.length;
            }

            str = str.replace(/\r\n?/g, '\n');
            // Remove potential UTF Byte Order Mark
            str = preText + str.replace(/^\uFEFF/, '') + modifyVars;
            imports.contents[fileInfo.filename] = str;

            // Start with the primary rule.
            // The whole syntax tree is held under a Ruleset node,
            // with the 'root' property set to true, so no '{}' are
            // output. The callback is called when the input is parsed.
            try {
                parserInput.start(str, context.chunkInput, function fail(msg, index) {
                    throw new LessError({
                        index: index,
                        type: 'Parse',
                        message: msg,
                        filename: fileInfo.filename
                    }, imports);
                });

                root = new(tree.Ruleset)(null, this.parsers.primary());
                root.root = true;
                root.firstRoot = true;
            } catch (e) {
                return callback(new LessError(e, imports, fileInfo.filename));
            }

            // If 'i' is smaller than the 'input.length - 1',
            // it means the parser wasn't able to parse the whole
            // string, so we've got a parsing error. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginLoader"></a>[function <span class="apidocSignatureSpan">less.</span>PluginLoader (less)](#apidoc.element.less.PluginLoader)
- description and source-code
```javascript
PluginLoader = function (less) {
    this.less = less;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager"></a>[function <span class="apidocSignatureSpan">less.</span>PluginManager (less)](#apidoc.element.less.PluginManager)
- description and source-code
```javascript
PluginManager = function (less) {
    this.less = less;
    this.visitors = [];
    this.preProcessors = [];
    this.postProcessors = [];
    this.installedPlugins = [];
    this.fileManagers = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder"></a>[function <span class="apidocSignatureSpan">less.</span>SourceMapBuilder (options)](#apidoc.element.less.SourceMapBuilder)
- description and source-code
```javascript
SourceMapBuilder = function (options) {
    this.options = options;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapOutput"></a>[function <span class="apidocSignatureSpan">less.</span>SourceMapOutput (options)](#apidoc.element.less.SourceMapOutput)
- description and source-code
```javascript
SourceMapOutput = function (options) {
    this._css = [];
    this._rootNode = options.rootNode;
    this._contentsMap = options.contentsMap;
    this._contentsIgnoredCharsMap = options.contentsIgnoredCharsMap;
    if (options.sourceMapFilename) {
        this._sourceMapFilename = options.sourceMapFilename.replace(/\\/g, '/');
    }
    this._outputFilename = options.outputFilename;
    this.sourceMapURL = options.sourceMapURL;
    if (options.sourceMapBasepath) {
        this._sourceMapBasepath = options.sourceMapBasepath.replace(/\\/g, '/');
    }
    if (options.sourceMapRootpath) {
        this._sourceMapRootpath = options.sourceMapRootpath.replace(/\\/g, '/');
        if (this._sourceMapRootpath.charAt(this._sourceMapRootpath.length - 1) !== '/') {
            this._sourceMapRootpath += '/';
        }
    } else {
        this._sourceMapRootpath = "";
    }
    this._outputSourceFiles = options.outputSourceFiles;
    this._sourceMapGeneratorConstructor = environment.getSourceMapGenerator();

    this._lineNumber = 0;
    this._column = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.UrlFileManager"></a>[function <span class="apidocSignatureSpan">less.</span>UrlFileManager ()](#apidoc.element.less.UrlFileManager)
- description and source-code
```javascript
UrlFileManager = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Eval"></a>[function <span class="apidocSignatureSpan">less.</span>contexts.Eval (options, frames)](#apidoc.element.less.contexts.Eval)
- description and source-code
```javascript
contexts.Eval = function (options, frames) {
    copyFromOriginal(options, this, evalCopyProperties);

    if (typeof this.paths === "string") { this.paths = [this.paths]; }

    this.frames = frames || [];
    this.importantScope = this.importantScope || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.createFromEnvironment"></a>[function <span class="apidocSignatureSpan">less.</span>createFromEnvironment (environment, fileManagers)](#apidoc.element.less.createFromEnvironment)
- description and source-code
```javascript
createFromEnvironment = function (environment, fileManagers) {
    var SourceMapOutput, SourceMapBuilder, ParseTree, ImportManager, Environment;

    var less = {
        version: [2, 7, 2],
        data: require('./data'),
        tree: require('./tree'),
        Environment: (Environment = require("./environment/environment")),
        AbstractFileManager: require("./environment/abstract-file-manager"),
        environment: (environment = new Environment(environment, fileManagers)),
        visitors: require('./visitors'),
        Parser: require('./parser/parser'),
        functions: require('./functions')(environment),
        contexts: require("./contexts"),
        SourceMapOutput: (SourceMapOutput = require('./source-map-output')(environment)),
        SourceMapBuilder: (SourceMapBuilder = require('./source-map-builder')(SourceMapOutput, environment)),
        ParseTree: (ParseTree = require('./parse-tree')(SourceMapBuilder)),
        ImportManager: (ImportManager = require('./import-manager')(environment)),
        render: require("./render")(environment, ParseTree, ImportManager),
        parse: require("./parse")(environment, ParseTree, ImportManager),
        LessError: require('./less-error'),
        transformTree: require('./transform-tree'),
        utils: require('./utils'),
        PluginManager: require('./plugin-manager'),
        logger: require('./logger')
    };

    return less;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.formatError"></a>[function <span class="apidocSignatureSpan">less.</span>formatError (ctx, options)](#apidoc.element.less.formatError)
- description and source-code
```javascript
formatError = function (ctx, options) {
    options = options || {};

    var message = "";
    var extract = ctx.extract;
    var error = [];
    var stylize = options.color ? lesscHelper.stylize : function (str) { return str; };

    // only output a stack if it isn't a less error
    if (ctx.stack && !ctx.type) { return stylize(ctx.stack, 'red'); }

    if (!ctx.hasOwnProperty('index') || !extract) {
        return ctx.stack || ctx.message;
    }

    if (typeof extract[0] === 'string') {
        error.push(stylize((ctx.line - 1) + ' ' + extract[0], 'grey'));
    }

    if (typeof extract[1] === 'string') {
        var errorTxt = ctx.line + ' ';
        if (extract[1]) {
            errorTxt += extract[1].slice(0, ctx.column) +
                            stylize(stylize(stylize(extract[1].substr(ctx.column, 1), 'bold') +
                            extract[1].slice(ctx.column + 1), 'red'), 'inverse');
        }
        error.push(errorTxt);
    }

    if (typeof extract[2] === 'string') {
        error.push(stylize((ctx.line + 1) + ' ' + extract[2], 'grey'));
    }
    error = error.join('\n') + stylize('', 'reset') + '\n';

    message += stylize(ctx.type + 'Error: ' + ctx.message, 'red');
    if (ctx.filename) {
        message += stylize(' in ', 'red') + ctx.filename +
            stylize(' on line ' + ctx.line + ', column ' + (ctx.column + 1) + ':', 'grey');
    }

    message += '\n' + error;

    if (ctx.callLine) {
        message += stylize('from ', 'red') + (ctx.filename || '') + '/n';
        message += stylize(ctx.callLine, 'grey') + ' ' + ctx.callExtract + '/n';
    }

    return message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.ReadStream"></a>[function <span class="apidocSignatureSpan">less.</span>fs.ReadStream (path, options)](#apidoc.element.less.fs.ReadStream)
- description and source-code
```javascript
function ReadStream(path, options) {
  if (this instanceof ReadStream)
    return fs$ReadStream.apply(this, arguments), this
  else
    return ReadStream.apply(Object.create(ReadStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats"></a>[function <span class="apidocSignatureSpan">less.</span>fs.Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats)
- description and source-code
```javascript
function Stats( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec) {
  this.dev = dev;
  this.mode = mode;
  this.nlink = nlink;
  this.uid = uid;
  this.gid = gid;
  this.rdev = rdev;
  this.blksize = blksize;
  this.ino = ino;
  this.size = size;
  this.blocks = blocks;
  this.atime = new Date(atim_msec);
  this.mtime = new Date(mtim_msec);
  this.ctime = new Date(ctim_msec);
  this.birthtime = new Date(birthtim_msec);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.WriteStream"></a>[function <span class="apidocSignatureSpan">less.</span>fs.WriteStream (path, options)](#apidoc.element.less.fs.WriteStream)
- description and source-code
```javascript
function WriteStream(path, options) {
  if (this instanceof WriteStream)
    return fs$WriteStream.apply(this, arguments), this
  else
    return WriteStream.apply(Object.create(WriteStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.functions.functionCaller"></a>[function <span class="apidocSignatureSpan">less.</span>functions.functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller)
- description and source-code
```javascript
functions.functionCaller = function (name, context, index, currentFileInfo) {
    this.name = name.toLowerCase();
    this.index = index;
    this.context = context;
    this.currentFileInfo = currentFileInfo;

    this.func = context.frames[0].functionRegistry.get(this.name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.parse"></a>[function <span class="apidocSignatureSpan">less.</span>parse (input, options, callback)](#apidoc.element.less.parse)
- description and source-code
```javascript
parse = function (input, options, callback) {
    options = options || {};

    if (typeof options === 'function') {
        callback = options;
        options = {};
    }

    if (!callback) {
        if (!PromiseConstructor) {
            PromiseConstructor = typeof Promise === 'undefined' ? require('promise') : Promise;
        }
        var self = this;
        return new PromiseConstructor(function (resolve, reject) {
            parse.call(self, input, options, function(err, output) {
                if (err) {
                    reject(err);
                } else {
                    resolve(output);
                }
            });
        });
    } else {
        var context,
            rootFileInfo,
            pluginManager = new PluginManager(this);

        pluginManager.addPlugins(options.plugins);
        options.pluginManager = pluginManager;

        context = new contexts.Parse(options);

        if (options.rootFileInfo) {
            rootFileInfo = options.rootFileInfo;
        } else {
            var filename = options.filename || "input";
            var entryPath = filename.replace(/[^\/\\]*$/, "");
            rootFileInfo = {
                filename: filename,
                relativeUrls: context.relativeUrls,
                rootpath: context.rootpath || "",
                currentDirectory: entryPath,
                entryPath: entryPath,
                rootFilename: filename
            };
            // add in a missing trailing slash
            if (rootFileInfo.rootpath && rootFileInfo.rootpath.slice(-1) !== "/") {
                rootFileInfo.rootpath += "/";
            }
        }

        var imports = new ImportManager(context, rootFileInfo);

        new Parser(context, imports, rootFileInfo)
            .parse(input, function (e, root) {
            if (e) { return callback(e); }
            callback(null, root, imports, options);
        }, options);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.render"></a>[function <span class="apidocSignatureSpan">less.</span>render (input, options, callback)](#apidoc.element.less.render)
- description and source-code
```javascript
render = function (input, options, callback) {
    if (typeof options === 'function') {
        callback = options;
        options = {};
    }

    if (!callback) {
        if (!PromiseConstructor) {
            PromiseConstructor = typeof Promise === 'undefined' ? require('promise') : Promise;
        }
        var self = this;
        return new PromiseConstructor(function (resolve, reject) {
            render.call(self, input, options, function(err, output) {
                if (err) {
                    reject(err);
                } else {
                    resolve(output);
                }
            });
        });
    } else {
        this.parse(input, options, function(err, root, imports, options) {
            if (err) { return callback(err); }

            var result;
            try {
                var parseTree = new ParseTree(root, imports);
                result = parseTree.toCSS(options);
            }
            catch (err) { return callback(err); }

            callback(null, result);
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.transformTree"></a>[function <span class="apidocSignatureSpan">less.</span>transformTree (root, options)](#apidoc.element.less.transformTree)
- description and source-code
```javascript
transformTree = function (root, options) {
    options = options || {};
    var evaldRoot,
        variables = options.variables,
        evalEnv = new contexts.Eval(options);

    //
    // Allows setting variables with a hash, so:
    //
    //   '{ color: new tree.Color('#f01') }' will become:
    //
    //   new tree.Rule('@color',
    //     new tree.Value([
    //       new tree.Expression([
    //         new tree.Color('#f01')
    //       ])
    //     ])
    //   )
    //
    if (typeof variables === 'object' && !Array.isArray(variables)) {
        variables = Object.keys(variables).map(function (k) {
            var value = variables[k];

            if (! (value instanceof tree.Value)) {
                if (! (value instanceof tree.Expression)) {
                    value = new tree.Expression([value]);
                }
                value = new tree.Value([value]);
            }
            return new tree.Rule('@' + k, value, false, null, 0);
        });
        evalEnv.frames = [new tree.Ruleset(null, variables)];
    }

    var preEvalVisitors = [],
        visitors = [
            new visitor.JoinSelectorVisitor(),
            new visitor.MarkVisibleSelectorsVisitor(true),
            new visitor.ExtendVisitor(),
            new visitor.ToCSSVisitor({compress: Boolean(options.compress)})
        ], i;

    if (options.pluginManager) {
        var pluginVisitors = options.pluginManager.getVisitors();
        for (i = 0; i < pluginVisitors.length; i++) {
            var pluginVisitor = pluginVisitors[i];
            if (pluginVisitor.isPreEvalVisitor) {
                preEvalVisitors.push(pluginVisitor);
            } else {
                if (pluginVisitor.isPreVisitor) {
                    visitors.splice(0, 0, pluginVisitor);
                } else {
                    visitors.push(pluginVisitor);
                }
            }
        }
    }

    for (i = 0; i < preEvalVisitors.length; i++) {
        preEvalVisitors[i].run(root);
    }

    evaldRoot = root.eval(evalEnv);

    for (i = 0; i < visitors.length; i++) {
        visitors[i].run(evaldRoot);
    }

    return evaldRoot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Alpha"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Alpha (val)](#apidoc.element.less.tree.Alpha)
- description and source-code
```javascript
tree.Alpha = function (val) {
    this.value = val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Anonymous"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous)
- description and source-code
```javascript
tree.Anonymous = function (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo) {
    this.value = value;
    this.index = index;
    this.mapLines = mapLines;
    this.currentFileInfo = currentFileInfo;
    this.rulesetLike = (typeof rulesetLike === 'undefined') ? false : rulesetLike;
    this.allowRoot = true;
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Assignment"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Assignment (key, val)](#apidoc.element.less.tree.Assignment)
- description and source-code
```javascript
tree.Assignment = function (key, val) {
    this.key = key;
    this.value = val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Attribute"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Attribute (key, op, value)](#apidoc.element.less.tree.Attribute)
- description and source-code
```javascript
tree.Attribute = function (key, op, value) {
    this.key = key;
    this.op = op;
    this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Call"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call)
- description and source-code
```javascript
tree.Call = function (name, args, index, currentFileInfo) {
    this.name = name;
    this.args = args;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color)
- description and source-code
```javascript
tree.Color = function (rgb, a, originalForm) {
    //
    // The end goal here, is to parse the arguments
    // into an integer triplet, such as '128, 255, 0'
    //
    // This facilitates operations and conversions.
    //
    if (Array.isArray(rgb)) {
        this.rgb = rgb;
    } else if (rgb.length == 6) {
        this.rgb = rgb.match(/.{2}/g).map(function (c) {
            return parseInt(c, 16);
        });
    } else {
        this.rgb = rgb.split('').map(function (c) {
            return parseInt(c + c, 16);
        });
    }
    this.alpha = typeof a === 'number' ? a : 1;
    if (typeof originalForm !== 'undefined') {
        this.value = originalForm;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Combinator"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Combinator (value)](#apidoc.element.less.tree.Combinator)
- description and source-code
```javascript
tree.Combinator = function (value) {
    if (value === ' ') {
        this.value = ' ';
        this.emptyOrWhitespace = true;
    } else {
        this.value = value ? value.trim() : "";
        this.emptyOrWhitespace = this.value === "";
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Comment"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment)
- description and source-code
```javascript
tree.Comment = function (value, isLineComment, index, currentFileInfo) {
    this.value = value;
    this.isLineComment = isLineComment;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Condition"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition)
- description and source-code
```javascript
tree.Condition = function (op, l, r, i, negate) {
    this.op = op.trim();
    this.lvalue = l;
    this.rvalue = r;
    this.index = i;
    this.negate = negate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.DetachedRuleset"></a>[function <span class="apidocSignatureSpan">less.</span>tree.DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset)
- description and source-code
```javascript
tree.DetachedRuleset = function (ruleset, frames) {
    this.ruleset = ruleset;
    this.frames = frames;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Dimension (value, unit)](#apidoc.element.less.tree.Dimension)
- description and source-code
```javascript
tree.Dimension = function (value, unit) {
    this.value = parseFloat(value);
    this.unit = (unit && unit instanceof Unit) ? unit :
      new Unit(unit ? [unit] : undefined);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive)
- description and source-code
```javascript
tree.Directive = function (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo) {
    var i;

    this.name  = name;
    this.value = value;
    if (rules) {
        if (Array.isArray(rules)) {
            this.rules = rules;
        } else {
            this.rules = [rules];
            this.rules[0].selectors = (new Selector([], null, null, this.index, currentFileInfo)).createEmptySelectors();
        }
        for (i = 0; i < this.rules.length; i++) {
            this.rules[i].allowImports = true;
        }
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.debugInfo = debugInfo;
    this.isRooted = isRooted || false;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element)
- description and source-code
```javascript
tree.Element = function (combinator, value, index, currentFileInfo, info) {
    this.combinator = combinator instanceof Combinator ?
                      combinator : new Combinator(combinator);

    if (typeof value === 'string') {
        this.value = value.trim();
    } else if (value) {
        this.value = value;
    } else {
        this.value = "";
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.copyVisibilityInfo(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Expression"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Expression (value)](#apidoc.element.less.tree.Expression)
- description and source-code
```javascript
tree.Expression = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Expression requires an array parameter");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Extend"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend)
- description and source-code
```javascript
function Extend(selector, option, index, currentFileInfo, visibilityInfo) {
    this.selector = selector;
    this.option = option;
    this.index = index;
    this.object_id = Extend.next_id++;
    this.parent_ids = [this.object_id];
    this.currentFileInfo = currentFileInfo || {};
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;

    switch(option) {
        case "all":
            this.allowBefore = true;
            this.allowAfter = true;
            break;
        default:
            this.allowBefore = false;
            this.allowAfter = false;
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import)
- description and source-code
```javascript
tree.Import = function (path, features, options, index, currentFileInfo, visibilityInfo) {
    this.options = options;
    this.index = index;
    this.path = path;
    this.features = features;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;

    if (this.options.less !== undefined || this.options.inline) {
        this.css = !this.options.less || this.options.inline;
    } else {
        var pathValue = this.getPath();
        if (pathValue && /[#\.\&\?\/]css([\?;].*)?$/.test(pathValue)) {
            this.css = true;
        }
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.JavaScript"></a>[function <span class="apidocSignatureSpan">less.</span>tree.JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript)
- description and source-code
```javascript
tree.JavaScript = function (string, escaped, index, currentFileInfo) {
    this.escaped = escaped;
    this.expression = string;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Keyword"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Keyword (value)](#apidoc.element.less.tree.Keyword)
- description and source-code
```javascript
tree.Keyword = function (value) { this.value = value; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media)
- description and source-code
```javascript
tree.Media = function (value, features, index, currentFileInfo, visibilityInfo) {
    this.index = index;
    this.currentFileInfo = currentFileInfo;

    var selectors = (new Selector([], null, null, this.index, this.currentFileInfo)).createEmptySelectors();

    this.features = new Value(features);
    this.rules = [new Ruleset(selectors, value)];
    this.rules[0].allowImports = true;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Negative"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Negative (node)](#apidoc.element.less.tree.Negative)
- description and source-code
```javascript
tree.Negative = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Node ()](#apidoc.element.less.tree.Node)
- description and source-code
```javascript
tree.Node = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Operation"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation)
- description and source-code
```javascript
tree.Operation = function (op, operands, isSpaced) {
    this.op = op.trim();
    this.operands = operands;
    this.isSpaced = isSpaced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Paren"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Paren (node)](#apidoc.element.less.tree.Paren)
- description and source-code
```javascript
tree.Paren = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Quoted"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted)
- description and source-code
```javascript
tree.Quoted = function (str, content, escaped, index, currentFileInfo) {
    this.escaped = (escaped == null) ? true : escaped;
    this.value = content || '';
    this.quote = str.charAt(0);
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Rule"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule)
- description and source-code
```javascript
tree.Rule = function (name, value, important, merge, index, currentFileInfo, inline, variable) {
    this.name = name;
    this.value = (value instanceof Node) ? value : new Value([value]); //value instanceof tree.Value || value instanceof tree.Ruleset
 ??
    this.important = important ? ' ' + important.trim() : '';
    this.merge = merge;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.inline = inline || false;
    this.variable = (variable !== undefined) ? variable
        : (name.charAt && (name.charAt(0) === '@'));
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset)
- description and source-code
```javascript
tree.Ruleset = function (selectors, rules, strictImports, visibilityInfo) {
    this.selectors = selectors;
    this.rules = rules;
    this._lookups = {};
    this.strictImports = strictImports;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.RulesetCall"></a>[function <span class="apidocSignatureSpan">less.</span>tree.RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall)
- description and source-code
```javascript
tree.RulesetCall = function (variable) {
    this.variable = variable;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector)
- description and source-code
```javascript
tree.Selector = function (elements, extendList, condition, index, currentFileInfo, visibilityInfo) {
    this.elements = elements;
    this.extendList = extendList;
    this.condition = condition;
    this.currentFileInfo = currentFileInfo || {};
    if (!condition) {
        this.evaldCondition = true;
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.URL"></a>[function <span class="apidocSignatureSpan">less.</span>tree.URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL)
- description and source-code
```javascript
tree.URL = function (val, index, currentFileInfo, isEvald) {
    this.value = val;
    this.currentFileInfo = currentFileInfo;
    this.index = index;
    this.isEvald = isEvald;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit)
- description and source-code
```javascript
tree.Unit = function (numerator, denominator, backupUnit) {
    this.numerator = numerator ? numerator.slice(0).sort() : [];
    this.denominator = denominator ? denominator.slice(0).sort() : [];
    if (backupUnit) {
        this.backupUnit = backupUnit;
    } else if (numerator && numerator.length) {
        this.backupUnit = numerator[0];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Value"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Value (value)](#apidoc.element.less.tree.Value)
- description and source-code
```javascript
tree.Value = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Value requires an array argument");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Variable"></a>[function <span class="apidocSignatureSpan">less.</span>tree.Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable)
- description and source-code
```javascript
tree.Variable = function (name, index, currentFileInfo) {
    this.name = name;
    this.index = index;
    this.currentFileInfo = currentFileInfo || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor)
- description and source-code
```javascript
visitors.ExtendVisitor = function () {
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor)
- description and source-code
```javascript
visitors.ImportVisitor = function (importer, finish) {

    this._visitor = new Visitor(this);
    this._importer = importer;
    this._finish = finish;
    this.context = new contexts.Eval();
    this.importCount = 0;
    this.onceFileDetectionMap = {};
    this.recursionDetector = {};
    this._sequencer = new ImportSequencer(this._onSequencerEmpty.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor)
- description and source-code
```javascript
visitors.JoinSelectorVisitor = function () {
    this.contexts = [[]];
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor)
- description and source-code
```javascript
visitors.MarkVisibleSelectorsVisitor = function (visible) {
    this.visible = visible;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor)
- description and source-code
```javascript
visitors.ToCSSVisitor = function (context) {
    this._visitor = new Visitor(this);
    this._context = context;
    this.utils = new CSSVisitorUtils(context);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.Visitor"></a>[function <span class="apidocSignatureSpan">less.</span>visitors.Visitor (implementation)](#apidoc.element.less.visitors.Visitor)
- description and source-code
```javascript
visitors.Visitor = function (implementation) {
    this._implementation = implementation;
    this._visitFnCache = [];

    if (!_hasIndexed) {
        indexNodeTypes(tree, 1);
        _hasIndexed = true;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.writeError"></a>[function <span class="apidocSignatureSpan">less.</span>writeError (ctx, options)](#apidoc.element.less.writeError)
- description and source-code
```javascript
writeError = function (ctx, options) {
    options = options || {};
    if (options.silent) { return; }
    console.error(less.formatError(ctx, options));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.AbstractFileManager"></a>[module less.AbstractFileManager](#apidoc.module.less.AbstractFileManager)

#### <a name="apidoc.element.less.AbstractFileManager.AbstractFileManager"></a>[function <span class="apidocSignatureSpan">less.</span>AbstractFileManager ()](#apidoc.element.less.AbstractFileManager.AbstractFileManager)
- description and source-code
```javascript
AbstractFileManager = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.AbstractFileManager.prototype"></a>[module less.AbstractFileManager.prototype](#apidoc.module.less.AbstractFileManager.prototype)

#### <a name="apidoc.element.less.AbstractFileManager.prototype.alwaysMakePathsAbsolute"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>alwaysMakePathsAbsolute ()](#apidoc.element.less.AbstractFileManager.prototype.alwaysMakePathsAbsolute)
- description and source-code
```javascript
alwaysMakePathsAbsolute = function () {
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.extractUrlParts"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>extractUrlParts (url, baseUrl)](#apidoc.element.less.AbstractFileManager.prototype.extractUrlParts)
- description and source-code
```javascript
function extractUrlParts(url, baseUrl) {
    // urlParts[1] = protocol://hostname/ OR /
    // urlParts[2] = / if path relative to host base
    // urlParts[3] = directories
    // urlParts[4] = filename
    // urlParts[5] = parameters

    var urlPartsRegex = /^((?:[a-z-]+:)?\/{2}(?:[^\/\?#]*\/)|([\/\\]))?((?:[^\/\\\?#]*[\/\\])*)([^\/\\\?#]*)([#\?].*)?$/i,
        urlParts = url.match(urlPartsRegex),
        returner = {}, directories = [], i, baseUrlParts;

    if (!urlParts) {
        throw new Error("Could not parse sheet href - '" + url + "'");
    }

    // Stylesheets in IE don't always return the full path
    if (baseUrl && (!urlParts[1] || urlParts[2])) {
        baseUrlParts = baseUrl.match(urlPartsRegex);
        if (!baseUrlParts) {
            throw new Error("Could not parse page url - '" + baseUrl + "'");
        }
        urlParts[1] = urlParts[1] || baseUrlParts[1] || "";
        if (!urlParts[2]) {
            urlParts[3] = baseUrlParts[3] + urlParts[3];
        }
    }

    if (urlParts[3]) {
        directories = urlParts[3].replace(/\\/g, "/").split("/");

        // extract out . before .. so .. doesn't absorb a non-directory
        for (i = 0; i < directories.length; i++) {
            if (directories[i] === ".") {
                directories.splice(i, 1);
                i -= 1;
            }
        }

        for (i = 0; i < directories.length; i++) {
            if (directories[i] === ".." && i > 0) {
                directories.splice(i - 1, 2);
                i -= 2;
            }
        }
    }

    returner.hostPart = urlParts[1];
    returner.directories = directories;
    returner.path = (urlParts[1] || "") + directories.join("/");
    returner.fileUrl = returner.path + (urlParts[4] || "");
    returner.url = returner.fileUrl + (urlParts[5] || "");
    return returner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.getPath"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>getPath (filename)](#apidoc.element.less.AbstractFileManager.prototype.getPath)
- description and source-code
```javascript
getPath = function (filename) {
    var j = filename.lastIndexOf('?');
    if (j > 0) {
        filename = filename.slice(0, j);
    }
    j = filename.lastIndexOf('/');
    if (j < 0) {
        j = filename.lastIndexOf('\\');
    }
    if (j < 0) {
        return "";
    }
    return filename.slice(0, j + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.isPathAbsolute"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>isPathAbsolute (filename)](#apidoc.element.less.AbstractFileManager.prototype.isPathAbsolute)
- description and source-code
```javascript
isPathAbsolute = function (filename) {
    return (/^(?:[a-z-]+:|\/|\\|#)/i).test(filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.join"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>join (basePath, laterPath)](#apidoc.element.less.AbstractFileManager.prototype.join)
- description and source-code
```javascript
join = function (basePath, laterPath) {
    if (!basePath) {
        return laterPath;
    }
    return basePath + laterPath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.pathDiff"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>pathDiff (url, baseUrl)](#apidoc.element.less.AbstractFileManager.prototype.pathDiff)
- description and source-code
```javascript
function pathDiff(url, baseUrl) {
    // diff between two paths to create a relative path

    var urlParts = this.extractUrlParts(url),
        baseUrlParts = this.extractUrlParts(baseUrl),
        i, max, urlDirectories, baseUrlDirectories, diff = "";
    if (urlParts.hostPart !== baseUrlParts.hostPart) {
        return "";
    }
    max = Math.max(baseUrlParts.directories.length, urlParts.directories.length);
    for (i = 0; i < max; i++) {
        if (baseUrlParts.directories[i] !== urlParts.directories[i]) { break; }
    }
    baseUrlDirectories = baseUrlParts.directories.slice(i);
    urlDirectories = urlParts.directories.slice(i);
    for (i = 0; i < baseUrlDirectories.length - 1; i++) {
        diff += "../";
    }
    for (i = 0; i < urlDirectories.length - 1; i++) {
        diff += urlDirectories[i] + "/";
    }
    return diff;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.supportsSync"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>supportsSync ()](#apidoc.element.less.AbstractFileManager.prototype.supportsSync)
- description and source-code
```javascript
supportsSync = function () {
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.tryAppendExtension"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>tryAppendExtension (path, ext)](#apidoc.element.less.AbstractFileManager.prototype.tryAppendExtension)
- description and source-code
```javascript
tryAppendExtension = function (path, ext) {
    return /(\.[a-z]*$)|([\?;].*)$/.test(path) ? path : path + ext;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.AbstractFileManager.prototype.tryAppendLessExtension"></a>[function <span class="apidocSignatureSpan">less.AbstractFileManager.prototype.</span>tryAppendLessExtension (path)](#apidoc.element.less.AbstractFileManager.prototype.tryAppendLessExtension)
- description and source-code
```javascript
tryAppendLessExtension = function (path) {
    return this.tryAppendExtension(path, '.less');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.Environment"></a>[module less.Environment](#apidoc.module.less.Environment)

#### <a name="apidoc.element.less.Environment.Environment"></a>[function <span class="apidocSignatureSpan">less.</span>Environment (externalEnvironment, fileManagers)](#apidoc.element.less.Environment.Environment)
- description and source-code
```javascript
Environment = function (externalEnvironment, fileManagers) {
    this.fileManagers = fileManagers || [];
    externalEnvironment = externalEnvironment || {};

    var optionalFunctions = ["encodeBase64", "mimeLookup", "charsetLookup", "getSourceMapGenerator"],
        requiredFunctions = [],
        functions = requiredFunctions.concat(optionalFunctions);

    for (var i = 0; i < functions.length; i++) {
        var propName = functions[i],
            environmentFunc = externalEnvironment[propName];
        if (environmentFunc) {
            this[propName] = environmentFunc.bind(externalEnvironment);
        } else if (i < requiredFunctions.length) {
            this.warn("missing required function in environment - " + propName);
        }
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.Environment.prototype"></a>[module less.Environment.prototype](#apidoc.module.less.Environment.prototype)

#### <a name="apidoc.element.less.Environment.prototype.addFileManager"></a>[function <span class="apidocSignatureSpan">less.Environment.prototype.</span>addFileManager (fileManager)](#apidoc.element.less.Environment.prototype.addFileManager)
- description and source-code
```javascript
addFileManager = function (fileManager) {
    this.fileManagers.push(fileManager);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.Environment.prototype.clearFileManagers"></a>[function <span class="apidocSignatureSpan">less.Environment.prototype.</span>clearFileManagers ()](#apidoc.element.less.Environment.prototype.clearFileManagers)
- description and source-code
```javascript
clearFileManagers = function () {
    this.fileManagers = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.Environment.prototype.getFileManager"></a>[function <span class="apidocSignatureSpan">less.Environment.prototype.</span>getFileManager (filename, currentDirectory, options, environment, isSync)](#apidoc.element.less.Environment.prototype.getFileManager)
- description and source-code
```javascript
getFileManager = function (filename, currentDirectory, options, environment, isSync) {

    if (!filename) {
        logger.warn("getFileManager called with no filename.. Please report this issue. continuing.");
    }
    if (currentDirectory == null) {
        logger.warn("getFileManager called with null directory.. Please report this issue. continuing.");
    }

    var fileManagers = this.fileManagers;
    if (options.pluginManager) {
        fileManagers = [].concat(fileManagers).concat(options.pluginManager.getFileManagers());
    }
    for (var i = fileManagers.length - 1; i >= 0 ; i--) {
        var fileManager = fileManagers[i];
        if (fileManager[isSync ? "supportsSync" : "supports"](filename, currentDirectory, options, environment)) {
            return fileManager;
        }
    }
    return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.FileManager"></a>[module less.FileManager](#apidoc.module.less.FileManager)

#### <a name="apidoc.element.less.FileManager.FileManager"></a>[function <span class="apidocSignatureSpan">less.</span>FileManager ()](#apidoc.element.less.FileManager.FileManager)
- description and source-code
```javascript
FileManager = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.FileManager.prototype"></a>[module less.FileManager.prototype](#apidoc.module.less.FileManager.prototype)

#### <a name="apidoc.element.less.FileManager.prototype.loadFile"></a>[function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>loadFile (filename, currentDirectory, options, environment, callback)](#apidoc.element.less.FileManager.prototype.loadFile)
- description and source-code
```javascript
loadFile = function (filename, currentDirectory, options, environment, callback) {
    var fullFilename,
        data,
        isAbsoluteFilename = this.isPathAbsolute(filename),
        filenamesTried = [];

    options = options || {};

    if (options.syncImport || !PromiseConstructor) {
        data = this.loadFileSync(filename, currentDirectory, options, environment, 'utf-8');
        callback(data.error, data);
        return;
    }

    var paths = isAbsoluteFilename ? [""] : [currentDirectory];
    if (options.paths) { paths.push.apply(paths, options.paths); }
    if (!isAbsoluteFilename && paths.indexOf('.') === -1) { paths.push('.'); }

    // promise is guaranteed to be asyncronous
    // which helps as it allows the file handle
    // to be closed before it continues with the next file
    return new PromiseConstructor(function(fulfill, reject) {
        (function tryPathIndex(i) {
            if (i < paths.length) {
                fullFilename = filename;
                if (paths[i]) {
                    fullFilename = path.join(paths[i], fullFilename);
                }
                fs.stat(fullFilename, function (err) {
                    if (err) {
                        filenamesTried.push(fullFilename);
                        tryPathIndex(i + 1);
                    } else {
                        fs.readFile(fullFilename, 'utf-8', function(e, data) {
                            if (e) { reject(e); return; }

                            fulfill({ contents: data, filename: fullFilename});
                        });
                    }
                });
            } else {
                reject({ type: 'File', message: "'" + filename + "' wasn't found. Tried - " + filenamesTried.join(",") });
            }
        }(0));
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.FileManager.prototype.loadFileSync"></a>[function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>loadFileSync (filename, currentDirectory, options, environment, encoding)](#apidoc.element.less.FileManager.prototype.loadFileSync)
- description and source-code
```javascript
loadFileSync = function (filename, currentDirectory, options, environment, encoding) {
    var fullFilename, paths, filenamesTried = [], isAbsoluteFilename = this.isPathAbsolute(filename) , data;
    options = options || {};

    paths = isAbsoluteFilename ? [""] : [currentDirectory];
    if (options.paths) {
        paths.push.apply(paths, options.paths);
    }
    if (!isAbsoluteFilename && paths.indexOf('.') === -1) {
        paths.push('.');
    }

    var err, result;
    for (var i = 0; i < paths.length; i++) {
        try {
            fullFilename = filename;
            if (paths[i]) {
                fullFilename = path.join(paths[i], fullFilename);
            }
            filenamesTried.push(fullFilename);
            fs.statSync(fullFilename);
            break;
        } catch (e) {
            fullFilename = null;
        }
    }

    if (!fullFilename) {
        err = { type: 'File', message: "'" + filename + "' wasn't found. Tried - " + filenamesTried.join(",") };
        result = { error: err };
    } else {
        data = fs.readFileSync(fullFilename, encoding);
        result = { contents: data, filename: fullFilename};
    }

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.FileManager.prototype.supports"></a>[function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>supports (filename, currentDirectory, options, environment)](#apidoc.element.less.FileManager.prototype.supports)
- description and source-code
```javascript
supports = function (filename, currentDirectory, options, environment) {
    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.FileManager.prototype.supportsSync"></a>[function <span class="apidocSignatureSpan">less.FileManager.prototype.</span>supportsSync (filename, currentDirectory, options, environment)](#apidoc.element.less.FileManager.prototype.supportsSync)
- description and source-code
```javascript
supportsSync = function (filename, currentDirectory, options, environment) {
    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.ImportManager"></a>[module less.ImportManager](#apidoc.module.less.ImportManager)

#### <a name="apidoc.element.less.ImportManager.ImportManager"></a>[function <span class="apidocSignatureSpan">less.</span>ImportManager (context, rootFileInfo)](#apidoc.element.less.ImportManager.ImportManager)
- description and source-code
```javascript
ImportManager = function (context, rootFileInfo) {
    this.rootFilename = rootFileInfo.filename;
    this.paths = context.paths || [];  // Search paths, when importing
    this.contents = {};             // map - filename to contents of all the files
    this.contentsIgnoredChars = {}; // map - filename to lines at the beginning of each file to ignore
    this.mime = context.mime;
    this.error = null;
    this.context = context;
    // Deprecated? Unused outside of here, could be useful.
    this.queue = [];        // Files which haven't been imported yet
    this.files = {};        // Holds the imported parse trees.
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.ImportManager.prototype"></a>[module less.ImportManager.prototype](#apidoc.module.less.ImportManager.prototype)

#### <a name="apidoc.element.less.ImportManager.prototype.push"></a>[function <span class="apidocSignatureSpan">less.ImportManager.prototype.</span>push (path, tryAppendLessExtension, currentFileInfo, importOptions, callback)](#apidoc.element.less.ImportManager.prototype.push)
- description and source-code
```javascript
push = function (path, tryAppendLessExtension, currentFileInfo, importOptions, callback) {
    var importManager = this;
    this.queue.push(path);

    var fileParsedFunc = function (e, root, fullPath) {
        importManager.queue.splice(importManager.queue.indexOf(path), 1); // Remove the path from the queue

        var importedEqualsRoot = fullPath === importManager.rootFilename;
        if (importOptions.optional && e) {
            callback(null, {rules:[]}, false, null);
        }
        else {
            importManager.files[fullPath] = root;
            if (e && !importManager.error) { importManager.error = e; }
            callback(e, root, importedEqualsRoot, fullPath);
        }
    };

    var newFileInfo = {
        relativeUrls: this.context.relativeUrls,
        entryPath: currentFileInfo.entryPath,
        rootpath: currentFileInfo.rootpath,
        rootFilename: currentFileInfo.rootFilename
    };

    var fileManager = environment.getFileManager(path, currentFileInfo.currentDirectory, this.context, environment);

    if (!fileManager) {
        fileParsedFunc({ message: "Could not find a file-manager for " + path });
        return;
    }

    if (tryAppendLessExtension) {
        path = fileManager.tryAppendExtension(path, importOptions.plugin ? ".js" : ".less");
    }

    var loadFileCallback = function(loadedFile) {
        var resolvedFilename = loadedFile.filename,
            contents = loadedFile.contents.replace(/^\uFEFF/, '');

        // Pass on an updated rootpath if path of imported file is relative and file
        // is in a (sub|sup) directory
        //
        // Examples:
        // - If path of imported file is 'module/nav/nav.less' and rootpath is 'less/',
        //   then rootpath should become 'less/module/nav/'
        // - If path of imported file is '../mixins.less' and rootpath is 'less/',
        //   then rootpath should become 'less/../'
        newFileInfo.currentDirectory = fileManager.getPath(resolvedFilename);
        if (newFileInfo.relativeUrls) {
            newFileInfo.rootpath = fileManager.join(
                (importManager.context.rootpath || ""),
                fileManager.pathDiff(newFileInfo.currentDirectory, newFileInfo.entryPath));

            if (!fileManager.isPathAbsolute(newFileInfo.rootpath) && fileManager.alwaysMakePathsAbsolute()) {
                newFileInfo.rootpath = fileManager.join(newFileInfo.entryPath, newFileInfo.rootpath);
            }
        }
        newFileInfo.filename = resolvedFilename;

        var newEnv = new contexts.Parse(importManager.context);

        newEnv.processImports = false;
        importManager.contents[resolvedFilename] = contents;

        if (currentFileInfo.reference || importOptions.reference) {
            newFileInfo.reference = true;
        }

        if (importOptions.plugin) {
            new FunctionImporter(newEnv, newFileInfo).eval(contents, function (e, root) {
                fileParsedFunc(e, root, resolvedFilename);
            });
        } else if (importOptions.inline) {
            fileParsedFunc(null, contents, resolvedFilename);
        } else {
            new Parser(newEnv, importManager, newFileInfo).parse(contents, function (e, root) {
                fileParsedFunc(e, root, resolvedFilename);
            });
        }
    };

    var promise = fileManager.loadFile(path, currentFileInfo.currentDirectory, this.context, environment,
        function(err, loadedFile) {
        if (err) {
            fileParsedFunc(err);
        } else {
            loadFileCallback(loadedFile);
        }
    });
    if (promise) {
        promise.then(loadFileCallback, fileParsedFunc);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.LessError"></a>[module less.LessError](#apidoc.module.less.LessError)

#### <a name="apidoc.element.less.LessError.LessError"></a>[function <span class="apidocSignatureSpan">less.</span>LessError (e, importManager, currentFilename)](#apidoc.element.less.LessError.LessError)
- description and source-code
```javascript
function LessError(e, importManager, currentFilename) {

    Error.call(this);

    var filename = e.filename || currentFilename;

    if (importManager && filename) {
        var input = importManager.contents[filename],
            loc = utils.getLocation(e.index, input),
            line = loc.line,
            col  = loc.column,
            callLine = e.call && utils.getLocation(e.call, input).line,
            lines = input.split('\n');

        this.type = e.type || 'Syntax';
        this.filename = filename;
        this.index = e.index;
        this.line = typeof line === 'number' ? line + 1 : null;
        this.callLine = callLine + 1;
        this.callExtract = lines[callLine];
        this.column = col;
        this.extract = [
            lines[line - 1],
            lines[line],
            lines[line + 1]
        ];
    }
    this.message = e.message;
    this.stack = e.stack;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.LessError.prototype"></a>[module less.LessError.prototype](#apidoc.module.less.LessError.prototype)

#### <a name="apidoc.element.less.LessError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">less.LessError.prototype.</span>constructor (e, importManager, currentFilename)](#apidoc.element.less.LessError.prototype.constructor)
- description and source-code
```javascript
function LessError(e, importManager, currentFilename) {

    Error.call(this);

    var filename = e.filename || currentFilename;

    if (importManager && filename) {
        var input = importManager.contents[filename],
            loc = utils.getLocation(e.index, input),
            line = loc.line,
            col  = loc.column,
            callLine = e.call && utils.getLocation(e.call, input).line,
            lines = input.split('\n');

        this.type = e.type || 'Syntax';
        this.filename = filename;
        this.index = e.index;
        this.line = typeof line === 'number' ? line + 1 : null;
        this.callLine = callLine + 1;
        this.callExtract = lines[callLine];
        this.column = col;
        this.extract = [
            lines[line - 1],
            lines[line],
            lines[line + 1]
        ];
    }
    this.message = e.message;
    this.stack = e.stack;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.ParseTree"></a>[module less.ParseTree](#apidoc.module.less.ParseTree)

#### <a name="apidoc.element.less.ParseTree.ParseTree"></a>[function <span class="apidocSignatureSpan">less.</span>ParseTree (root, imports)](#apidoc.element.less.ParseTree.ParseTree)
- description and source-code
```javascript
ParseTree = function (root, imports) {
    this.root = root;
    this.imports = imports;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.ParseTree.prototype"></a>[module less.ParseTree.prototype](#apidoc.module.less.ParseTree.prototype)

#### <a name="apidoc.element.less.ParseTree.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.ParseTree.prototype.</span>toCSS (options)](#apidoc.element.less.ParseTree.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (options) {
    var evaldRoot, result = {}, sourceMapBuilder;
    try {
        evaldRoot = transformTree(this.root, options);
    } catch (e) {
        throw new LessError(e, this.imports);
    }

    try {
        var compress = Boolean(options.compress);
        if (compress) {
            logger.warn("The compress option has been deprecated. We recommend you use a dedicated css minifier, for instance see
 less-plugin-clean-css.");
        }

        var toCSSOptions = {
            compress: compress,
            dumpLineNumbers: options.dumpLineNumbers,
            strictUnits: Boolean(options.strictUnits),
            numPrecision: 8};

        if (options.sourceMap) {
            sourceMapBuilder = new SourceMapBuilder(options.sourceMap);
            result.css = sourceMapBuilder.toCSS(evaldRoot, toCSSOptions, this.imports);
        } else {
            result.css = evaldRoot.toCSS(toCSSOptions);
        }
    } catch (e) {
        throw new LessError(e, this.imports);
    }

    if (options.pluginManager) {
        var postProcessors = options.pluginManager.getPostProcessors();
        for (var i = 0; i < postProcessors.length; i++) {
            result.css = postProcessors[i].process(result.css, { sourceMap: sourceMapBuilder, options: options, imports: this.imports
 });
        }
    }
    if (options.sourceMap) {
        result.map = sourceMapBuilder.getExternalSourceMap();
    }

    result.imports = [];
    for (var file in this.imports.files) {
        if (this.imports.files.hasOwnProperty(file) && file !== this.imports.rootFilename) {
            result.imports.push(file);
        }
    }
    return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.Parser"></a>[module less.Parser](#apidoc.module.less.Parser)

#### <a name="apidoc.element.less.Parser.Parser"></a>[function <span class="apidocSignatureSpan">less.</span>Parser (context, imports, fileInfo)](#apidoc.element.less.Parser.Parser)
- description and source-code
```javascript
function Parser(context, imports, fileInfo) {
    var parsers,
        parserInput = getParserInput();

    function error(msg, type) {
        throw new LessError(
            {
                index: parserInput.i,
                filename: fileInfo.filename,
                type: type || 'Syntax',
                message: msg
            },
            imports
        );
    }

    function expect(arg, msg, index) {
        // some older browsers return typeof 'function' for RegExp
        var result = (arg instanceof Function) ? arg.call(parsers) : parserInput.$re(arg);
        if (result) {
            return result;
        }
        error(msg || (typeof arg === 'string' ? "expected '" + arg + "' got '" + parserInput.currentChar() + "'"
                                               : "unexpected token"));
    }

    // Specialization of expect()
    function expectChar(arg, msg) {
        if (parserInput.$char(arg)) {
            return arg;
        }
        error(msg || "expected '" + arg + "' got '" + parserInput.currentChar() + "'");
    }

    function getDebugInfo(index) {
        var filename = fileInfo.filename;

        return {
            lineNumber: utils.getLocation(index, parserInput.getInput()).line + 1,
            fileName: filename
        };
    }

    //
    // The Parser
    //
    return {

        //
        // Parse an input string into an abstract syntax tree,
        // @param str A string containing 'less' markup
        // @param callback call 'callback' when done.
        // @param [additionalData] An optional map which can contains vars - a map (key, value) of variables to apply
        //
        parse: function (str, callback, additionalData) {
            var root, error = null, globalVars, modifyVars, ignored, preText = "";

            globalVars = (additionalData && additionalData.globalVars) ? Parser.serializeVars(additionalData.globalVars) + '\n' : '';
            modifyVars = (additionalData && additionalData.modifyVars) ? '\n' + Parser.serializeVars(additionalData.modifyVars) : '';

            if (context.pluginManager) {
                var preProcessors = context.pluginManager.getPreProcessors();
                for (var i = 0; i < preProcessors.length; i++) {
                    str = preProcessors[i].process(str, { context: context, imports: imports, fileInfo: fileInfo });
                }
            }

            if (globalVars || (additionalData && additionalData.banner)) {
                preText = ((additionalData && additionalData.banner) ? additionalData.banner : "") + globalVars;
                ignored = imports.contentsIgnoredChars;
                ignored[fileInfo.filename] = ignored[fileInfo.filename] || 0;
                ignored[fileInfo.filename] += preText.length;
            }

            str = str.replace(/\r\n?/g, '\n');
            // Remove potential UTF Byte Order Mark
            str = preText + str.replace(/^\uFEFF/, '') + modifyVars;
            imports.contents[fileInfo.filename] = str;

            // Start with the primary rule.
            // The whole syntax tree is held under a Ruleset node,
            // with the 'root' property set to true, so no '{}' are
            // output. The callback is called when the input is parsed.
            try {
                parserInput.start(str, context.chunkInput, function fail(msg, index) {
                    throw new LessError({
                        index: index,
                        type: 'Parse',
                        message: msg,
                        filename: fileInfo.filename
                    }, imports);
                });

                root = new(tree.Ruleset)(null, this.parsers.primary());
                root.root = true;
                root.firstRoot = true;
            } catch (e) {
                return callback(new LessError(e, imports, fileInfo.filename));
            }

            // If 'i' is smaller than the 'input.length - 1',
            // it means the parser wasn't able to parse the whole
            // string, so we've got a parsing error. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.Parser.serializeVars"></a>[function <span class="apidocSignatureSpan">less.Parser.</span>serializeVars (vars)](#apidoc.element.less.Parser.serializeVars)
- description and source-code
```javascript
serializeVars = function (vars) {
    var s = '';

    for (var name in vars) {
        if (Object.hasOwnProperty.call(vars, name)) {
            var value = vars[name];
            s += ((name[0] === '@') ? '' : '@') + name + ': ' + value +
                ((String(value).slice(-1) === ';') ? '' : ';');
        }
    }

    return s;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.PluginLoader"></a>[module less.PluginLoader](#apidoc.module.less.PluginLoader)

#### <a name="apidoc.element.less.PluginLoader.PluginLoader"></a>[function <span class="apidocSignatureSpan">less.</span>PluginLoader (less)](#apidoc.element.less.PluginLoader.PluginLoader)
- description and source-code
```javascript
PluginLoader = function (less) {
    this.less = less;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.PluginLoader.prototype"></a>[module less.PluginLoader.prototype](#apidoc.module.less.PluginLoader.prototype)

#### <a name="apidoc.element.less.PluginLoader.prototype.compareVersion"></a>[function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>compareVersion (aVersion, bVersion)](#apidoc.element.less.PluginLoader.prototype.compareVersion)
- description and source-code
```javascript
compareVersion = function (aVersion, bVersion) {
    for (var i = 0; i < aVersion.length; i++) {
        if (aVersion[i] !== bVersion[i]) {
            return parseInt(aVersion[i]) > parseInt(bVersion[i]) ? -1 : 1;
        }
    }
    return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginLoader.prototype.printUsage"></a>[function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>printUsage (plugins)](#apidoc.element.less.PluginLoader.prototype.printUsage)
- description and source-code
```javascript
printUsage = function (plugins) {
    for (var i = 0; i < plugins.length; i++) {
        var plugin = plugins[i];
        if (plugin.printUsage) {
            plugin.printUsage();
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginLoader.prototype.tryLoadPlugin"></a>[function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>tryLoadPlugin (name, argument)](#apidoc.element.less.PluginLoader.prototype.tryLoadPlugin)
- description and source-code
```javascript
tryLoadPlugin = function (name, argument) {
    var plugin = this.tryRequirePlugin(name);
    if (plugin) {
        // support plugins being a function
        // so that the plugin can be more usable programmatically
        if (typeof plugin === "function") {
            plugin = new plugin();
        }
        if (plugin.minVersion) {
            if (this.compareVersion(plugin.minVersion, this.less.version) < 0) {
                console.log("plugin " + name + " requires version " + this.versionToString(plugin.minVersion));
                return null;
            }
        }
        if (argument) {
            if (!plugin.setOptions) {
                console.log("options have been provided but the plugin " + name + "does not support any options");
                return null;
            }
            try {
                plugin.setOptions(argument);
            }
            catch(e) {
                console.log("Error setting options on plugin " + name);
                console.log(e.message);
                return null;
            }
        }
        return plugin;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginLoader.prototype.tryRequirePlugin"></a>[function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>tryRequirePlugin (name)](#apidoc.element.less.PluginLoader.prototype.tryRequirePlugin)
- description and source-code
```javascript
tryRequirePlugin = function (name) {
    // is at the same level as the less.js module
    try {
        return require("../../../" + name);
    }
    catch(e) {
    }
    // is installed as a sub dependency of the current folder
    try {
        return require(path.join(process.cwd(), "node_modules", name));
    }
    catch(e) {
    }
    // is referenced relative to the current directory
    try {
        return require(path.join(process.cwd(), name));
    }
    catch(e) {
    }
    // unlikely - would have to be a dependency of where this code was running (less.js)...
    if (name[0] !== '.') {
        try {
            return require(name);
        }
        catch(e) {
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginLoader.prototype.versionToString"></a>[function <span class="apidocSignatureSpan">less.PluginLoader.prototype.</span>versionToString (version)](#apidoc.element.less.PluginLoader.prototype.versionToString)
- description and source-code
```javascript
versionToString = function (version) {
    var versionString = "";
    for (var i = 0; i < version.length; i++) {
        versionString += (versionString ? "." : "") + version[i];
    }
    return versionString;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.PluginManager"></a>[module less.PluginManager](#apidoc.module.less.PluginManager)

#### <a name="apidoc.element.less.PluginManager.PluginManager"></a>[function <span class="apidocSignatureSpan">less.</span>PluginManager (less)](#apidoc.element.less.PluginManager.PluginManager)
- description and source-code
```javascript
PluginManager = function (less) {
    this.less = less;
    this.visitors = [];
    this.preProcessors = [];
    this.postProcessors = [];
    this.installedPlugins = [];
    this.fileManagers = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.PluginManager.prototype"></a>[module less.PluginManager.prototype](#apidoc.module.less.PluginManager.prototype)

#### <a name="apidoc.element.less.PluginManager.prototype.addFileManager"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addFileManager (manager)](#apidoc.element.less.PluginManager.prototype.addFileManager)
- description and source-code
```javascript
addFileManager = function (manager) {
    this.fileManagers.push(manager);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.addPlugin"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPlugin (plugin)](#apidoc.element.less.PluginManager.prototype.addPlugin)
- description and source-code
```javascript
addPlugin = function (plugin) {
    this.installedPlugins.push(plugin);
    plugin.install(this.less, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.addPlugins"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPlugins (plugins)](#apidoc.element.less.PluginManager.prototype.addPlugins)
- description and source-code
```javascript
addPlugins = function (plugins) {
    if (plugins) {
        for (var i = 0; i < plugins.length; i++) {
            this.addPlugin(plugins[i]);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.addPostProcessor"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPostProcessor (postProcessor, priority)](#apidoc.element.less.PluginManager.prototype.addPostProcessor)
- description and source-code
```javascript
addPostProcessor = function (postProcessor, priority) {
    var indexToInsertAt;
    for (indexToInsertAt = 0; indexToInsertAt < this.postProcessors.length; indexToInsertAt++) {
        if (this.postProcessors[indexToInsertAt].priority >= priority) {
            break;
        }
    }
    this.postProcessors.splice(indexToInsertAt, 0, {postProcessor: postProcessor, priority: priority});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.addPreProcessor"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addPreProcessor (preProcessor, priority)](#apidoc.element.less.PluginManager.prototype.addPreProcessor)
- description and source-code
```javascript
addPreProcessor = function (preProcessor, priority) {
    var indexToInsertAt;
    for (indexToInsertAt = 0; indexToInsertAt < this.preProcessors.length; indexToInsertAt++) {
        if (this.preProcessors[indexToInsertAt].priority >= priority) {
            break;
        }
    }
    this.preProcessors.splice(indexToInsertAt, 0, {preProcessor: preProcessor, priority: priority});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.addVisitor"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>addVisitor (visitor)](#apidoc.element.less.PluginManager.prototype.addVisitor)
- description and source-code
```javascript
addVisitor = function (visitor) {
    this.visitors.push(visitor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.getFileManagers"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getFileManagers ()](#apidoc.element.less.PluginManager.prototype.getFileManagers)
- description and source-code
```javascript
getFileManagers = function () {
    return this.fileManagers;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.getPostProcessors"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getPostProcessors ()](#apidoc.element.less.PluginManager.prototype.getPostProcessors)
- description and source-code
```javascript
getPostProcessors = function () {
    var postProcessors = [];
    for (var i = 0; i < this.postProcessors.length; i++) {
        postProcessors.push(this.postProcessors[i].postProcessor);
    }
    return postProcessors;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.getPreProcessors"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getPreProcessors ()](#apidoc.element.less.PluginManager.prototype.getPreProcessors)
- description and source-code
```javascript
getPreProcessors = function () {
    var preProcessors = [];
    for (var i = 0; i < this.preProcessors.length; i++) {
        preProcessors.push(this.preProcessors[i].preProcessor);
    }
    return preProcessors;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.PluginManager.prototype.getVisitors"></a>[function <span class="apidocSignatureSpan">less.PluginManager.prototype.</span>getVisitors ()](#apidoc.element.less.PluginManager.prototype.getVisitors)
- description and source-code
```javascript
getVisitors = function () {
    return this.visitors;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.SourceMapBuilder"></a>[module less.SourceMapBuilder](#apidoc.module.less.SourceMapBuilder)

#### <a name="apidoc.element.less.SourceMapBuilder.SourceMapBuilder"></a>[function <span class="apidocSignatureSpan">less.</span>SourceMapBuilder (options)](#apidoc.element.less.SourceMapBuilder.SourceMapBuilder)
- description and source-code
```javascript
SourceMapBuilder = function (options) {
    this.options = options;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.SourceMapBuilder.prototype"></a>[module less.SourceMapBuilder.prototype](#apidoc.module.less.SourceMapBuilder.prototype)

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.getCSSAppendage"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getCSSAppendage ()](#apidoc.element.less.SourceMapBuilder.prototype.getCSSAppendage)
- description and source-code
```javascript
getCSSAppendage = function () {

    var sourceMapURL = this.sourceMapURL;
    if (this.options.sourceMapFileInline) {
        if (this.sourceMap === undefined) {
            return "";
        }
        sourceMapURL = "data:application/json;base64," + environment.encodeBase64(this.sourceMap);
    }

    if (sourceMapURL) {
        return "/*# sourceMappingURL=" + sourceMapURL + " */";
    }
    return "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.getExternalSourceMap"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getExternalSourceMap ()](#apidoc.element.less.SourceMapBuilder.prototype.getExternalSourceMap)
- description and source-code
```javascript
getExternalSourceMap = function () {
    return this.sourceMap;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.getInputFilename"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getInputFilename ()](#apidoc.element.less.SourceMapBuilder.prototype.getInputFilename)
- description and source-code
```javascript
getInputFilename = function () {
    return this.sourceMapInputFilename;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.getOutputFilename"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getOutputFilename ()](#apidoc.element.less.SourceMapBuilder.prototype.getOutputFilename)
- description and source-code
```javascript
getOutputFilename = function () {
    return this.options.sourceMapOutputFilename;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.getSourceMapURL"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>getSourceMapURL ()](#apidoc.element.less.SourceMapBuilder.prototype.getSourceMapURL)
- description and source-code
```javascript
getSourceMapURL = function () {
    return this.sourceMapURL;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.isInline"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>isInline ()](#apidoc.element.less.SourceMapBuilder.prototype.isInline)
- description and source-code
```javascript
isInline = function () {
    return this.options.sourceMapFileInline;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.setExternalSourceMap"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>setExternalSourceMap (sourceMap)](#apidoc.element.less.SourceMapBuilder.prototype.setExternalSourceMap)
- description and source-code
```javascript
setExternalSourceMap = function (sourceMap) {
    this.sourceMap = sourceMap;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapBuilder.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.SourceMapBuilder.prototype.</span>toCSS (rootNode, options, imports)](#apidoc.element.less.SourceMapBuilder.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (rootNode, options, imports) {
    var sourceMapOutput = new SourceMapOutput(
        {
            contentsIgnoredCharsMap: imports.contentsIgnoredChars,
            rootNode: rootNode,
            contentsMap: imports.contents,
            sourceMapFilename: this.options.sourceMapFilename,
            sourceMapURL: this.options.sourceMapURL,
            outputFilename: this.options.sourceMapOutputFilename,
            sourceMapBasepath: this.options.sourceMapBasepath,
            sourceMapRootpath: this.options.sourceMapRootpath,
            outputSourceFiles: this.options.outputSourceFiles,
            sourceMapGenerator: this.options.sourceMapGenerator,
            sourceMapFileInline: this.options.sourceMapFileInline
        });

    var css = sourceMapOutput.toCSS(options);
    this.sourceMap = sourceMapOutput.sourceMap;
    this.sourceMapURL = sourceMapOutput.sourceMapURL;
    if (this.options.sourceMapInputFilename) {
        this.sourceMapInputFilename = sourceMapOutput.normalizeFilename(this.options.sourceMapInputFilename);
    }
    return css + this.getCSSAppendage();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.SourceMapOutput"></a>[module less.SourceMapOutput](#apidoc.module.less.SourceMapOutput)

#### <a name="apidoc.element.less.SourceMapOutput.SourceMapOutput"></a>[function <span class="apidocSignatureSpan">less.</span>SourceMapOutput (options)](#apidoc.element.less.SourceMapOutput.SourceMapOutput)
- description and source-code
```javascript
SourceMapOutput = function (options) {
    this._css = [];
    this._rootNode = options.rootNode;
    this._contentsMap = options.contentsMap;
    this._contentsIgnoredCharsMap = options.contentsIgnoredCharsMap;
    if (options.sourceMapFilename) {
        this._sourceMapFilename = options.sourceMapFilename.replace(/\\/g, '/');
    }
    this._outputFilename = options.outputFilename;
    this.sourceMapURL = options.sourceMapURL;
    if (options.sourceMapBasepath) {
        this._sourceMapBasepath = options.sourceMapBasepath.replace(/\\/g, '/');
    }
    if (options.sourceMapRootpath) {
        this._sourceMapRootpath = options.sourceMapRootpath.replace(/\\/g, '/');
        if (this._sourceMapRootpath.charAt(this._sourceMapRootpath.length - 1) !== '/') {
            this._sourceMapRootpath += '/';
        }
    } else {
        this._sourceMapRootpath = "";
    }
    this._outputSourceFiles = options.outputSourceFiles;
    this._sourceMapGeneratorConstructor = environment.getSourceMapGenerator();

    this._lineNumber = 0;
    this._column = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.SourceMapOutput.prototype"></a>[module less.SourceMapOutput.prototype](#apidoc.module.less.SourceMapOutput.prototype)

#### <a name="apidoc.element.less.SourceMapOutput.prototype.add"></a>[function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>add (chunk, fileInfo, index, mapLines)](#apidoc.element.less.SourceMapOutput.prototype.add)
- description and source-code
```javascript
add = function (chunk, fileInfo, index, mapLines) {

    //ignore adding empty strings
    if (!chunk) {
        return;
    }

    var lines,
        sourceLines,
        columns,
        sourceColumns,
        i;

    if (fileInfo) {
        var inputSource = this._contentsMap[fileInfo.filename];

        // remove vars/banner added to the top of the file
        if (this._contentsIgnoredCharsMap[fileInfo.filename]) {
            // adjust the index
            index -= this._contentsIgnoredCharsMap[fileInfo.filename];
            if (index < 0) { index = 0; }
            // adjust the source
            inputSource = inputSource.slice(this._contentsIgnoredCharsMap[fileInfo.filename]);
        }
        inputSource = inputSource.substring(0, index);
        sourceLines = inputSource.split("\n");
        sourceColumns = sourceLines[sourceLines.length - 1];
    }

    lines = chunk.split("\n");
    columns = lines[lines.length - 1];

    if (fileInfo) {
        if (!mapLines) {
            this._sourceMapGenerator.addMapping({ generated: { line: this._lineNumber + 1, column: this._column},
                original: { line: sourceLines.length, column: sourceColumns.length},
                source: this.normalizeFilename(fileInfo.filename)});
        } else {
            for (i = 0; i < lines.length; i++) {
                this._sourceMapGenerator.addMapping({ generated: { line: this._lineNumber + i + 1, column: i === 0 ? this._column
 : 0},
                    original: { line: sourceLines.length + i, column: i === 0 ? sourceColumns.length : 0},
                    source: this.normalizeFilename(fileInfo.filename)});
            }
        }
    }

    if (lines.length === 1) {
        this._column += columns.length;
    } else {
        this._lineNumber += lines.length - 1;
        this._column = columns.length;
    }

    this._css.push(chunk);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapOutput.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>isEmpty ()](#apidoc.element.less.SourceMapOutput.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
    return this._css.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapOutput.prototype.normalizeFilename"></a>[function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>normalizeFilename (filename)](#apidoc.element.less.SourceMapOutput.prototype.normalizeFilename)
- description and source-code
```javascript
normalizeFilename = function (filename) {
    filename = filename.replace(/\\/g, '/');

    if (this._sourceMapBasepath && filename.indexOf(this._sourceMapBasepath) === 0) {
        filename = filename.substring(this._sourceMapBasepath.length);
        if (filename.charAt(0) === '\\' || filename.charAt(0) === '/') {
            filename = filename.substring(1);
        }
    }
    return (this._sourceMapRootpath || "") + filename;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.SourceMapOutput.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.SourceMapOutput.prototype.</span>toCSS (context)](#apidoc.element.less.SourceMapOutput.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (context) {
    this._sourceMapGenerator = new this._sourceMapGeneratorConstructor({ file: this._outputFilename, sourceRoot: null });

    if (this._outputSourceFiles) {
        for (var filename in this._contentsMap) {
            if (this._contentsMap.hasOwnProperty(filename)) {
                var source = this._contentsMap[filename];
                if (this._contentsIgnoredCharsMap[filename]) {
                    source = source.slice(this._contentsIgnoredCharsMap[filename]);
                }
                this._sourceMapGenerator.setSourceContent(this.normalizeFilename(filename), source);
            }
        }
    }

    this._rootNode.genCSS(context, this);

    if (this._css.length > 0) {
        var sourceMapURL,
            sourceMapContent = JSON.stringify(this._sourceMapGenerator.toJSON());

        if (this.sourceMapURL) {
            sourceMapURL = this.sourceMapURL;
        } else if (this._sourceMapFilename) {
            sourceMapURL = this._sourceMapFilename;
        }
        this.sourceMapURL = sourceMapURL;

        this.sourceMap = sourceMapContent;
    }

    return this._css.join('');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.UrlFileManager"></a>[module less.UrlFileManager](#apidoc.module.less.UrlFileManager)

#### <a name="apidoc.element.less.UrlFileManager.UrlFileManager"></a>[function <span class="apidocSignatureSpan">less.</span>UrlFileManager ()](#apidoc.element.less.UrlFileManager.UrlFileManager)
- description and source-code
```javascript
UrlFileManager = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.UrlFileManager.prototype"></a>[module less.UrlFileManager.prototype](#apidoc.module.less.UrlFileManager.prototype)

#### <a name="apidoc.element.less.UrlFileManager.prototype.loadFile"></a>[function <span class="apidocSignatureSpan">less.UrlFileManager.prototype.</span>loadFile (filename, currentDirectory, options, environment)](#apidoc.element.less.UrlFileManager.prototype.loadFile)
- description and source-code
```javascript
loadFile = function (filename, currentDirectory, options, environment) {
    if (!PromiseConstructor) {
        PromiseConstructor = typeof Promise === 'undefined' ? require('promise') : Promise;
    }
    return new PromiseConstructor(function(fulfill, reject) {
        if (request === undefined) {
            try { request = require('request'); }
            catch(e) { request = null; }
        }
        if (!request) {
            reject({ type: 'File', message: "optional dependency 'request' required to import over http(s)\n" });
            return;
        }

        var urlStr = isUrlRe.test( filename ) ? filename : url.resolve(currentDirectory, filename),
            urlObj = url.parse(urlStr);

        if (!urlObj.protocol) {
            urlObj.protocol = "http";
            urlStr = urlObj.format();
        }

        request.get({uri: urlStr, strictSSL: !options.insecure }, function (error, res, body) {
            if (error) {
                reject({ type: 'File', message: "resource '" + urlStr + "' gave this Error:\n  " + error + "\n" });
                return;
            }
            if (res && res.statusCode === 404) {
                reject({ type: 'File', message: "resource '" + urlStr + "' was not found\n" });
                return;
            }
            if (!body) {
                logger.warn('Warning: Empty body (HTTP ' + res.statusCode + ') returned by "' + urlStr + '"');
            }
            fulfill({ contents: body, filename: urlStr });
        });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.UrlFileManager.prototype.supports"></a>[function <span class="apidocSignatureSpan">less.UrlFileManager.prototype.</span>supports (filename, currentDirectory, options, environment)](#apidoc.element.less.UrlFileManager.prototype.supports)
- description and source-code
```javascript
supports = function (filename, currentDirectory, options, environment) {
    return isUrlRe.test( filename ) || isUrlRe.test(currentDirectory);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.contexts"></a>[module less.contexts](#apidoc.module.less.contexts)

#### <a name="apidoc.element.less.contexts.Eval"></a>[function <span class="apidocSignatureSpan">less.contexts.</span>Eval (options, frames)](#apidoc.element.less.contexts.Eval)
- description and source-code
```javascript
Eval = function (options, frames) {
    copyFromOriginal(options, this, evalCopyProperties);

    if (typeof this.paths === "string") { this.paths = [this.paths]; }

    this.frames = frames || [];
    this.importantScope = this.importantScope || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Parse"></a>[function <span class="apidocSignatureSpan">less.contexts.</span>Parse (options)](#apidoc.element.less.contexts.Parse)
- description and source-code
```javascript
Parse = function (options) {
    copyFromOriginal(options, this, parseCopyProperties);

    if (typeof this.paths === "string") { this.paths = [this.paths]; }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.contexts.Eval"></a>[module less.contexts.Eval](#apidoc.module.less.contexts.Eval)

#### <a name="apidoc.element.less.contexts.Eval.Eval"></a>[function <span class="apidocSignatureSpan">less.contexts.</span>Eval (options, frames)](#apidoc.element.less.contexts.Eval.Eval)
- description and source-code
```javascript
Eval = function (options, frames) {
    copyFromOriginal(options, this, evalCopyProperties);

    if (typeof this.paths === "string") { this.paths = [this.paths]; }

    this.frames = frames || [];
    this.importantScope = this.importantScope || [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.contexts.Eval.prototype"></a>[module less.contexts.Eval.prototype](#apidoc.module.less.contexts.Eval.prototype)

#### <a name="apidoc.element.less.contexts.Eval.prototype.inParenthesis"></a>[function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>inParenthesis ()](#apidoc.element.less.contexts.Eval.prototype.inParenthesis)
- description and source-code
```javascript
inParenthesis = function () {
    if (!this.parensStack) {
        this.parensStack = [];
    }
    this.parensStack.push(true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Eval.prototype.isMathOn"></a>[function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>isMathOn ()](#apidoc.element.less.contexts.Eval.prototype.isMathOn)
- description and source-code
```javascript
isMathOn = function () {
    return this.strictMath ? (this.parensStack && this.parensStack.length) : true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Eval.prototype.isPathRelative"></a>[function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>isPathRelative (path)](#apidoc.element.less.contexts.Eval.prototype.isPathRelative)
- description and source-code
```javascript
isPathRelative = function (path) {
    return !/^(?:[a-z-]+:|\/|#)/i.test(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Eval.prototype.normalizePath"></a>[function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>normalizePath ( path )](#apidoc.element.less.contexts.Eval.prototype.normalizePath)
- description and source-code
```javascript
normalizePath = function ( path ) {
    var
      segments = path.split("/").reverse(),
      segment;

    path = [];
    while (segments.length !== 0 ) {
        segment = segments.pop();
        switch( segment ) {
            case ".":
                break;
            case "..":
                if ((path.length === 0) || (path[path.length - 1] === "..")) {
                    path.push( segment );
                } else {
                    path.pop();
                }
                break;
            default:
                path.push( segment );
                break;
        }
    }

    return path.join("/");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.contexts.Eval.prototype.outOfParenthesis"></a>[function <span class="apidocSignatureSpan">less.contexts.Eval.prototype.</span>outOfParenthesis ()](#apidoc.element.less.contexts.Eval.prototype.outOfParenthesis)
- description and source-code
```javascript
outOfParenthesis = function () {
    this.parensStack.pop();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.environment"></a>[module less.environment](#apidoc.module.less.environment)

#### <a name="apidoc.element.less.environment.charsetLookup"></a>[function <span class="apidocSignatureSpan">less.environment.</span>charsetLookup ()](#apidoc.element.less.environment.charsetLookup)
- description and source-code
```javascript
charsetLookup = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.environment.encodeBase64"></a>[function <span class="apidocSignatureSpan">less.environment.</span>encodeBase64 ()](#apidoc.element.less.environment.encodeBase64)
- description and source-code
```javascript
encodeBase64 = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.environment.getSourceMapGenerator"></a>[function <span class="apidocSignatureSpan">less.environment.</span>getSourceMapGenerator ()](#apidoc.element.less.environment.getSourceMapGenerator)
- description and source-code
```javascript
getSourceMapGenerator = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.environment.mimeLookup"></a>[function <span class="apidocSignatureSpan">less.environment.</span>mimeLookup ()](#apidoc.element.less.environment.mimeLookup)
- description and source-code
```javascript
mimeLookup = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs"></a>[module less.fs](#apidoc.module.less.fs)

#### <a name="apidoc.element.less.fs.FileReadStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>FileReadStream (path, options)](#apidoc.element.less.fs.FileReadStream)
- description and source-code
```javascript
function ReadStream(path, options) {
  if (this instanceof ReadStream)
    return fs$ReadStream.apply(this, arguments), this
  else
    return ReadStream.apply(Object.create(ReadStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.FileWriteStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>FileWriteStream (path, options)](#apidoc.element.less.fs.FileWriteStream)
- description and source-code
```javascript
function WriteStream(path, options) {
  if (this instanceof WriteStream)
    return fs$WriteStream.apply(this, arguments), this
  else
    return WriteStream.apply(Object.create(WriteStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.ReadStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>ReadStream (path, options)](#apidoc.element.less.fs.ReadStream)
- description and source-code
```javascript
function ReadStream(path, options) {
  if (this instanceof ReadStream)
    return fs$ReadStream.apply(this, arguments), this
  else
    return ReadStream.apply(Object.create(ReadStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats"></a>[function <span class="apidocSignatureSpan">less.fs.</span>Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats)
- description and source-code
```javascript
function Stats( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec) {
  this.dev = dev;
  this.mode = mode;
  this.nlink = nlink;
  this.uid = uid;
  this.gid = gid;
  this.rdev = rdev;
  this.blksize = blksize;
  this.ino = ino;
  this.size = size;
  this.blocks = blocks;
  this.atime = new Date(atim_msec);
  this.mtime = new Date(mtim_msec);
  this.ctime = new Date(ctim_msec);
  this.birthtime = new Date(birthtim_msec);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.WriteStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>WriteStream (path, options)](#apidoc.element.less.fs.WriteStream)
- description and source-code
```javascript
function WriteStream(path, options) {
  if (this instanceof WriteStream)
    return fs$WriteStream.apply(this, arguments), this
  else
    return WriteStream.apply(Object.create(WriteStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs._toUnixTimestamp"></a>[function <span class="apidocSignatureSpan">less.fs.</span>_toUnixTimestamp (time)](#apidoc.element.less.fs._toUnixTimestamp)
- description and source-code
```javascript
function toUnixTimestamp(time) {
  if (typeof time === 'string' && +time == time) {
    return +time;
  }
  if (typeof time === 'number') {
    if (!Number.isFinite(time) || time < 0) {
      return Date.now() / 1000;
    }
    return time;
  }
  if (util.isDate(time)) {
    // convert to 123.456 UNIX timestamp
    return time.getTime() / 1000;
  }
  throw new Error('Cannot parse time: ' + time);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.access"></a>[function <span class="apidocSignatureSpan">less.fs.</span>access (path, mode, callback)](#apidoc.element.less.fs.access)
- description and source-code
```javascript
access = function (path, mode, callback) {
  if (typeof mode === 'function') {
    callback = mode;
    mode = fs.F_OK;
  } else if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  if (!nullCheck(path, callback))
    return;

  mode = mode | 0;
  var req = new FSReqWrap();
  req.oncomplete = makeCallback(callback);
  binding.access(pathModule._makeLong(path), mode, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.accessSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>accessSync (path, mode)](#apidoc.element.less.fs.accessSync)
- description and source-code
```javascript
accessSync = function (path, mode) {
  nullCheck(path);

  if (mode === undefined)
    mode = fs.F_OK;
  else
    mode = mode | 0;

  binding.access(pathModule._makeLong(path), mode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.appendFile"></a>[function <span class="apidocSignatureSpan">less.fs.</span>appendFile (path, data, options, cb)](#apidoc.element.less.fs.appendFile)
- description and source-code
```javascript
function appendFile(path, data, options, cb) {
  if (typeof options === 'function')
    cb = options, options = null

  return go$appendFile(path, data, options, cb)

  function go$appendFile (path, data, options, cb) {
    return fs$appendFile(path, data, options, function (err) {
      if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
        enqueue([go$appendFile, [path, data, options, cb]])
      else {
        if (typeof cb === 'function')
          cb.apply(this, arguments)
        retry()
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.appendFileSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>appendFileSync (path, data, options)](#apidoc.element.less.fs.appendFileSync)
- description and source-code
```javascript
appendFileSync = function (path, data, options) {
  if (!options) {
    options = { encoding: 'utf8', mode: 0o666, flag: 'a' };
  } else if (typeof options === 'string') {
    options = { encoding: options, mode: 0o666, flag: 'a' };
  } else if (typeof options !== 'object') {
    throwOptionsError(options);
  }

  if (!options.flag)
    options = util._extend({ flag: 'a' }, options);

  // force append behavior when using a supplied file descriptor
  if (isFd(path))
    options.flag = 'a';

  fs.writeFileSync(path, data, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.chmod"></a>[function <span class="apidocSignatureSpan">less.fs.</span>chmod (target, mode, cb)](#apidoc.element.less.fs.chmod)
- description and source-code
```javascript
chmod = function (target, mode, cb) {
  return orig.call(fs, target, mode, function (er) {
    if (chownErOk(er)) er = null
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.chmodSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>chmodSync (target, mode)](#apidoc.element.less.fs.chmodSync)
- description and source-code
```javascript
chmodSync = function (target, mode) {
  try {
    return orig.call(fs, target, mode)
  } catch (er) {
    if (!chownErOk(er)) throw er
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.chown"></a>[function <span class="apidocSignatureSpan">less.fs.</span>chown (target, uid, gid, cb)](#apidoc.element.less.fs.chown)
- description and source-code
```javascript
chown = function (target, uid, gid, cb) {
  return orig.call(fs, target, uid, gid, function (er) {
    if (chownErOk(er)) er = null
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.chownSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>chownSync (target, uid, gid)](#apidoc.element.less.fs.chownSync)
- description and source-code
```javascript
chownSync = function (target, uid, gid) {
  try {
    return orig.call(fs, target, uid, gid)
  } catch (er) {
    if (!chownErOk(er)) throw er
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.close"></a>[function <span class="apidocSignatureSpan">less.fs.</span>close (fd, cb)](#apidoc.element.less.fs.close)
- description and source-code
```javascript
close = function (fd, cb) {
  return fs$close.call(fs, fd, function (err) {
    if (!err)
      retry()

    if (typeof cb === 'function')
      cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.closeSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>closeSync (fd)](#apidoc.element.less.fs.closeSync)
- description and source-code
```javascript
closeSync = function (fd) {
  // Note that graceful-fs also retries when fs.closeSync() fails.
  // Looks like a bug to me, although it's probably a harmless one.
  var rval = fs$closeSync.apply(fs, arguments)
  retry()
  return rval
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.createReadStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>createReadStream (path, options)](#apidoc.element.less.fs.createReadStream)
- description and source-code
```javascript
function createReadStream(path, options) {
  return new ReadStream(path, options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.createWriteStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>createWriteStream (path, options)](#apidoc.element.less.fs.createWriteStream)
- description and source-code
```javascript
function createWriteStream(path, options) {
  return new WriteStream(path, options)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.exists"></a>[function <span class="apidocSignatureSpan">less.fs.</span>exists (path, callback)](#apidoc.element.less.fs.exists)
- description and source-code
```javascript
exists = function (path, callback) {
  if (!nullCheck(path, cb)) return;
  var req = new FSReqWrap();
  req.oncomplete = cb;
  binding.stat(pathModule._makeLong(path), req);
  function cb(err, stats) {
    if (callback) callback(err ? false : true);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.existsSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>existsSync (path)](#apidoc.element.less.fs.existsSync)
- description and source-code
```javascript
existsSync = function (path) {
  try {
    nullCheck(path);
    binding.stat(pathModule._makeLong(path), statValues);
    return true;
  } catch (e) {
    return false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fchmod"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fchmod (target, mode, cb)](#apidoc.element.less.fs.fchmod)
- description and source-code
```javascript
fchmod = function (target, mode, cb) {
  return orig.call(fs, target, mode, function (er) {
    if (chownErOk(er)) er = null
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fchmodSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fchmodSync (target, mode)](#apidoc.element.less.fs.fchmodSync)
- description and source-code
```javascript
fchmodSync = function (target, mode) {
  try {
    return orig.call(fs, target, mode)
  } catch (er) {
    if (!chownErOk(er)) throw er
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fchown"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fchown (target, uid, gid, cb)](#apidoc.element.less.fs.fchown)
- description and source-code
```javascript
fchown = function (target, uid, gid, cb) {
  return orig.call(fs, target, uid, gid, function (er) {
    if (chownErOk(er)) er = null
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fchownSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fchownSync (target, uid, gid)](#apidoc.element.less.fs.fchownSync)
- description and source-code
```javascript
fchownSync = function (target, uid, gid) {
  try {
    return orig.call(fs, target, uid, gid)
  } catch (er) {
    if (!chownErOk(er)) throw er
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fdatasync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fdatasync (fd, callback)](#apidoc.element.less.fs.fdatasync)
- description and source-code
```javascript
fdatasync = function (fd, callback) {
  var req = new FSReqWrap();
  req.oncomplete = makeCallback(callback);
  binding.fdatasync(fd, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fdatasyncSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fdatasyncSync (fd)](#apidoc.element.less.fs.fdatasyncSync)
- description and source-code
```javascript
fdatasyncSync = function (fd) {
  return binding.fdatasync(fd);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fstat"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fstat (target, cb)](#apidoc.element.less.fs.fstat)
- description and source-code
```javascript
fstat = function (target, cb) {
  return orig.call(fs, target, function (er, stats) {
    if (!stats) return cb.apply(this, arguments)
    if (stats.uid < 0) stats.uid += 0x100000000
    if (stats.gid < 0) stats.gid += 0x100000000
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fstatSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fstatSync (target)](#apidoc.element.less.fs.fstatSync)
- description and source-code
```javascript
fstatSync = function (target) {
  var stats = orig.call(fs, target)
  if (stats.uid < 0) stats.uid += 0x100000000
  if (stats.gid < 0) stats.gid += 0x100000000
  return stats;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fsync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fsync (fd, callback)](#apidoc.element.less.fs.fsync)
- description and source-code
```javascript
fsync = function (fd, callback) {
  var req = new FSReqWrap();
  req.oncomplete = makeCallback(callback);
  binding.fsync(fd, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.fsyncSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>fsyncSync (fd)](#apidoc.element.less.fs.fsyncSync)
- description and source-code
```javascript
fsyncSync = function (fd) {
  return binding.fsync(fd);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.ftruncate"></a>[function <span class="apidocSignatureSpan">less.fs.</span>ftruncate (fd, len, callback)](#apidoc.element.less.fs.ftruncate)
- description and source-code
```javascript
ftruncate = function (fd, len, callback) {
  if (typeof len === 'function') {
    callback = len;
    len = 0;
  } else if (len === undefined) {
    len = 0;
  }
  var req = new FSReqWrap();
  req.oncomplete = makeCallback(callback);
  binding.ftruncate(fd, len, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.ftruncateSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>ftruncateSync (fd, len)](#apidoc.element.less.fs.ftruncateSync)
- description and source-code
```javascript
ftruncateSync = function (fd, len) {
  if (len === undefined) {
    len = 0;
  }
  return binding.ftruncate(fd, len);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.futimes"></a>[function <span class="apidocSignatureSpan">less.fs.</span>futimes (fd, atime, mtime, callback)](#apidoc.element.less.fs.futimes)
- description and source-code
```javascript
futimes = function (fd, atime, mtime, callback) {
  atime = toUnixTimestamp(atime);
  mtime = toUnixTimestamp(mtime);
  var req = new FSReqWrap();
  req.oncomplete = makeCallback(callback);
  binding.futimes(fd, atime, mtime, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.futimesSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>futimesSync (fd, atime, mtime)](#apidoc.element.less.fs.futimesSync)
- description and source-code
```javascript
futimesSync = function (fd, atime, mtime) {
  atime = toUnixTimestamp(atime);
  mtime = toUnixTimestamp(mtime);
  binding.futimes(fd, atime, mtime);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.gracefulify"></a>[function <span class="apidocSignatureSpan">less.fs.</span>gracefulify (fs)](#apidoc.element.less.fs.gracefulify)
- description and source-code
```javascript
function patch(fs) {
  // Everything that references the open() function needs to be in here
  polyfills(fs)
  fs.gracefulify = patch
  fs.FileReadStream = ReadStream;  // Legacy name.
  fs.FileWriteStream = WriteStream;  // Legacy name.
  fs.createReadStream = createReadStream
  fs.createWriteStream = createWriteStream
  var fs$readFile = fs.readFile
  fs.readFile = readFile
  function readFile (path, options, cb) {
    if (typeof options === 'function')
      cb = options, options = null

    return go$readFile(path, options, cb)

    function go$readFile (path, options, cb) {
      return fs$readFile(path, options, function (err) {
        if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
          enqueue([go$readFile, [path, options, cb]])
        else {
          if (typeof cb === 'function')
            cb.apply(this, arguments)
          retry()
        }
      })
    }
  }

  var fs$writeFile = fs.writeFile
  fs.writeFile = writeFile
  function writeFile (path, data, options, cb) {
    if (typeof options === 'function')
      cb = options, options = null

    return go$writeFile(path, data, options, cb)

    function go$writeFile (path, data, options, cb) {
      return fs$writeFile(path, data, options, function (err) {
        if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
          enqueue([go$writeFile, [path, data, options, cb]])
        else {
          if (typeof cb === 'function')
            cb.apply(this, arguments)
          retry()
        }
      })
    }
  }

  var fs$appendFile = fs.appendFile
  if (fs$appendFile)
    fs.appendFile = appendFile
  function appendFile (path, data, options, cb) {
    if (typeof options === 'function')
      cb = options, options = null

    return go$appendFile(path, data, options, cb)

    function go$appendFile (path, data, options, cb) {
      return fs$appendFile(path, data, options, function (err) {
        if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
          enqueue([go$appendFile, [path, data, options, cb]])
        else {
          if (typeof cb === 'function')
            cb.apply(this, arguments)
          retry()
        }
      })
    }
  }

  var fs$readdir = fs.readdir
  fs.readdir = readdir
  function readdir (path, options, cb) {
    var args = [path]
    if (typeof options !== 'function') {
      args.push(options)
    } else {
      cb = options
    }
    args.push(go$readdir$cb)

    return go$readdir(args)

    function go$readdir$cb (err, files) {
      if (files && files.sort)
        files.sort()

      if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
        enqueue([go$readdir, [args]])
      else {
        if (typeof cb === 'function')
          cb.apply(this, arguments)
        retry()
      }
    }
  }

  function go$readdir (args) {
    return fs$readdir.apply(fs, args)
  }

  if (process.version.substr(0, 4) === 'v0.8') {
    var legStreams = legacy(fs)
    ReadStream = legStreams.ReadStream
    WriteStream = legStreams.WriteStream
  }

  var fs$ReadStream = fs.ReadStream
  ReadStream.prototype = Object.create(fs$ReadStream.prototype)
  ReadStream.prototype.open = ReadStream$open

  var fs$WriteStream = fs.WriteStream
  WriteStream.prototype = Object.create(fs$WriteStream.prototype)
  WriteStream.prototype.open = WriteStream$open

  fs.ReadStream = ReadStream
  fs.WriteStream = WriteStream

  function ReadStream (path, options) {
    if (this instanceof ReadStream)
      return fs$ReadStream.apply(this, arguments), this
    else
      return ReadStream.apply(Object.create(ReadStream.prototype), arguments)
  }

  function ReadStream$open () {
    var that = this
    open(that.path, that.flags, that.mode, function (err, fd) {
      if (err) {
        if (that.autoClose)
          that.destroy()

        that.emit('error', err)
      } else {
        that.fd = fd
        that.emit('open', fd)
        that.read()
      }
    })
  }

  function WriteStream (path, options) {
    if (this instanceof WriteStream)
      return fs$WriteStream.apply(this, arguments), this
    else
      return W ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lchmod"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lchmod (path, mode, cb)](#apidoc.element.less.fs.lchmod)
- description and source-code
```javascript
lchmod = function (path, mode, cb) {
  if (cb) process.nextTick(cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lchmodSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lchmodSync ()](#apidoc.element.less.fs.lchmodSync)
- description and source-code
```javascript
lchmodSync = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lchown"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lchown (path, uid, gid, cb)](#apidoc.element.less.fs.lchown)
- description and source-code
```javascript
lchown = function (path, uid, gid, cb) {
  if (cb) process.nextTick(cb)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lchownSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lchownSync ()](#apidoc.element.less.fs.lchownSync)
- description and source-code
```javascript
lchownSync = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.link"></a>[function <span class="apidocSignatureSpan">less.fs.</span>link (existingPath, newPath, callback)](#apidoc.element.less.fs.link)
- description and source-code
```javascript
link = function (existingPath, newPath, callback) {
  callback = makeCallback(callback);
  if (!nullCheck(existingPath, callback)) return;
  if (!nullCheck(newPath, callback)) return;

  var req = new FSReqWrap();
  req.oncomplete = callback;

  binding.link(pathModule._makeLong(existingPath),
               pathModule._makeLong(newPath),
               req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.linkSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>linkSync (existingPath, newPath)](#apidoc.element.less.fs.linkSync)
- description and source-code
```javascript
linkSync = function (existingPath, newPath) {
  nullCheck(existingPath);
  nullCheck(newPath);
  return binding.link(pathModule._makeLong(existingPath),
                      pathModule._makeLong(newPath));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lstat"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lstat (target, cb)](#apidoc.element.less.fs.lstat)
- description and source-code
```javascript
lstat = function (target, cb) {
  return orig.call(fs, target, function (er, stats) {
    if (!stats) return cb.apply(this, arguments)
    if (stats.uid < 0) stats.uid += 0x100000000
    if (stats.gid < 0) stats.gid += 0x100000000
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lstatSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lstatSync (target)](#apidoc.element.less.fs.lstatSync)
- description and source-code
```javascript
lstatSync = function (target) {
  var stats = orig.call(fs, target)
  if (stats.uid < 0) stats.uid += 0x100000000
  if (stats.gid < 0) stats.gid += 0x100000000
  return stats;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lutimes"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lutimes (_a, _b, _c, cb)](#apidoc.element.less.fs.lutimes)
- description and source-code
```javascript
lutimes = function (_a, _b, _c, cb) { if (cb) process.nextTick(cb) }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.lutimesSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>lutimesSync ()](#apidoc.element.less.fs.lutimesSync)
- description and source-code
```javascript
lutimesSync = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.mkdir"></a>[function <span class="apidocSignatureSpan">less.fs.</span>mkdir (path, mode, callback)](#apidoc.element.less.fs.mkdir)
- description and source-code
```javascript
mkdir = function (path, mode, callback) {
  if (typeof mode === 'function') callback = mode;
  callback = makeCallback(callback);
  if (!nullCheck(path, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.mkdir(pathModule._makeLong(path),
                modeNum(mode, 0o777),
                req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.mkdirSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>mkdirSync (path, mode)](#apidoc.element.less.fs.mkdirSync)
- description and source-code
```javascript
mkdirSync = function (path, mode) {
  nullCheck(path);
  return binding.mkdir(pathModule._makeLong(path),
                       modeNum(mode, 0o777));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.mkdtemp"></a>[function <span class="apidocSignatureSpan">less.fs.</span>mkdtemp (prefix, options, callback)](#apidoc.element.less.fs.mkdtemp)
- description and source-code
```javascript
mkdtemp = function (prefix, options, callback) {
  if (!prefix || typeof prefix !== 'string')
    throw new TypeError('filename prefix is required');

  options = options || {};
  if (typeof options === 'function') {
    callback = options;
    options = {};
  } else if (typeof options === 'string') {
    options = {encoding: options};
  }
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');

  callback = makeCallback(callback);
  if (!nullCheck(prefix, callback)) {
    return;
  }

  var req = new FSReqWrap();
  req.oncomplete = callback;

  binding.mkdtemp(prefix + 'XXXXXX', options.encoding, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.mkdtempSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>mkdtempSync (prefix, options)](#apidoc.element.less.fs.mkdtempSync)
- description and source-code
```javascript
mkdtempSync = function (prefix, options) {
  if (!prefix || typeof prefix !== 'string')
    throw new TypeError('filename prefix is required');

  options = options || {};
  if (typeof options === 'string')
    options = {encoding: options};
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');
  nullCheck(prefix);

  return binding.mkdtemp(prefix + 'XXXXXX', options.encoding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.open"></a>[function <span class="apidocSignatureSpan">less.fs.</span>open (path, flags, mode, cb)](#apidoc.element.less.fs.open)
- description and source-code
```javascript
function open(path, flags, mode, cb) {
  if (typeof mode === 'function')
    cb = mode, mode = null

  return go$open(path, flags, mode, cb)

  function go$open (path, flags, mode, cb) {
    return fs$open(path, flags, mode, function (err, fd) {
      if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
        enqueue([go$open, [path, flags, mode, cb]])
      else {
        if (typeof cb === 'function')
          cb.apply(this, arguments)
        retry()
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.openSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>openSync (path, flags, mode)](#apidoc.element.less.fs.openSync)
- description and source-code
```javascript
openSync = function (path, flags, mode) {
  mode = modeNum(mode, 0o666);
  nullCheck(path);
  return binding.open(pathModule._makeLong(path), stringToFlags(flags), mode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.read"></a>[function <span class="apidocSignatureSpan">less.fs.</span>read (fd, buffer, offset, length, position, callback_)](#apidoc.element.less.fs.read)
- description and source-code
```javascript
read = function (fd, buffer, offset, length, position, callback_) {
  var callback
  if (callback_ && typeof callback_ === 'function') {
    var eagCounter = 0
    callback = function (er, _, __) {
      if (er && er.code === 'EAGAIN' && eagCounter < 10) {
        eagCounter ++
        return fs$read.call(fs, fd, buffer, offset, length, position, callback)
      }
      callback_.apply(this, arguments)
    }
  }
  return fs$read.call(fs, fd, buffer, offset, length, position, callback)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readFile"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readFile (path, options, cb)](#apidoc.element.less.fs.readFile)
- description and source-code
```javascript
function readFile(path, options, cb) {
  if (typeof options === 'function')
    cb = options, options = null

  return go$readFile(path, options, cb)

  function go$readFile (path, options, cb) {
    return fs$readFile(path, options, function (err) {
      if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
        enqueue([go$readFile, [path, options, cb]])
      else {
        if (typeof cb === 'function')
          cb.apply(this, arguments)
        retry()
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readFileSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readFileSync (path, options)](#apidoc.element.less.fs.readFileSync)
- description and source-code
```javascript
readFileSync = function (path, options) {
  if (!options) {
    options = { encoding: null, flag: 'r' };
  } else if (typeof options === 'string') {
    options = { encoding: options, flag: 'r' };
  } else if (typeof options !== 'object') {
    throwOptionsError(options);
  }

  var encoding = options.encoding;
  assertEncoding(encoding);

  var flag = options.flag || 'r';
  var isUserFd = isFd(path); // file descriptor ownership
  var fd = isUserFd ? path : fs.openSync(path, flag, 0o666);

  var st = tryStatSync(fd, isUserFd);
  var size = st.isFile() ? st.size : 0;
  var pos = 0;
  var buffer; // single buffer with file data
  var buffers; // list for when size is unknown

  if (size === 0) {
    buffers = [];
  } else {
    buffer = tryCreateBuffer(size, fd, isUserFd);
  }

  var bytesRead;

  if (size !== 0) {
    do {
      bytesRead = tryReadSync(fd, isUserFd, buffer, pos, size - pos);
      pos += bytesRead;
    } while (bytesRead !== 0 && pos < size);
  } else {
    do {
      // the kernel lies about many files.
      // Go ahead and try to read some bytes.
      buffer = Buffer.allocUnsafe(8192);
      bytesRead = tryReadSync(fd, isUserFd, buffer, 0, 8192);
      if (bytesRead !== 0) {
        buffers.push(buffer.slice(0, bytesRead));
      }
      pos += bytesRead;
    } while (bytesRead !== 0);
  }

  if (!isUserFd)
    fs.closeSync(fd);

  if (size === 0) {
    // data was collected into the buffers list.
    buffer = Buffer.concat(buffers, pos);
  } else if (pos < size) {
    buffer = buffer.slice(0, pos);
  }

  if (encoding) buffer = buffer.toString(encoding);
  return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readSync (fd, buffer, offset, length, position)](#apidoc.element.less.fs.readSync)
- description and source-code
```javascript
readSync = function (fd, buffer, offset, length, position) {
  var eagCounter = 0
  while (true) {
    try {
      return fs$readSync.call(fs, fd, buffer, offset, length, position)
    } catch (er) {
      if (er.code === 'EAGAIN' && eagCounter < 10) {
        eagCounter ++
        continue
      }
      throw er
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readdir"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readdir (path, options, cb)](#apidoc.element.less.fs.readdir)
- description and source-code
```javascript
function readdir(path, options, cb) {
  var args = [path]
  if (typeof options !== 'function') {
    args.push(options)
  } else {
    cb = options
  }
  args.push(go$readdir$cb)

  return go$readdir(args)

  function go$readdir$cb (err, files) {
    if (files && files.sort)
      files.sort()

    if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
      enqueue([go$readdir, [args]])
    else {
      if (typeof cb === 'function')
        cb.apply(this, arguments)
      retry()
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readdirSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readdirSync (path, options)](#apidoc.element.less.fs.readdirSync)
- description and source-code
```javascript
readdirSync = function (path, options) {
  options = options || {};
  if (typeof options === 'string')
    options = {encoding: options};
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');
  nullCheck(path);
  return binding.readdir(pathModule._makeLong(path), options.encoding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readlink"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readlink (path, options, callback)](#apidoc.element.less.fs.readlink)
- description and source-code
```javascript
readlink = function (path, options, callback) {
  options = options || {};
  if (typeof options === 'function') {
    callback = options;
    options = {};
  } else if (typeof options === 'string') {
    options = {encoding: options};
  }
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');
  callback = makeCallback(callback);
  if (!nullCheck(path, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.readlink(pathModule._makeLong(path), options.encoding, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.readlinkSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>readlinkSync (path, options)](#apidoc.element.less.fs.readlinkSync)
- description and source-code
```javascript
readlinkSync = function (path, options) {
  options = options || {};
  if (typeof options === 'string')
    options = {encoding: options};
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');
  nullCheck(path);
  return binding.readlink(pathModule._makeLong(path), options.encoding);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.realpath"></a>[function <span class="apidocSignatureSpan">less.fs.</span>realpath (p, options, callback)](#apidoc.element.less.fs.realpath)
- description and source-code
```javascript
function realpath(p, options, callback) {
  if (typeof callback !== 'function') {
    callback = maybeCallback(options);
    options = {};
  }

  if (!options) {
    options = {};
  } else if (typeof options === 'function') {
    options = {};
  } else if (typeof options === 'string') {
    options = {encoding: options};
  } else if (typeof options !== 'object') {
    throw new TypeError('"options" must be a string or an object');
  }
  if (!nullCheck(p, callback))
    return;

  p = p.toString('utf8');
  p = pathModule.resolve(p);

  const seenLinks = {};
  const knownHard = {};

  // current character position in p
  var pos;
  // the partial path so far, including a trailing slash if any
  var current;
  // the partial path without a trailing slash (except when pointing at a root)
  var base;
  // the partial path scanned in the previous round, with slash
  var previous;

  start();

  function start() {
    // Skip over roots
    var m = splitRootRe.exec(p);
    pos = m[0].length;
    current = m[0];
    base = m[0];
    previous = '';

    // On windows, check that the root exists. On unix there is no need.
    if (isWindows && !knownHard[base]) {
      fs.lstat(base, function(err) {
        if (err) return callback(err);
        knownHard[base] = true;
        LOOP();
      });
    } else {
      process.nextTick(LOOP);
    }
  }

  // walk down the path, swapping out linked pathparts for their real
  // values
  function LOOP() {
    // stop if scanned past end of path
    if (pos >= p.length) {
      return callback(null, encodeRealpathResult(p, options));
    }

    // find the next part
    nextPartRe.lastIndex = pos;
    var result = nextPartRe.exec(p);
    previous = current;
    current += result[0];
    base = previous + result[1];
    pos = nextPartRe.lastIndex;

    // continue if not a symlink
    if (knownHard[base]) {
      return process.nextTick(LOOP);
    }

    return fs.lstat(base, gotStat);
  }

  function gotStat(err, stat) {
    if (err) return callback(err);

    // if not a symlink, skip to the next path part
    if (!stat.isSymbolicLink()) {
      knownHard[base] = true;
      return process.nextTick(LOOP);
    }

    // stat & read the link if not read before
    // call gotTarget as soon as the link target is known
    // dev/ino always return 0 on windows, so skip the check.
    let id;
    if (!isWindows) {
      id = '${stat.dev.toString(32)}:${stat.ino.toString(32)}';
      if (seenLinks.hasOwnProperty(id)) {
        return gotTarget(null, seenLinks[id], base);
      }
    }
    fs.stat(base, function(err) {
      if (err) return callback(err);

      fs.readlink(base, function(err, target) {
        if (!isWindows) seenLinks[id] = target;
        gotTarget(err, target);
      });
    });
  }

  function gotTarget(err, target, base) {
    if (err) return callback(err);

    var resolvedLink = pathModule.resolve(previous, target);
    gotResolvedLink(resolvedLink);
  }

  function gotResolvedLink(resolvedLink) {
    // resolve the link, then start over
    p = pathModule.resolve(resolvedLink, p.slice(pos));
    start();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.realpathSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>realpathSync (p, options)](#apidoc.element.less.fs.realpathSync)
- description and source-code
```javascript
function realpathSync(p, options) {
  if (!options)
    options = {};
  else if (typeof options === 'string')
    options = {encoding: options};
  else if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');
  nullCheck(p);

  p = p.toString('utf8');
  p = pathModule.resolve(p);

  const seenLinks = {};
  const knownHard = {};
  const cache = options[realpathCacheKey];
  const original = p;

  const maybeCachedResult = cache && cache.get(p);
  if (maybeCachedResult) {
    return maybeCachedResult;
  }

  // current character position in p
  var pos;
  // the partial path so far, including a trailing slash if any
  var current;
  // the partial path without a trailing slash (except when pointing at a root)
  var base;
  // the partial path scanned in the previous round, with slash
  var previous;

  start();

  function start() {
    // Skip over roots
    var m = splitRootRe.exec(p);
    pos = m[0].length;
    current = m[0];
    base = m[0];
    previous = '';

    // On windows, check that the root exists. On unix there is no need.
    if (isWindows && !knownHard[base]) {
      fs.lstatSync(base);
      knownHard[base] = true;
    }
  }

  // walk down the path, swapping out linked pathparts for their real
  // values
  // NB: p.length changes.
  while (pos < p.length) {
    // find the next part
    nextPartRe.lastIndex = pos;
    var result = nextPartRe.exec(p);
    previous = current;
    current += result[0];
    base = previous + result[1];
    pos = nextPartRe.lastIndex;

    // continue if not a symlink
    if (knownHard[base] || (cache && cache.get(base) === base)) {
      continue;
    }

    var resolvedLink;
    const maybeCachedResolved = cache && cache.get(base);
    if (maybeCachedResolved) {
      resolvedLink = maybeCachedResolved;
    } else {
      var stat = fs.lstatSync(base);
      if (!stat.isSymbolicLink()) {
        knownHard[base] = true;
        if (cache) cache.set(base, base);
        continue;
      }

      // read the link if it wasn't read before
      // dev/ino always return 0 on windows, so skip the check.
      let linkTarget = null;
      let id;
      if (!isWindows) {
        id = '${stat.dev.toString(32)}:${stat.ino.toString(32)}';
        if (seenLinks.hasOwnProperty(id)) {
          linkTarget = seenLinks[id];
        }
      }
      if (linkTarget === null) {
        fs.statSync(base);
        linkTarget = fs.readlinkSync(base);
      }
      resolvedLink = pathModule.resolve(previous, linkTarget);

      if (cache) cache.set(base, resolvedLink);
      if (!isWindows) seenLinks[id] = linkTarget;
    }

    // resolve the link, then start over
    p = pathModule.resolve(resolvedLink, p.slice(pos));
    start();
  }

  if (cache) cache.set(original, p);
  return encodeRealpathResult(p, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.rename"></a>[function <span class="apidocSignatureSpan">less.fs.</span>rename (oldPath, newPath, callback)](#apidoc.element.less.fs.rename)
- description and source-code
```javascript
rename = function (oldPath, newPath, callback) {
  callback = makeCallback(callback);
  if (!nullCheck(oldPath, callback)) return;
  if (!nullCheck(newPath, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.rename(pathModule._makeLong(oldPath),
                 pathModule._makeLong(newPath),
                 req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.renameSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>renameSync (oldPath, newPath)](#apidoc.element.less.fs.renameSync)
- description and source-code
```javascript
renameSync = function (oldPath, newPath) {
  nullCheck(oldPath);
  nullCheck(newPath);
  return binding.rename(pathModule._makeLong(oldPath),
                        pathModule._makeLong(newPath));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.rmdir"></a>[function <span class="apidocSignatureSpan">less.fs.</span>rmdir (path, callback)](#apidoc.element.less.fs.rmdir)
- description and source-code
```javascript
rmdir = function (path, callback) {
  callback = maybeCallback(callback);
  if (!nullCheck(path, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.rmdir(pathModule._makeLong(path), req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.rmdirSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>rmdirSync (path)](#apidoc.element.less.fs.rmdirSync)
- description and source-code
```javascript
rmdirSync = function (path) {
  nullCheck(path);
  return binding.rmdir(pathModule._makeLong(path));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.stat"></a>[function <span class="apidocSignatureSpan">less.fs.</span>stat (target, cb)](#apidoc.element.less.fs.stat)
- description and source-code
```javascript
stat = function (target, cb) {
  return orig.call(fs, target, function (er, stats) {
    if (!stats) return cb.apply(this, arguments)
    if (stats.uid < 0) stats.uid += 0x100000000
    if (stats.gid < 0) stats.gid += 0x100000000
    if (cb) cb.apply(this, arguments)
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.statSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>statSync (target)](#apidoc.element.less.fs.statSync)
- description and source-code
```javascript
statSync = function (target) {
  var stats = orig.call(fs, target)
  if (stats.uid < 0) stats.uid += 0x100000000
  if (stats.gid < 0) stats.gid += 0x100000000
  return stats;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.symlink"></a>[function <span class="apidocSignatureSpan">less.fs.</span>symlink (target, path, type_, callback_)](#apidoc.element.less.fs.symlink)
- description and source-code
```javascript
symlink = function (target, path, type_, callback_) {
  var type = (typeof type_ === 'string' ? type_ : null);
  var callback = makeCallback(arguments[arguments.length - 1]);

  if (!nullCheck(target, callback)) return;
  if (!nullCheck(path, callback)) return;

  var req = new FSReqWrap();
  req.oncomplete = callback;

  binding.symlink(preprocessSymlinkDestination(target, type, path),
                  pathModule._makeLong(path),
                  type,
                  req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.symlinkSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>symlinkSync (target, path, type)](#apidoc.element.less.fs.symlinkSync)
- description and source-code
```javascript
symlinkSync = function (target, path, type) {
  type = (typeof type === 'string' ? type : null);

  nullCheck(target);
  nullCheck(path);

  return binding.symlink(preprocessSymlinkDestination(target, type, path),
                         pathModule._makeLong(path),
                         type);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.truncate"></a>[function <span class="apidocSignatureSpan">less.fs.</span>truncate (path, len, callback)](#apidoc.element.less.fs.truncate)
- description and source-code
```javascript
truncate = function (path, len, callback) {
  if (typeof path === 'number') {
    return fs.ftruncate(path, len, callback);
  }
  if (typeof len === 'function') {
    callback = len;
    len = 0;
  } else if (len === undefined) {
    len = 0;
  }

  callback = maybeCallback(callback);
  fs.open(path, 'r+', function(er, fd) {
    if (er) return callback(er);
    var req = new FSReqWrap();
    req.oncomplete = function oncomplete(er) {
      fs.close(fd, function(er2) {
        callback(er || er2);
      });
    };
    binding.ftruncate(fd, len, req);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.truncateSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>truncateSync (path, len)](#apidoc.element.less.fs.truncateSync)
- description and source-code
```javascript
truncateSync = function (path, len) {
  if (typeof path === 'number') {
    // legacy
    return fs.ftruncateSync(path, len);
  }
  if (len === undefined) {
    len = 0;
  }
  // allow error to be thrown, but still close fd.
  var fd = fs.openSync(path, 'r+');
  var ret;

  try {
    ret = fs.ftruncateSync(fd, len);
  } finally {
    fs.closeSync(fd);
  }
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.unlink"></a>[function <span class="apidocSignatureSpan">less.fs.</span>unlink (path, callback)](#apidoc.element.less.fs.unlink)
- description and source-code
```javascript
unlink = function (path, callback) {
  callback = makeCallback(callback);
  if (!nullCheck(path, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.unlink(pathModule._makeLong(path), req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.unlinkSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>unlinkSync (path)](#apidoc.element.less.fs.unlinkSync)
- description and source-code
```javascript
unlinkSync = function (path) {
  nullCheck(path);
  return binding.unlink(pathModule._makeLong(path));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.unwatchFile"></a>[function <span class="apidocSignatureSpan">less.fs.</span>unwatchFile (filename, listener)](#apidoc.element.less.fs.unwatchFile)
- description and source-code
```javascript
unwatchFile = function (filename, listener) {
  nullCheck(filename);
  filename = pathModule.resolve(filename);
  var stat = statWatchers.get(filename);

  if (stat === undefined) return;

  if (typeof listener === 'function') {
    stat.removeListener('change', listener);
  } else {
    stat.removeAllListeners('change');
  }

  if (stat.listenerCount('change') === 0) {
    stat.stop();
    statWatchers.delete(filename);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.utimes"></a>[function <span class="apidocSignatureSpan">less.fs.</span>utimes (path, atime, mtime, callback)](#apidoc.element.less.fs.utimes)
- description and source-code
```javascript
utimes = function (path, atime, mtime, callback) {
  callback = makeCallback(callback);
  if (!nullCheck(path, callback)) return;
  var req = new FSReqWrap();
  req.oncomplete = callback;
  binding.utimes(pathModule._makeLong(path),
                 toUnixTimestamp(atime),
                 toUnixTimestamp(mtime),
                 req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.utimesSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>utimesSync (path, atime, mtime)](#apidoc.element.less.fs.utimesSync)
- description and source-code
```javascript
utimesSync = function (path, atime, mtime) {
  nullCheck(path);
  atime = toUnixTimestamp(atime);
  mtime = toUnixTimestamp(mtime);
  binding.utimes(pathModule._makeLong(path), atime, mtime);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.watch"></a>[function <span class="apidocSignatureSpan">less.fs.</span>watch (filename, options, listener)](#apidoc.element.less.fs.watch)
- description and source-code
```javascript
watch = function (filename, options, listener) {
  nullCheck(filename);

  options = options || {};
  if (typeof options === 'function') {
    listener = options;
    options = {};
  } else if (typeof options === 'string') {
    options = {encoding: options};
  }
  if (typeof options !== 'object')
    throw new TypeError('"options" must be a string or an object');

  if (options.persistent === undefined) options.persistent = true;
  if (options.recursive === undefined) options.recursive = false;

  const watcher = new FSWatcher();
  watcher.start(filename,
                options.persistent,
                options.recursive,
                options.encoding);

  if (listener) {
    watcher.addListener('change', listener);
  }

  return watcher;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.watchFile"></a>[function <span class="apidocSignatureSpan">less.fs.</span>watchFile (filename, options, listener)](#apidoc.element.less.fs.watchFile)
- description and source-code
```javascript
watchFile = function (filename, options, listener) {
  nullCheck(filename);
  filename = pathModule.resolve(filename);
  var stat;

  var defaults = {
    // Poll interval in milliseconds. 5007 is what libev used to use. It's
    // a little on the slow side but let's stick with it for now to keep
    // behavioral changes to a minimum.
    interval: 5007,
    persistent: true
  };

  if (options !== null && typeof options === 'object') {
    options = util._extend(defaults, options);
  } else {
    listener = options;
    options = defaults;
  }

  if (typeof listener !== 'function') {
    throw new Error('"watchFile()" requires a listener function');
  }

  stat = statWatchers.get(filename);

  if (stat === undefined) {
    stat = new StatWatcher();
    stat.start(filename, options.persistent, options.interval);
    statWatchers.set(filename, stat);
  }

  stat.addListener('change', listener);
  return stat;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.write"></a>[function <span class="apidocSignatureSpan">less.fs.</span>write (fd, buffer, offset, length, position, callback)](#apidoc.element.less.fs.write)
- description and source-code
```javascript
write = function (fd, buffer, offset, length, position, callback) {
  function wrapper(err, written) {
    // Retain a reference to buffer so that it can't be GC'ed too soon.
    callback(err, written || 0, buffer);
  }

  var req = new FSReqWrap();
  req.oncomplete = wrapper;

  if (buffer instanceof Buffer) {
    // if no position is passed then assume null
    if (typeof position === 'function') {
      callback = position;
      position = null;
    }
    callback = maybeCallback(callback);
    return binding.writeBuffer(fd, buffer, offset, length, position, req);
  }

  if (typeof buffer !== 'string')
    buffer += '';
  if (typeof position !== 'function') {
    if (typeof offset === 'function') {
      position = offset;
      offset = null;
    } else {
      position = length;
    }
    length = 'utf8';
  }
  callback = maybeCallback(position);
  return binding.writeString(fd, buffer, offset, length, req);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.writeFile"></a>[function <span class="apidocSignatureSpan">less.fs.</span>writeFile (path, data, options, cb)](#apidoc.element.less.fs.writeFile)
- description and source-code
```javascript
function writeFile(path, data, options, cb) {
  if (typeof options === 'function')
    cb = options, options = null

  return go$writeFile(path, data, options, cb)

  function go$writeFile (path, data, options, cb) {
    return fs$writeFile(path, data, options, function (err) {
      if (err && (err.code === 'EMFILE' || err.code === 'ENFILE'))
        enqueue([go$writeFile, [path, data, options, cb]])
      else {
        if (typeof cb === 'function')
          cb.apply(this, arguments)
        retry()
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.writeFileSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>writeFileSync (path, data, options)](#apidoc.element.less.fs.writeFileSync)
- description and source-code
```javascript
writeFileSync = function (path, data, options) {
  if (!options) {
    options = { encoding: 'utf8', mode: 0o666, flag: 'w' };
  } else if (typeof options === 'string') {
    options = { encoding: options, mode: 0o666, flag: 'w' };
  } else if (typeof options !== 'object') {
    throwOptionsError(options);
  }

  assertEncoding(options.encoding);

  var flag = options.flag || 'w';
  var isUserFd = isFd(path); // file descriptor ownership
  var fd = isUserFd ? path : fs.openSync(path, flag, options.mode);

  if (!(data instanceof Buffer)) {
    data = Buffer.from('' + data, options.encoding || 'utf8');
  }
  var offset = 0;
  var length = data.length;
  var position = /a/.test(flag) ? null : 0;
  try {
    while (length > 0) {
      var written = fs.writeSync(fd, data, offset, length, position);
      offset += written;
      length -= written;
      if (position !== null) {
        position += written;
      }
    }
  } finally {
    if (!isUserFd) fs.closeSync(fd);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.writeSync"></a>[function <span class="apidocSignatureSpan">less.fs.</span>writeSync (fd, buffer, offset, length, position)](#apidoc.element.less.fs.writeSync)
- description and source-code
```javascript
writeSync = function (fd, buffer, offset, length, position) {
  if (buffer instanceof Buffer) {
    if (position === undefined)
      position = null;
    return binding.writeBuffer(fd, buffer, offset, length, position);
  }
  if (typeof buffer !== 'string')
    buffer += '';
  if (offset === undefined)
    offset = null;
  return binding.writeString(fd, buffer, offset, length, position);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.ReadStream"></a>[module less.fs.ReadStream](#apidoc.module.less.fs.ReadStream)

#### <a name="apidoc.element.less.fs.ReadStream.ReadStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>ReadStream (path, options)](#apidoc.element.less.fs.ReadStream.ReadStream)
- description and source-code
```javascript
function ReadStream(path, options) {
  if (this instanceof ReadStream)
    return fs$ReadStream.apply(this, arguments), this
  else
    return ReadStream.apply(Object.create(ReadStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.ReadStream.prototype"></a>[module less.fs.ReadStream.prototype](#apidoc.module.less.fs.ReadStream.prototype)

#### <a name="apidoc.element.less.fs.ReadStream.prototype.open"></a>[function <span class="apidocSignatureSpan">less.fs.ReadStream.prototype.</span>open ()](#apidoc.element.less.fs.ReadStream.prototype.open)
- description and source-code
```javascript
function ReadStream$open() {
  var that = this
  open(that.path, that.flags, that.mode, function (err, fd) {
    if (err) {
      if (that.autoClose)
        that.destroy()

      that.emit('error', err)
    } else {
      that.fd = fd
      that.emit('open', fd)
      that.read()
    }
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.Stats"></a>[module less.fs.Stats](#apidoc.module.less.fs.Stats)

#### <a name="apidoc.element.less.fs.Stats.Stats"></a>[function <span class="apidocSignatureSpan">less.fs.</span>Stats ( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec)](#apidoc.element.less.fs.Stats.Stats)
- description and source-code
```javascript
function Stats( dev, mode, nlink, uid, gid, rdev, blksize, ino, size, blocks, atim_msec, mtim_msec, ctim_msec, birthtim_msec) {
  this.dev = dev;
  this.mode = mode;
  this.nlink = nlink;
  this.uid = uid;
  this.gid = gid;
  this.rdev = rdev;
  this.blksize = blksize;
  this.ino = ino;
  this.size = size;
  this.blocks = blocks;
  this.atime = new Date(atim_msec);
  this.mtime = new Date(mtim_msec);
  this.ctime = new Date(ctim_msec);
  this.birthtime = new Date(birthtim_msec);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.Stats.prototype"></a>[module less.fs.Stats.prototype](#apidoc.module.less.fs.Stats.prototype)

#### <a name="apidoc.element.less.fs.Stats.prototype._checkModeProperty"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>_checkModeProperty (property)](#apidoc.element.less.fs.Stats.prototype._checkModeProperty)
- description and source-code
```javascript
_checkModeProperty = function (property) {
  return ((this.mode & constants.S_IFMT) === property);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isBlockDevice"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isBlockDevice ()](#apidoc.element.less.fs.Stats.prototype.isBlockDevice)
- description and source-code
```javascript
isBlockDevice = function () {
  return this._checkModeProperty(constants.S_IFBLK);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isCharacterDevice"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isCharacterDevice ()](#apidoc.element.less.fs.Stats.prototype.isCharacterDevice)
- description and source-code
```javascript
isCharacterDevice = function () {
  return this._checkModeProperty(constants.S_IFCHR);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isDirectory"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isDirectory ()](#apidoc.element.less.fs.Stats.prototype.isDirectory)
- description and source-code
```javascript
isDirectory = function () {
  return this._checkModeProperty(constants.S_IFDIR);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isFIFO"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isFIFO ()](#apidoc.element.less.fs.Stats.prototype.isFIFO)
- description and source-code
```javascript
isFIFO = function () {
  return this._checkModeProperty(constants.S_IFIFO);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isFile"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isFile ()](#apidoc.element.less.fs.Stats.prototype.isFile)
- description and source-code
```javascript
isFile = function () {
  return this._checkModeProperty(constants.S_IFREG);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isSocket"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isSocket ()](#apidoc.element.less.fs.Stats.prototype.isSocket)
- description and source-code
```javascript
isSocket = function () {
  return this._checkModeProperty(constants.S_IFSOCK);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.fs.Stats.prototype.isSymbolicLink"></a>[function <span class="apidocSignatureSpan">less.fs.Stats.prototype.</span>isSymbolicLink ()](#apidoc.element.less.fs.Stats.prototype.isSymbolicLink)
- description and source-code
```javascript
isSymbolicLink = function () {
  return this._checkModeProperty(constants.S_IFLNK);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.WriteStream"></a>[module less.fs.WriteStream](#apidoc.module.less.fs.WriteStream)

#### <a name="apidoc.element.less.fs.WriteStream.WriteStream"></a>[function <span class="apidocSignatureSpan">less.fs.</span>WriteStream (path, options)](#apidoc.element.less.fs.WriteStream.WriteStream)
- description and source-code
```javascript
function WriteStream(path, options) {
  if (this instanceof WriteStream)
    return fs$WriteStream.apply(this, arguments), this
  else
    return WriteStream.apply(Object.create(WriteStream.prototype), arguments)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.fs.WriteStream.prototype"></a>[module less.fs.WriteStream.prototype](#apidoc.module.less.fs.WriteStream.prototype)

#### <a name="apidoc.element.less.fs.WriteStream.prototype.open"></a>[function <span class="apidocSignatureSpan">less.fs.WriteStream.prototype.</span>open ()](#apidoc.element.less.fs.WriteStream.prototype.open)
- description and source-code
```javascript
function WriteStream$open() {
  var that = this
  open(that.path, that.flags, that.mode, function (err, fd) {
    if (err) {
      that.destroy()
      that.emit('error', err)
    } else {
      that.fd = fd
      that.emit('open', fd)
    }
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.functions"></a>[module less.functions](#apidoc.module.less.functions)

#### <a name="apidoc.element.less.functions.functionCaller"></a>[function <span class="apidocSignatureSpan">less.functions.</span>functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller)
- description and source-code
```javascript
functionCaller = function (name, context, index, currentFileInfo) {
    this.name = name.toLowerCase();
    this.index = index;
    this.context = context;
    this.currentFileInfo = currentFileInfo;

    this.func = context.frames[0].functionRegistry.get(this.name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.functions.functionCaller"></a>[module less.functions.functionCaller](#apidoc.module.less.functions.functionCaller)

#### <a name="apidoc.element.less.functions.functionCaller.functionCaller"></a>[function <span class="apidocSignatureSpan">less.functions.</span>functionCaller (name, context, index, currentFileInfo)](#apidoc.element.less.functions.functionCaller.functionCaller)
- description and source-code
```javascript
functionCaller = function (name, context, index, currentFileInfo) {
    this.name = name.toLowerCase();
    this.index = index;
    this.context = context;
    this.currentFileInfo = currentFileInfo;

    this.func = context.frames[0].functionRegistry.get(this.name);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.functions.functionCaller.prototype"></a>[module less.functions.functionCaller.prototype](#apidoc.module.less.functions.functionCaller.prototype)

#### <a name="apidoc.element.less.functions.functionCaller.prototype.call"></a>[function <span class="apidocSignatureSpan">less.functions.functionCaller.prototype.</span>call (args)](#apidoc.element.less.functions.functionCaller.prototype.call)
- description and source-code
```javascript
call = function (args) {

    // This code is terrible and should be replaced as per this issue...
    // https://github.com/less/less.js/issues/2477
    if (Array.isArray(args)) {
        args = args.filter(function (item) {
            if (item.type === "Comment") {
                return false;
            }
            return true;
        })
        .map(function(item) {
            if (item.type === "Expression") {
                var subNodes = item.value.filter(function (item) {
                    if (item.type === "Comment") {
                        return false;
                    }
                    return true;
                });
                if (subNodes.length === 1) {
                    return subNodes[0];
                } else {
                    return new Expression(subNodes);
                }
            }
            return item;
        });
    }

    return this.func.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.functions.functionCaller.prototype.isValid"></a>[function <span class="apidocSignatureSpan">less.functions.functionCaller.prototype.</span>isValid ()](#apidoc.element.less.functions.functionCaller.prototype.isValid)
- description and source-code
```javascript
isValid = function () {
    return Boolean(this.func);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.functions.functionRegistry"></a>[module less.functions.functionRegistry](#apidoc.module.less.functions.functionRegistry)

#### <a name="apidoc.element.less.functions.functionRegistry.add"></a>[function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>add (name, func)](#apidoc.element.less.functions.functionRegistry.add)
- description and source-code
```javascript
add = function (name, func) {
    // precautionary case conversion, as later querying of
    // the registry by function-caller uses lower case as well.
    name = name.toLowerCase();

    if (this._data.hasOwnProperty(name)) {
        //TODO warn
    }
    this._data[name] = func;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.functions.functionRegistry.addMultiple"></a>[function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>addMultiple (functions)](#apidoc.element.less.functions.functionRegistry.addMultiple)
- description and source-code
```javascript
addMultiple = function (functions) {
    Object.keys(functions).forEach(
        function(name) {
            this.add(name, functions[name]);
        }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.functions.functionRegistry.get"></a>[function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>get (name)](#apidoc.element.less.functions.functionRegistry.get)
- description and source-code
```javascript
get = function (name) {
    return this._data[name] || ( base && base.get( name ));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.functions.functionRegistry.inherit"></a>[function <span class="apidocSignatureSpan">less.functions.functionRegistry.</span>inherit ()](#apidoc.element.less.functions.functionRegistry.inherit)
- description and source-code
```javascript
inherit = function () {
    return makeRegistry( this );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.lesscHelper"></a>[module less.lesscHelper](#apidoc.module.less.lesscHelper)

#### <a name="apidoc.element.less.lesscHelper.printUsage"></a>[function <span class="apidocSignatureSpan">less.lesscHelper.</span>printUsage ()](#apidoc.element.less.lesscHelper.printUsage)
- description and source-code
```javascript
printUsage = function () {
    console.log("usage: lessc [option option=parameter ...] <source> [destination]");
    console.log("");
    console.log("If source is set to '-' (dash or hyphen-minus), input is read from stdin.");
    console.log("");
    console.log("options:");
    console.log("  -h, --help               Prints help (this message) and exit.");
    console.log("  --include-path=PATHS     Sets include paths. Separated by ':'. ';' also supported on windows.");
    console.log("  -M, --depends            Outputs a makefile import dependency list to stdout.");
    console.log("  --no-color               Disables colorized output.");
    console.log("  --no-ie-compat           Disables IE compatibility checks.");
    console.log("  --no-js                  Disables JavaScript in less files");
    console.log("  -l, --lint               Syntax check only (lint).");
    console.log("  -s, --silent             Suppresses output of error messages.");
    console.log("  --strict-imports         Forces evaluation of imports.");
    console.log("  --insecure               Allows imports from insecure https hosts.");
    console.log("  -v, --version            Prints version number and exit.");
    console.log("  --verbose                Be verbose.");
    console.log("  --source-map[=FILENAME]  Outputs a v3 sourcemap to the filename (or output filename.map).");
    console.log("  --source-map-rootpath=X  Adds this path onto the sourcemap filename and less file paths.");
    console.log("  --source-map-basepath=X  Sets sourcemap base path, defaults to current working directory.");
    console.log("  --source-map-less-inline Puts the less files into the map instead of referencing them.");
    console.log("  --source-map-map-inline  Puts the map (and any less files) as a base64 data uri into the output css file.");
    console.log("  --source-map-url=URL     Sets a custom URL to map file, for sourceMappingURL comment");
    console.log("                           in generated CSS file.");
    console.log("  -rp, --rootpath=URL      Sets rootpath for url rewriting in relative imports and urls");
    console.log("                           Works with or without the relative-urls option.");
    console.log("  -ru, --relative-urls     Re-writes relative urls to the base less file.");
    console.log("  -sm=on|off               Turns on or off strict math, where in strict mode, math.");
    console.log("  --strict-math=on|off     Requires brackets. This option may default to on and then");
    console.log("                           be removed in the future.");
    console.log("  -su=on|off               Allows mixed units, e.g. 1px+1em or 1px*1px which have units");
    console.log("  --strict-units=on|off    that cannot be represented.");
    console.log("  --global-var='VAR=VALUE' Defines a variable that can be referenced by the file.");
    console.log("  --modify-var='VAR=VALUE' Modifies a variable already declared in the file.");
    console.log("  --url-args='QUERYSTRING' Adds params into url tokens (e.g. 42, cb=42 or 'a=1&b=2')");
    console.log("  --plugin=PLUGIN=OPTIONS  Loads a plugin. You can also omit the --plugin= if the plugin begins");
    console.log("                           less-plugin. E.g. the clean css plugin is called less-plugin-clean-css");
    console.log("                           once installed (npm install less-plugin-clean-css), use either with");
    console.log("                           --plugin=less-plugin-clean-css or just --clean-css");
    console.log("                           specify options afterwards e.g. --plugin=less-plugin-clean-css=\"advanced\"");
    console.log("                           or --clean-css=\"advanced\"");
    console.log("");
    console.log("-------------------------- Deprecated ----------------");
    console.log("  --line-numbers=TYPE      Outputs filename and line numbers.");
    console.log("                           TYPE can be either 'comments', which will output");
    console.log("                           the debug info within comments, 'mediaquery'");
    cons ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.lesscHelper.stylize"></a>[function <span class="apidocSignatureSpan">less.lesscHelper.</span>stylize (str, style)](#apidoc.element.less.lesscHelper.stylize)
- description and source-code
```javascript
stylize = function (str, style) {
    var styles = {
        'reset'     : [0,   0],
        'bold'      : [1,  22],
        'inverse'   : [7,  27],
        'underline' : [4,  24],
        'yellow'    : [33, 39],
        'green'     : [32, 39],
        'red'       : [31, 39],
        'grey'      : [90, 39]
    };
    return '\x1b[' + styles[style][0] + 'm' + str +
           '\x1b[' + styles[style][1] + 'm';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.logger"></a>[module less.logger](#apidoc.module.less.logger)

#### <a name="apidoc.element.less.logger._fireEvent"></a>[function <span class="apidocSignatureSpan">less.logger.</span>_fireEvent (type, msg)](#apidoc.element.less.logger._fireEvent)
- description and source-code
```javascript
_fireEvent = function (type, msg) {
    for (var i = 0; i < this._listeners.length; i++) {
        var logFunction = this._listeners[i][type];
        if (logFunction) {
            logFunction(msg);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.addListener"></a>[function <span class="apidocSignatureSpan">less.logger.</span>addListener (listener)](#apidoc.element.less.logger.addListener)
- description and source-code
```javascript
addListener = function (listener) {
    this._listeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.debug"></a>[function <span class="apidocSignatureSpan">less.logger.</span>debug (msg)](#apidoc.element.less.logger.debug)
- description and source-code
```javascript
debug = function (msg) {
    this._fireEvent("debug", msg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.error"></a>[function <span class="apidocSignatureSpan">less.logger.</span>error (msg)](#apidoc.element.less.logger.error)
- description and source-code
```javascript
error = function (msg) {
    this._fireEvent("error", msg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.info"></a>[function <span class="apidocSignatureSpan">less.logger.</span>info (msg)](#apidoc.element.less.logger.info)
- description and source-code
```javascript
info = function (msg) {
    this._fireEvent("info", msg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.removeListener"></a>[function <span class="apidocSignatureSpan">less.logger.</span>removeListener (listener)](#apidoc.element.less.logger.removeListener)
- description and source-code
```javascript
removeListener = function (listener) {
    for (var i = 0; i < this._listeners.length; i++) {
        if (this._listeners[i] === listener) {
            this._listeners.splice(i, 1);
            return;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.logger.warn"></a>[function <span class="apidocSignatureSpan">less.logger.</span>warn (msg)](#apidoc.element.less.logger.warn)
- description and source-code
```javascript
warn = function (msg) {
    this._fireEvent("warn", msg);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree"></a>[module less.tree](#apidoc.module.less.tree)

#### <a name="apidoc.element.less.tree.Alpha"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Alpha (val)](#apidoc.element.less.tree.Alpha)
- description and source-code
```javascript
Alpha = function (val) {
    this.value = val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Anonymous"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous)
- description and source-code
```javascript
Anonymous = function (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo) {
    this.value = value;
    this.index = index;
    this.mapLines = mapLines;
    this.currentFileInfo = currentFileInfo;
    this.rulesetLike = (typeof rulesetLike === 'undefined') ? false : rulesetLike;
    this.allowRoot = true;
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Assignment"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Assignment (key, val)](#apidoc.element.less.tree.Assignment)
- description and source-code
```javascript
Assignment = function (key, val) {
    this.key = key;
    this.value = val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Attribute"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Attribute (key, op, value)](#apidoc.element.less.tree.Attribute)
- description and source-code
```javascript
Attribute = function (key, op, value) {
    this.key = key;
    this.op = op;
    this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Call"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call)
- description and source-code
```javascript
Call = function (name, args, index, currentFileInfo) {
    this.name = name;
    this.args = args;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color)
- description and source-code
```javascript
Color = function (rgb, a, originalForm) {
    //
    // The end goal here, is to parse the arguments
    // into an integer triplet, such as '128, 255, 0'
    //
    // This facilitates operations and conversions.
    //
    if (Array.isArray(rgb)) {
        this.rgb = rgb;
    } else if (rgb.length == 6) {
        this.rgb = rgb.match(/.{2}/g).map(function (c) {
            return parseInt(c, 16);
        });
    } else {
        this.rgb = rgb.split('').map(function (c) {
            return parseInt(c + c, 16);
        });
    }
    this.alpha = typeof a === 'number' ? a : 1;
    if (typeof originalForm !== 'undefined') {
        this.value = originalForm;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Combinator"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Combinator (value)](#apidoc.element.less.tree.Combinator)
- description and source-code
```javascript
Combinator = function (value) {
    if (value === ' ') {
        this.value = ' ';
        this.emptyOrWhitespace = true;
    } else {
        this.value = value ? value.trim() : "";
        this.emptyOrWhitespace = this.value === "";
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Comment"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment)
- description and source-code
```javascript
Comment = function (value, isLineComment, index, currentFileInfo) {
    this.value = value;
    this.isLineComment = isLineComment;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Condition"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition)
- description and source-code
```javascript
Condition = function (op, l, r, i, negate) {
    this.op = op.trim();
    this.lvalue = l;
    this.rvalue = r;
    this.index = i;
    this.negate = negate;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.DetachedRuleset"></a>[function <span class="apidocSignatureSpan">less.tree.</span>DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset)
- description and source-code
```javascript
DetachedRuleset = function (ruleset, frames) {
    this.ruleset = ruleset;
    this.frames = frames;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Dimension (value, unit)](#apidoc.element.less.tree.Dimension)
- description and source-code
```javascript
Dimension = function (value, unit) {
    this.value = parseFloat(value);
    this.unit = (unit && unit instanceof Unit) ? unit :
      new Unit(unit ? [unit] : undefined);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive)
- description and source-code
```javascript
Directive = function (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo) {
    var i;

    this.name  = name;
    this.value = value;
    if (rules) {
        if (Array.isArray(rules)) {
            this.rules = rules;
        } else {
            this.rules = [rules];
            this.rules[0].selectors = (new Selector([], null, null, this.index, currentFileInfo)).createEmptySelectors();
        }
        for (i = 0; i < this.rules.length; i++) {
            this.rules[i].allowImports = true;
        }
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.debugInfo = debugInfo;
    this.isRooted = isRooted || false;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element)
- description and source-code
```javascript
Element = function (combinator, value, index, currentFileInfo, info) {
    this.combinator = combinator instanceof Combinator ?
                      combinator : new Combinator(combinator);

    if (typeof value === 'string') {
        this.value = value.trim();
    } else if (value) {
        this.value = value;
    } else {
        this.value = "";
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.copyVisibilityInfo(info);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Expression"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Expression (value)](#apidoc.element.less.tree.Expression)
- description and source-code
```javascript
Expression = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Expression requires an array parameter");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Extend"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend)
- description and source-code
```javascript
function Extend(selector, option, index, currentFileInfo, visibilityInfo) {
    this.selector = selector;
    this.option = option;
    this.index = index;
    this.object_id = Extend.next_id++;
    this.parent_ids = [this.object_id];
    this.currentFileInfo = currentFileInfo || {};
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;

    switch(option) {
        case "all":
            this.allowBefore = true;
            this.allowAfter = true;
            break;
        default:
            this.allowBefore = false;
            this.allowAfter = false;
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import)
- description and source-code
```javascript
Import = function (path, features, options, index, currentFileInfo, visibilityInfo) {
    this.options = options;
    this.index = index;
    this.path = path;
    this.features = features;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;

    if (this.options.less !== undefined || this.options.inline) {
        this.css = !this.options.less || this.options.inline;
    } else {
        var pathValue = this.getPath();
        if (pathValue && /[#\.\&\?\/]css([\?;].*)?$/.test(pathValue)) {
            this.css = true;
        }
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.JavaScript"></a>[function <span class="apidocSignatureSpan">less.tree.</span>JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript)
- description and source-code
```javascript
JavaScript = function (string, escaped, index, currentFileInfo) {
    this.escaped = escaped;
    this.expression = string;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Keyword"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Keyword (value)](#apidoc.element.less.tree.Keyword)
- description and source-code
```javascript
Keyword = function (value) { this.value = value; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media)
- description and source-code
```javascript
Media = function (value, features, index, currentFileInfo, visibilityInfo) {
    this.index = index;
    this.currentFileInfo = currentFileInfo;

    var selectors = (new Selector([], null, null, this.index, this.currentFileInfo)).createEmptySelectors();

    this.features = new Value(features);
    this.rules = [new Ruleset(selectors, value)];
    this.rules[0].allowImports = true;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Negative"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Negative (node)](#apidoc.element.less.tree.Negative)
- description and source-code
```javascript
Negative = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Node ()](#apidoc.element.less.tree.Node)
- description and source-code
```javascript
Node = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Operation"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation)
- description and source-code
```javascript
Operation = function (op, operands, isSpaced) {
    this.op = op.trim();
    this.operands = operands;
    this.isSpaced = isSpaced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Paren"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Paren (node)](#apidoc.element.less.tree.Paren)
- description and source-code
```javascript
Paren = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Quoted"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted)
- description and source-code
```javascript
Quoted = function (str, content, escaped, index, currentFileInfo) {
    this.escaped = (escaped == null) ? true : escaped;
    this.value = content || '';
    this.quote = str.charAt(0);
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Rule"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule)
- description and source-code
```javascript
Rule = function (name, value, important, merge, index, currentFileInfo, inline, variable) {
    this.name = name;
    this.value = (value instanceof Node) ? value : new Value([value]); //value instanceof tree.Value || value instanceof tree.Ruleset
 ??
    this.important = important ? ' ' + important.trim() : '';
    this.merge = merge;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.inline = inline || false;
    this.variable = (variable !== undefined) ? variable
        : (name.charAt && (name.charAt(0) === '@'));
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset)
- description and source-code
```javascript
Ruleset = function (selectors, rules, strictImports, visibilityInfo) {
    this.selectors = selectors;
    this.rules = rules;
    this._lookups = {};
    this.strictImports = strictImports;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.RulesetCall"></a>[function <span class="apidocSignatureSpan">less.tree.</span>RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall)
- description and source-code
```javascript
RulesetCall = function (variable) {
    this.variable = variable;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector)
- description and source-code
```javascript
Selector = function (elements, extendList, condition, index, currentFileInfo, visibilityInfo) {
    this.elements = elements;
    this.extendList = extendList;
    this.condition = condition;
    this.currentFileInfo = currentFileInfo || {};
    if (!condition) {
        this.evaldCondition = true;
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.URL"></a>[function <span class="apidocSignatureSpan">less.tree.</span>URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL)
- description and source-code
```javascript
URL = function (val, index, currentFileInfo, isEvald) {
    this.value = val;
    this.currentFileInfo = currentFileInfo;
    this.index = index;
    this.isEvald = isEvald;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.UnicodeDescriptor"></a>[function <span class="apidocSignatureSpan">less.tree.</span>UnicodeDescriptor (value)](#apidoc.element.less.tree.UnicodeDescriptor)
- description and source-code
```javascript
UnicodeDescriptor = function (value) {
    this.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit)
- description and source-code
```javascript
Unit = function (numerator, denominator, backupUnit) {
    this.numerator = numerator ? numerator.slice(0).sort() : [];
    this.denominator = denominator ? denominator.slice(0).sort() : [];
    if (backupUnit) {
        this.backupUnit = backupUnit;
    } else if (numerator && numerator.length) {
        this.backupUnit = numerator[0];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Value"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Value (value)](#apidoc.element.less.tree.Value)
- description and source-code
```javascript
Value = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Value requires an array argument");
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Variable"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable)
- description and source-code
```javascript
Variable = function (name, index, currentFileInfo) {
    this.name = name;
    this.index = index;
    this.currentFileInfo = currentFileInfo || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Alpha"></a>[module less.tree.Alpha](#apidoc.module.less.tree.Alpha)

#### <a name="apidoc.element.less.tree.Alpha.Alpha"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Alpha (val)](#apidoc.element.less.tree.Alpha.Alpha)
- description and source-code
```javascript
Alpha = function (val) {
    this.value = val;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Alpha.prototype"></a>[module less.tree.Alpha.prototype](#apidoc.module.less.tree.Alpha.prototype)

#### <a name="apidoc.element.less.tree.Alpha.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Alpha.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.value = visitor.visit(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Alpha.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>eval (context)](#apidoc.element.less.tree.Alpha.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    if (this.value.eval) { return new Alpha(this.value.eval(context)); }
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Alpha.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Alpha.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Alpha.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add("alpha(opacity=");

    if (this.value.genCSS) {
        this.value.genCSS(context, output);
    } else {
        output.add(this.value);
    }

    output.add(")");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Anonymous"></a>[module less.tree.Anonymous](#apidoc.module.less.tree.Anonymous)

#### <a name="apidoc.element.less.tree.Anonymous.Anonymous"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Anonymous (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo)](#apidoc.element.less.tree.Anonymous.Anonymous)
- description and source-code
```javascript
Anonymous = function (value, index, currentFileInfo, mapLines, rulesetLike, visibilityInfo) {
    this.value = value;
    this.index = index;
    this.mapLines = mapLines;
    this.currentFileInfo = currentFileInfo;
    this.rulesetLike = (typeof rulesetLike === 'undefined') ? false : rulesetLike;
    this.allowRoot = true;
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Anonymous.prototype"></a>[module less.tree.Anonymous.prototype](#apidoc.module.less.tree.Anonymous.prototype)

#### <a name="apidoc.element.less.tree.Anonymous.prototype.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>compare (other)](#apidoc.element.less.tree.Anonymous.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
    return other.toCSS && this.toCSS() === other.toCSS() ? 0 : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Anonymous.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>eval ()](#apidoc.element.less.tree.Anonymous.prototype.eval)
- description and source-code
```javascript
eval = function () {
    return new Anonymous(this.value, this.index, this.currentFileInfo, this.mapLines, this.rulesetLike, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Anonymous.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Anonymous.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.value, this.currentFileInfo, this.index, this.mapLines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Anonymous.prototype.isRulesetLike"></a>[function <span class="apidocSignatureSpan">less.tree.Anonymous.prototype.</span>isRulesetLike ()](#apidoc.element.less.tree.Anonymous.prototype.isRulesetLike)
- description and source-code
```javascript
isRulesetLike = function () {
    return this.rulesetLike;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Assignment"></a>[module less.tree.Assignment](#apidoc.module.less.tree.Assignment)

#### <a name="apidoc.element.less.tree.Assignment.Assignment"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Assignment (key, val)](#apidoc.element.less.tree.Assignment.Assignment)
- description and source-code
```javascript
Assignment = function (key, val) {
    this.key = key;
    this.value = val;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Assignment.prototype"></a>[module less.tree.Assignment.prototype](#apidoc.module.less.tree.Assignment.prototype)

#### <a name="apidoc.element.less.tree.Assignment.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Assignment.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.value = visitor.visit(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Assignment.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>eval (context)](#apidoc.element.less.tree.Assignment.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    if (this.value.eval) {
        return new Assignment(this.key, this.value.eval(context));
    }
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Assignment.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Assignment.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Assignment.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.key + '=');
    if (this.value.genCSS) {
        this.value.genCSS(context, output);
    } else {
        output.add(this.value);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Attribute"></a>[module less.tree.Attribute](#apidoc.module.less.tree.Attribute)

#### <a name="apidoc.element.less.tree.Attribute.Attribute"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Attribute (key, op, value)](#apidoc.element.less.tree.Attribute.Attribute)
- description and source-code
```javascript
Attribute = function (key, op, value) {
    this.key = key;
    this.op = op;
    this.value = value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Attribute.prototype"></a>[module less.tree.Attribute.prototype](#apidoc.module.less.tree.Attribute.prototype)

#### <a name="apidoc.element.less.tree.Attribute.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>eval (context)](#apidoc.element.less.tree.Attribute.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return new Attribute(this.key.eval ? this.key.eval(context) : this.key,
        this.op, (this.value && this.value.eval) ? this.value.eval(context) : this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Attribute.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Attribute.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.toCSS(context));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Attribute.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Attribute.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Attribute.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (context) {
    var value = this.key.toCSS ? this.key.toCSS(context) : this.key;

    if (this.op) {
        value += this.op;
        value += (this.value.toCSS ? this.value.toCSS(context) : this.value);
    }

    return '[' + value + ']';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Call"></a>[module less.tree.Call](#apidoc.module.less.tree.Call)

#### <a name="apidoc.element.less.tree.Call.Call"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Call (name, args, index, currentFileInfo)](#apidoc.element.less.tree.Call.Call)
- description and source-code
```javascript
Call = function (name, args, index, currentFileInfo) {
    this.name = name;
    this.args = args;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Call.prototype"></a>[module less.tree.Call.prototype](#apidoc.module.less.tree.Call.prototype)

#### <a name="apidoc.element.less.tree.Call.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Call.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.args) {
        this.args = visitor.visitArray(this.args);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Call.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>eval (context)](#apidoc.element.less.tree.Call.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var args = this.args.map(function (a) { return a.eval(context); }),
        result, funcCaller = new FunctionCaller(this.name, context, this.index, this.currentFileInfo);

    if (funcCaller.isValid()) {
        try {
            result = funcCaller.call(args);
        } catch (e) {
            throw { type: e.type || "Runtime",
                    message: "error evaluating function '" + this.name + "'" +
                             (e.message ? ': ' + e.message : ''),
                    index: this.index, filename: this.currentFileInfo.filename };
        }

        if (result != null) {
            result.index = this.index;
            result.currentFileInfo = this.currentFileInfo;
            return result;
        }
    }

    return new Call(this.name, args, this.index, this.currentFileInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Call.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Call.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Call.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.name + "(", this.currentFileInfo, this.index);

    for (var i = 0; i < this.args.length; i++) {
        this.args[i].genCSS(context, output);
        if (i + 1 < this.args.length) {
            output.add(", ");
        }
    }

    output.add(")");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Color"></a>[module less.tree.Color](#apidoc.module.less.tree.Color)

#### <a name="apidoc.element.less.tree.Color.Color"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Color (rgb, a, originalForm)](#apidoc.element.less.tree.Color.Color)
- description and source-code
```javascript
Color = function (rgb, a, originalForm) {
    //
    // The end goal here, is to parse the arguments
    // into an integer triplet, such as '128, 255, 0'
    //
    // This facilitates operations and conversions.
    //
    if (Array.isArray(rgb)) {
        this.rgb = rgb;
    } else if (rgb.length == 6) {
        this.rgb = rgb.match(/.{2}/g).map(function (c) {
            return parseInt(c, 16);
        });
    } else {
        this.rgb = rgb.split('').map(function (c) {
            return parseInt(c + c, 16);
        });
    }
    this.alpha = typeof a === 'number' ? a : 1;
    if (typeof originalForm !== 'undefined') {
        this.value = originalForm;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.fromKeyword"></a>[function <span class="apidocSignatureSpan">less.tree.Color.</span>fromKeyword (keyword)](#apidoc.element.less.tree.Color.fromKeyword)
- description and source-code
```javascript
fromKeyword = function (keyword) {
    var c, key = keyword.toLowerCase();
    if (colors.hasOwnProperty(key)) {
        c = new Color(colors[key].slice(1));
    }
    else if (key === "transparent") {
        c = new Color([0, 0, 0], 0);
    }

    if (c) {
        c.value = keyword;
        return c;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Color.prototype"></a>[module less.tree.Color.prototype](#apidoc.module.less.tree.Color.prototype)

#### <a name="apidoc.element.less.tree.Color.prototype.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>compare (x)](#apidoc.element.less.tree.Color.prototype.compare)
- description and source-code
```javascript
compare = function (x) {
    return (x.rgb &&
        x.rgb[0] === this.rgb[0] &&
        x.rgb[1] === this.rgb[1] &&
        x.rgb[2] === this.rgb[2] &&
        x.alpha  === this.alpha) ? 0 : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Color.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.toCSS(context));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.luma"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>luma ()](#apidoc.element.less.tree.Color.prototype.luma)
- description and source-code
```javascript
luma = function () {
    var r = this.rgb[0] / 255,
        g = this.rgb[1] / 255,
        b = this.rgb[2] / 255;

    r = (r <= 0.03928) ? r / 12.92 : Math.pow(((r + 0.055) / 1.055), 2.4);
    g = (g <= 0.03928) ? g / 12.92 : Math.pow(((g + 0.055) / 1.055), 2.4);
    b = (b <= 0.03928) ? b / 12.92 : Math.pow(((b + 0.055) / 1.055), 2.4);

    return 0.2126 * r + 0.7152 * g + 0.0722 * b;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.operate"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>operate (context, op, other)](#apidoc.element.less.tree.Color.prototype.operate)
- description and source-code
```javascript
operate = function (context, op, other) {
    var rgb = [];
    var alpha = this.alpha * (1 - other.alpha) + other.alpha;
    for (var c = 0; c < 3; c++) {
        rgb[c] = this._operate(context, op, this.rgb[c], other.rgb[c]);
    }
    return new Color(rgb, alpha);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.toARGB"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toARGB ()](#apidoc.element.less.tree.Color.prototype.toARGB)
- description and source-code
```javascript
toARGB = function () {
    return toHex([this.alpha * 255].concat(this.rgb));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toCSS (context, doNotCompress)](#apidoc.element.less.tree.Color.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (context, doNotCompress) {
    var compress = context && context.compress && !doNotCompress, color, alpha;

    // 'value' is set if this color was originally
    // converted from a named color string so we need
    // to respect this and try to output named color too.
    if (this.value) {
        return this.value;
    }

    // If we have some transparency, the only way to represent it
    // is via 'rgba'. Otherwise, we use the hex representation,
    // which has better compatibility with older browsers.
    // Values are capped between '0' and '255', rounded and zero-padded.
    alpha = this.fround(context, this.alpha);
    if (alpha < 1) {
        return "rgba(" + this.rgb.map(function (c) {
            return clamp(Math.round(c), 255);
        }).concat(clamp(alpha, 1))
            .join(',' + (compress ? '' : ' ')) + ")";
    }

    color = this.toRGB();

    if (compress) {
        var splitcolor = color.split('');

        // Convert color to short format
        if (splitcolor[1] === splitcolor[2] && splitcolor[3] === splitcolor[4] && splitcolor[5] === splitcolor[6]) {
            color = '#' + splitcolor[1] + splitcolor[3] + splitcolor[5];
        }
    }

    return color;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.toHSL"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toHSL ()](#apidoc.element.less.tree.Color.prototype.toHSL)
- description and source-code
```javascript
toHSL = function () {
    var r = this.rgb[0] / 255,
        g = this.rgb[1] / 255,
        b = this.rgb[2] / 255,
        a = this.alpha;

    var max = Math.max(r, g, b), min = Math.min(r, g, b);
    var h, s, l = (max + min) / 2, d = max - min;

    if (max === min) {
        h = s = 0;
    } else {
        s = l > 0.5 ? d / (2 - max - min) : d / (max + min);

        switch (max) {
            case r: h = (g - b) / d + (g < b ? 6 : 0); break;
            case g: h = (b - r) / d + 2;               break;
            case b: h = (r - g) / d + 4;               break;
        }
        h /= 6;
    }
    return { h: h * 360, s: s, l: l, a: a };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.toHSV"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toHSV ()](#apidoc.element.less.tree.Color.prototype.toHSV)
- description and source-code
```javascript
toHSV = function () {
    var r = this.rgb[0] / 255,
        g = this.rgb[1] / 255,
        b = this.rgb[2] / 255,
        a = this.alpha;

    var max = Math.max(r, g, b), min = Math.min(r, g, b);
    var h, s, v = max;

    var d = max - min;
    if (max === 0) {
        s = 0;
    } else {
        s = d / max;
    }

    if (max === min) {
        h = 0;
    } else {
        switch(max) {
            case r: h = (g - b) / d + (g < b ? 6 : 0); break;
            case g: h = (b - r) / d + 2; break;
            case b: h = (r - g) / d + 4; break;
        }
        h /= 6;
    }
    return { h: h * 360, s: s, v: v, a: a };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Color.prototype.toRGB"></a>[function <span class="apidocSignatureSpan">less.tree.Color.prototype.</span>toRGB ()](#apidoc.element.less.tree.Color.prototype.toRGB)
- description and source-code
```javascript
toRGB = function () {
    return toHex(this.rgb);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Combinator"></a>[module less.tree.Combinator](#apidoc.module.less.tree.Combinator)

#### <a name="apidoc.element.less.tree.Combinator.Combinator"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Combinator (value)](#apidoc.element.less.tree.Combinator.Combinator)
- description and source-code
```javascript
Combinator = function (value) {
    if (value === ' ') {
        this.value = ' ';
        this.emptyOrWhitespace = true;
    } else {
        this.value = value ? value.trim() : "";
        this.emptyOrWhitespace = this.value === "";
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Combinator.prototype"></a>[module less.tree.Combinator.prototype](#apidoc.module.less.tree.Combinator.prototype)

#### <a name="apidoc.element.less.tree.Combinator.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Combinator.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Combinator.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    var spaceOrEmpty = (context.compress || _noSpaceCombinators[this.value]) ? '' : ' ';
    output.add(spaceOrEmpty + this.value + spaceOrEmpty);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Comment"></a>[module less.tree.Comment](#apidoc.module.less.tree.Comment)

#### <a name="apidoc.element.less.tree.Comment.Comment"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Comment (value, isLineComment, index, currentFileInfo)](#apidoc.element.less.tree.Comment.Comment)
- description and source-code
```javascript
Comment = function (value, isLineComment, index, currentFileInfo) {
    this.value = value;
    this.isLineComment = isLineComment;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Comment.prototype"></a>[module less.tree.Comment.prototype](#apidoc.module.less.tree.Comment.prototype)

#### <a name="apidoc.element.less.tree.Comment.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Comment.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Comment.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    if (this.debugInfo) {
        output.add(getDebugInfo(context, this), this.currentFileInfo, this.index);
    }
    output.add(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Comment.prototype.isSilent"></a>[function <span class="apidocSignatureSpan">less.tree.Comment.prototype.</span>isSilent (context)](#apidoc.element.less.tree.Comment.prototype.isSilent)
- description and source-code
```javascript
isSilent = function (context) {
    var isCompressed = context.compress && this.value[2] !== "!";
    return this.isLineComment || isCompressed;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Condition"></a>[module less.tree.Condition](#apidoc.module.less.tree.Condition)

#### <a name="apidoc.element.less.tree.Condition.Condition"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Condition (op, l, r, i, negate)](#apidoc.element.less.tree.Condition.Condition)
- description and source-code
```javascript
Condition = function (op, l, r, i, negate) {
    this.op = op.trim();
    this.lvalue = l;
    this.rvalue = r;
    this.index = i;
    this.negate = negate;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Condition.prototype"></a>[module less.tree.Condition.prototype](#apidoc.module.less.tree.Condition.prototype)

#### <a name="apidoc.element.less.tree.Condition.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Condition.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Condition.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.lvalue = visitor.visit(this.lvalue);
    this.rvalue = visitor.visit(this.rvalue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Condition.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Condition.prototype.</span>eval (context)](#apidoc.element.less.tree.Condition.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var result = (function (op, a, b) {
        switch (op) {
            case 'and': return a && b;
            case 'or':  return a || b;
            default:
                switch (Node.compare(a, b)) {
                    case -1:
                        return op === '<' || op === '=<' || op === '<=';
                    case 0:
                        return op === '=' || op === '>=' || op === '=<' || op === '<=';
                    case 1:
                        return op === '>' || op === '>=';
                    default:
                        return false;
                }
        }
    })(this.op, this.lvalue.eval(context), this.rvalue.eval(context));

    return this.negate ? !result : result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.DetachedRuleset"></a>[module less.tree.DetachedRuleset](#apidoc.module.less.tree.DetachedRuleset)

#### <a name="apidoc.element.less.tree.DetachedRuleset.DetachedRuleset"></a>[function <span class="apidocSignatureSpan">less.tree.</span>DetachedRuleset (ruleset, frames)](#apidoc.element.less.tree.DetachedRuleset.DetachedRuleset)
- description and source-code
```javascript
DetachedRuleset = function (ruleset, frames) {
    this.ruleset = ruleset;
    this.frames = frames;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.DetachedRuleset.prototype"></a>[module less.tree.DetachedRuleset.prototype](#apidoc.module.less.tree.DetachedRuleset.prototype)

#### <a name="apidoc.element.less.tree.DetachedRuleset.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>accept (visitor)](#apidoc.element.less.tree.DetachedRuleset.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.ruleset = visitor.visit(this.ruleset);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.DetachedRuleset.prototype.callEval"></a>[function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>callEval (context)](#apidoc.element.less.tree.DetachedRuleset.prototype.callEval)
- description and source-code
```javascript
callEval = function (context) {
    return this.ruleset.eval(this.frames ? new contexts.Eval(context, this.frames.concat(context.frames)) : context);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.DetachedRuleset.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.DetachedRuleset.prototype.</span>eval (context)](#apidoc.element.less.tree.DetachedRuleset.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var frames = this.frames || context.frames.slice(0);
    return new DetachedRuleset(this.ruleset, frames);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Dimension"></a>[module less.tree.Dimension](#apidoc.module.less.tree.Dimension)

#### <a name="apidoc.element.less.tree.Dimension.Dimension"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Dimension (value, unit)](#apidoc.element.less.tree.Dimension.Dimension)
- description and source-code
```javascript
Dimension = function (value, unit) {
    this.value = parseFloat(value);
    this.unit = (unit && unit instanceof Unit) ? unit :
      new Unit(unit ? [unit] : undefined);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Dimension.prototype"></a>[module less.tree.Dimension.prototype](#apidoc.module.less.tree.Dimension.prototype)

#### <a name="apidoc.element.less.tree.Dimension.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Dimension.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.unit = visitor.visit(this.unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>compare (other)](#apidoc.element.less.tree.Dimension.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
    var a, b;

    if (!(other instanceof Dimension)) {
        return undefined;
    }

    if (this.unit.isEmpty() || other.unit.isEmpty()) {
        a = this;
        b = other;
    } else {
        a = this.unify();
        b = other.unify();
        if (a.unit.compare(b.unit) !== 0) {
            return undefined;
        }
    }

    return Node.numericCompare(a.value, b.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.convertTo"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>convertTo (conversions)](#apidoc.element.less.tree.Dimension.prototype.convertTo)
- description and source-code
```javascript
convertTo = function (conversions) {
    var value = this.value, unit = this.unit.clone(),
        i, groupName, group, targetUnit, derivedConversions = {}, applyUnit;

    if (typeof conversions === 'string') {
        for (i in unitConversions) {
            if (unitConversions[i].hasOwnProperty(conversions)) {
                derivedConversions = {};
                derivedConversions[i] = conversions;
            }
        }
        conversions = derivedConversions;
    }
    applyUnit = function (atomicUnit, denominator) {
<span class="apidocCodeCommentSpan">        /* jshint loopfunc:true */
</span>        if (group.hasOwnProperty(atomicUnit)) {
            if (denominator) {
                value = value / (group[atomicUnit] / group[targetUnit]);
            } else {
                value = value * (group[atomicUnit] / group[targetUnit]);
            }

            return targetUnit;
        }

        return atomicUnit;
    };

    for (groupName in conversions) {
        if (conversions.hasOwnProperty(groupName)) {
            targetUnit = conversions[groupName];
            group = unitConversions[groupName];

            unit.map(applyUnit);
        }
    }

    unit.cancel();

    return new Dimension(value, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>eval (context)](#apidoc.element.less.tree.Dimension.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Dimension.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    if ((context && context.strictUnits) && !this.unit.isSingular()) {
        throw new Error("Multiple units in dimension. Correct the units or use the unit function. Bad unit: " + this.unit.toString
());
    }

    var value = this.fround(context, this.value),
        strValue = String(value);

    if (value !== 0 && value < 0.000001 && value > -0.000001) {
        // would be output 1e-6 etc.
        strValue = value.toFixed(20).replace(/0+$/, "");
    }

    if (context && context.compress) {
        // Zero values doesn't need a unit
        if (value === 0 && this.unit.isLength()) {
            output.add(strValue);
            return;
        }

        // Float values doesn't need a leading zero
        if (value > 0 && value < 1) {
            strValue = (strValue).substr(1);
        }
    }

    output.add(strValue);
    this.unit.genCSS(context, output);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.operate"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>operate (context, op, other)](#apidoc.element.less.tree.Dimension.prototype.operate)
- description and source-code
```javascript
operate = function (context, op, other) {
<span class="apidocCodeCommentSpan">    /*jshint noempty:false */
</span>    var value = this._operate(context, op, this.value, other.value),
        unit = this.unit.clone();

    if (op === '+' || op === '-') {
        if (unit.numerator.length === 0 && unit.denominator.length === 0) {
            unit = other.unit.clone();
            if (this.unit.backupUnit) {
                unit.backupUnit = this.unit.backupUnit;
            }
        } else if (other.unit.numerator.length === 0 && unit.denominator.length === 0) {
            // do nothing
        } else {
            other = other.convertTo(this.unit.usedUnits());

            if (context.strictUnits && other.unit.toString() !== unit.toString()) {
                throw new Error("Incompatible units. Change the units or use the unit function. Bad units: '" + unit.toString() +
                    "' and '" + other.unit.toString() + "'.");
            }

            value = this._operate(context, op, this.value, other.value);
        }
    } else if (op === '*') {
        unit.numerator = unit.numerator.concat(other.unit.numerator).sort();
        unit.denominator = unit.denominator.concat(other.unit.denominator).sort();
        unit.cancel();
    } else if (op === '/') {
        unit.numerator = unit.numerator.concat(other.unit.denominator).sort();
        unit.denominator = unit.denominator.concat(other.unit.numerator).sort();
        unit.cancel();
    }
    return new Dimension(value, unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.toColor"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>toColor ()](#apidoc.element.less.tree.Dimension.prototype.toColor)
- description and source-code
```javascript
toColor = function () {
    return new Color([this.value, this.value, this.value]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Dimension.prototype.unify"></a>[function <span class="apidocSignatureSpan">less.tree.Dimension.prototype.</span>unify ()](#apidoc.element.less.tree.Dimension.prototype.unify)
- description and source-code
```javascript
unify = function () {
    return this.convertTo({ length: 'px', duration: 's', angle: 'rad' });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Directive"></a>[module less.tree.Directive](#apidoc.module.less.tree.Directive)

#### <a name="apidoc.element.less.tree.Directive.Directive"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Directive (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo)](#apidoc.element.less.tree.Directive.Directive)
- description and source-code
```javascript
Directive = function (name, value, rules, index, currentFileInfo, debugInfo, isRooted, visibilityInfo) {
    var i;

    this.name  = name;
    this.value = value;
    if (rules) {
        if (Array.isArray(rules)) {
            this.rules = rules;
        } else {
            this.rules = [rules];
            this.rules[0].selectors = (new Selector([], null, null, this.index, currentFileInfo)).createEmptySelectors();
        }
        for (i = 0; i < this.rules.length; i++) {
            this.rules[i].allowImports = true;
        }
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.debugInfo = debugInfo;
    this.isRooted = isRooted || false;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Directive.prototype"></a>[module less.tree.Directive.prototype](#apidoc.module.less.tree.Directive.prototype)

#### <a name="apidoc.element.less.tree.Directive.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Directive.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    var value = this.value, rules = this.rules;
    if (rules) {
        this.rules = visitor.visitArray(rules);
    }
    if (value) {
        this.value = visitor.visit(value);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>eval (context)](#apidoc.element.less.tree.Directive.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var mediaPathBackup, mediaBlocksBackup, value = this.value, rules = this.rules;

    //media stored inside other directive should not bubble over it
    //backpup media bubbling information
    mediaPathBackup = context.mediaPath;
    mediaBlocksBackup = context.mediaBlocks;
    //deleted media bubbling information
    context.mediaPath = [];
    context.mediaBlocks = [];

    if (value) {
        value = value.eval(context);
    }
    if (rules) {
        // assuming that there is only one rule at this point - that is how parser constructs the rule
        rules = [rules[0].eval(context)];
        rules[0].root = true;
    }
    //restore media bubbling information
    context.mediaPath = mediaPathBackup;
    context.mediaBlocks = mediaBlocksBackup;

    return new Directive(this.name, value, rules,
        this.index, this.currentFileInfo, this.debugInfo, this.isRooted, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.find"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>find ()](#apidoc.element.less.tree.Directive.prototype.find)
- description and source-code
```javascript
find = function () {
    if (this.rules) {
        // assuming that there is only one rule at this point - that is how parser constructs the rule
        return Ruleset.prototype.find.apply(this.rules[0], arguments);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Directive.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    var value = this.value, rules = this.rules;
    output.add(this.name, this.currentFileInfo, this.index);
    if (value) {
        output.add(' ');
        value.genCSS(context, output);
    }
    if (rules) {
        this.outputRuleset(context, output, rules);
    } else {
        output.add(';');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.isCharset"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>isCharset ()](#apidoc.element.less.tree.Directive.prototype.isCharset)
- description and source-code
```javascript
isCharset = function () {
    return "@charset" === this.name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.isRulesetLike"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>isRulesetLike ()](#apidoc.element.less.tree.Directive.prototype.isRulesetLike)
- description and source-code
```javascript
isRulesetLike = function () {
    return this.rules || !this.isCharset();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.outputRuleset"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>outputRuleset (context, output, rules)](#apidoc.element.less.tree.Directive.prototype.outputRuleset)
- description and source-code
```javascript
outputRuleset = function (context, output, rules) {
    var ruleCnt = rules.length, i;
    context.tabLevel = (context.tabLevel | 0) + 1;

    // Compressed
    if (context.compress) {
        output.add('{');
        for (i = 0; i < ruleCnt; i++) {
            rules[i].genCSS(context, output);
        }
        output.add('}');
        context.tabLevel--;
        return;
    }

    // Non-compressed
    var tabSetStr = '\n' + Array(context.tabLevel).join("  "), tabRuleStr = tabSetStr + "  ";
    if (!ruleCnt) {
        output.add(" {" + tabSetStr + '}');
    } else {
        output.add(" {" + tabRuleStr);
        rules[0].genCSS(context, output);
        for (i = 1; i < ruleCnt; i++) {
            output.add(tabRuleStr);
            rules[i].genCSS(context, output);
        }
        output.add(tabSetStr + '}');
    }

    context.tabLevel--;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.rulesets"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>rulesets ()](#apidoc.element.less.tree.Directive.prototype.rulesets)
- description and source-code
```javascript
rulesets = function () {
    if (this.rules) {
        // assuming that there is only one rule at this point - that is how parser constructs the rule
        return Ruleset.prototype.rulesets.apply(this.rules[0]);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Directive.prototype.variable"></a>[function <span class="apidocSignatureSpan">less.tree.Directive.prototype.</span>variable (name)](#apidoc.element.less.tree.Directive.prototype.variable)
- description and source-code
```javascript
variable = function (name) {
    if (this.rules) {
        // assuming that there is only one rule at this point - that is how parser constructs the rule
        return Ruleset.prototype.variable.call(this.rules[0], name);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Element"></a>[module less.tree.Element](#apidoc.module.less.tree.Element)

#### <a name="apidoc.element.less.tree.Element.Element"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Element (combinator, value, index, currentFileInfo, info)](#apidoc.element.less.tree.Element.Element)
- description and source-code
```javascript
Element = function (combinator, value, index, currentFileInfo, info) {
    this.combinator = combinator instanceof Combinator ?
                      combinator : new Combinator(combinator);

    if (typeof value === 'string') {
        this.value = value.trim();
    } else if (value) {
        this.value = value;
    } else {
        this.value = "";
    }
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.copyVisibilityInfo(info);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Element.prototype"></a>[module less.tree.Element.prototype](#apidoc.module.less.tree.Element.prototype)

#### <a name="apidoc.element.less.tree.Element.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Element.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    var value = this.value;
    this.combinator = visitor.visit(this.combinator);
    if (typeof value === "object") {
        this.value = visitor.visit(value);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element.prototype.clone"></a>[function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>clone ()](#apidoc.element.less.tree.Element.prototype.clone)
- description and source-code
```javascript
clone = function () {
    return new Element(this.combinator,
        this.value,
        this.index,
        this.currentFileInfo, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>eval (context)](#apidoc.element.less.tree.Element.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return new Element(this.combinator,
                             this.value.eval ? this.value.eval(context) : this.value,
                             this.index,
                             this.currentFileInfo, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Element.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.toCSS(context), this.currentFileInfo, this.index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Element.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Element.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Element.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (context) {
    context = context || {};
    var value = this.value, firstSelector = context.firstSelector;
    if (value instanceof Paren) {
        // selector in parens should not be affected by outer selector
        // flags (breaks only interpolated selectors - see #1973)
        context.firstSelector = true;
    }
    value = value.toCSS ? value.toCSS(context) : value;
    context.firstSelector = firstSelector;
    if (value === '' && this.combinator.value.charAt(0) === '&') {
        return '';
    } else {
        return this.combinator.toCSS(context) + value;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Expression"></a>[module less.tree.Expression](#apidoc.module.less.tree.Expression)

#### <a name="apidoc.element.less.tree.Expression.Expression"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Expression (value)](#apidoc.element.less.tree.Expression.Expression)
- description and source-code
```javascript
Expression = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Expression requires an array parameter");
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Expression.prototype"></a>[module less.tree.Expression.prototype](#apidoc.module.less.tree.Expression.prototype)

#### <a name="apidoc.element.less.tree.Expression.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Expression.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.value = visitor.visitArray(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Expression.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>eval (context)](#apidoc.element.less.tree.Expression.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var returnValue,
        inParenthesis = this.parens && !this.parensInOp,
        doubleParen = false;
    if (inParenthesis) {
        context.inParenthesis();
    }
    if (this.value.length > 1) {
        returnValue = new Expression(this.value.map(function (e) {
            return e.eval(context);
        }));
    } else if (this.value.length === 1) {
        if (this.value[0].parens && !this.value[0].parensInOp) {
            doubleParen = true;
        }
        returnValue = this.value[0].eval(context);
    } else {
        returnValue = this;
    }
    if (inParenthesis) {
        context.outOfParenthesis();
    }
    if (this.parens && this.parensInOp && !(context.isMathOn()) && !doubleParen) {
        returnValue = new Paren(returnValue);
    }
    return returnValue;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Expression.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Expression.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    for (var i = 0; i < this.value.length; i++) {
        this.value[i].genCSS(context, output);
        if (i + 1 < this.value.length) {
            output.add(" ");
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Expression.prototype.throwAwayComments"></a>[function <span class="apidocSignatureSpan">less.tree.Expression.prototype.</span>throwAwayComments ()](#apidoc.element.less.tree.Expression.prototype.throwAwayComments)
- description and source-code
```javascript
throwAwayComments = function () {
    this.value = this.value.filter(function(v) {
        return !(v instanceof Comment);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Extend"></a>[module less.tree.Extend](#apidoc.module.less.tree.Extend)

#### <a name="apidoc.element.less.tree.Extend.Extend"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Extend (selector, option, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Extend.Extend)
- description and source-code
```javascript
function Extend(selector, option, index, currentFileInfo, visibilityInfo) {
    this.selector = selector;
    this.option = option;
    this.index = index;
    this.object_id = Extend.next_id++;
    this.parent_ids = [this.object_id];
    this.currentFileInfo = currentFileInfo || {};
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;

    switch(option) {
        case "all":
            this.allowBefore = true;
            this.allowAfter = true;
            break;
        default:
            this.allowBefore = false;
            this.allowAfter = false;
            break;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Extend.prototype"></a>[module less.tree.Extend.prototype](#apidoc.module.less.tree.Extend.prototype)

#### <a name="apidoc.element.less.tree.Extend.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Extend.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.selector = visitor.visit(this.selector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Extend.prototype.clone"></a>[function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>clone (context)](#apidoc.element.less.tree.Extend.prototype.clone)
- description and source-code
```javascript
clone = function (context) {
    return new Extend(this.selector, this.option, this.index, this.currentFileInfo, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Extend.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>eval (context)](#apidoc.element.less.tree.Extend.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return new Extend(this.selector.eval(context), this.option, this.index, this.currentFileInfo, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Extend.prototype.findSelfSelectors"></a>[function <span class="apidocSignatureSpan">less.tree.Extend.prototype.</span>findSelfSelectors (selectors)](#apidoc.element.less.tree.Extend.prototype.findSelfSelectors)
- description and source-code
```javascript
findSelfSelectors = function (selectors) {
    var selfElements = [],
        i,
        selectorElements;

    for (i = 0; i < selectors.length; i++) {
        selectorElements = selectors[i].elements;
        // duplicate the logic in genCSS function inside the selector node.
        // future TODO - move both logics into the selector joiner visitor
        if (i > 0 && selectorElements.length && selectorElements[0].combinator.value === "") {
            selectorElements[0].combinator.value = ' ';
        }
        selfElements = selfElements.concat(selectors[i].elements);
    }

    this.selfSelectors = [new Selector(selfElements)];
    this.selfSelectors[0].copyVisibilityInfo(this.visibilityInfo());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Import"></a>[module less.tree.Import](#apidoc.module.less.tree.Import)

#### <a name="apidoc.element.less.tree.Import.Import"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Import (path, features, options, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Import.Import)
- description and source-code
```javascript
Import = function (path, features, options, index, currentFileInfo, visibilityInfo) {
    this.options = options;
    this.index = index;
    this.path = path;
    this.features = features;
    this.currentFileInfo = currentFileInfo;
    this.allowRoot = true;

    if (this.options.less !== undefined || this.options.inline) {
        this.css = !this.options.less || this.options.inline;
    } else {
        var pathValue = this.getPath();
        if (pathValue && /[#\.\&\?\/]css([\?;].*)?$/.test(pathValue)) {
            this.css = true;
        }
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Import.prototype"></a>[module less.tree.Import.prototype](#apidoc.module.less.tree.Import.prototype)

#### <a name="apidoc.element.less.tree.Import.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Import.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.features) {
        this.features = visitor.visit(this.features);
    }
    this.path = visitor.visit(this.path);
    if (!this.options.plugin && !this.options.inline && this.root) {
        this.root = visitor.visit(this.root);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.doEval"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>doEval (context)](#apidoc.element.less.tree.Import.prototype.doEval)
- description and source-code
```javascript
doEval = function (context) {
    var ruleset, registry,
        features = this.features && this.features.eval(context);

    if (this.options.plugin) {
        registry = context.frames[0] && context.frames[0].functionRegistry;
        if ( registry && this.root && this.root.functions ) {
            registry.addMultiple( this.root.functions );
        }
        return [];
    }

    if (this.skip) {
        if (typeof this.skip === "function") {
            this.skip = this.skip();
        }
        if (this.skip) {
            return [];
        }
    }
    if (this.options.inline) {
        var contents = new Anonymous(this.root, 0,
          {
              filename: this.importedFilename,
              reference: this.path.currentFileInfo && this.path.currentFileInfo.reference
          }, true, true);

        return this.features ? new Media([contents], this.features.value) : [contents];
    } else if (this.css) {
        var newImport = new Import(this.evalPath(context), features, this.options, this.index);
        if (!newImport.css && this.error) {
            throw this.error;
        }
        return newImport;
    } else {
        ruleset = new Ruleset(null, this.root.rules.slice(0));
        ruleset.evalImports(context);

        return this.features ? new Media(ruleset.rules, this.features.value) : ruleset.rules;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>eval (context)](#apidoc.element.less.tree.Import.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var result = this.doEval(context);
    if (this.options.reference || this.blocksVisibility()) {
        if (result.length || result.length === 0) {
            result.forEach(function (node) {
                    node.addVisibilityBlock();
                }
            );
        } else {
            result.addVisibilityBlock();
        }
    }
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.evalForImport"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>evalForImport (context)](#apidoc.element.less.tree.Import.prototype.evalForImport)
- description and source-code
```javascript
evalForImport = function (context) {
    var path = this.path;

    if (path instanceof URL) {
        path = path.value;
    }

    return new Import(path.eval(context), this.features, this.options, this.index, this.currentFileInfo, this.visibilityInfo());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.evalPath"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>evalPath (context)](#apidoc.element.less.tree.Import.prototype.evalPath)
- description and source-code
```javascript
evalPath = function (context) {
    var path = this.path.eval(context);
    var rootpath = this.currentFileInfo && this.currentFileInfo.rootpath;

    if (!(path instanceof URL)) {
        if (rootpath) {
            var pathValue = path.value;
            // Add the base path if the import is relative
            if (pathValue && context.isPathRelative(pathValue)) {
                path.value = rootpath + pathValue;
            }
        }
        path.value = context.normalizePath(path.value);
    }

    return path;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Import.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    if (this.css && this.path.currentFileInfo.reference === undefined) {
        output.add("@import ", this.currentFileInfo, this.index);
        this.path.genCSS(context, output);
        if (this.features) {
            output.add(" ");
            this.features.genCSS(context, output);
        }
        output.add(';');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.getPath"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>getPath ()](#apidoc.element.less.tree.Import.prototype.getPath)
- description and source-code
```javascript
getPath = function () {
    return (this.path instanceof URL) ?
        this.path.value.value : this.path.value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Import.prototype.isVariableImport"></a>[function <span class="apidocSignatureSpan">less.tree.Import.prototype.</span>isVariableImport ()](#apidoc.element.less.tree.Import.prototype.isVariableImport)
- description and source-code
```javascript
isVariableImport = function () {
    var path = this.path;
    if (path instanceof URL) {
        path = path.value;
    }
    if (path instanceof Quoted) {
        return path.containsVariables();
    }

    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.JavaScript"></a>[module less.tree.JavaScript](#apidoc.module.less.tree.JavaScript)

#### <a name="apidoc.element.less.tree.JavaScript.JavaScript"></a>[function <span class="apidocSignatureSpan">less.tree.</span>JavaScript (string, escaped, index, currentFileInfo)](#apidoc.element.less.tree.JavaScript.JavaScript)
- description and source-code
```javascript
JavaScript = function (string, escaped, index, currentFileInfo) {
    this.escaped = escaped;
    this.expression = string;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.JavaScript.prototype"></a>[module less.tree.JavaScript.prototype](#apidoc.module.less.tree.JavaScript.prototype)

#### <a name="apidoc.element.less.tree.JavaScript.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.JavaScript.prototype.</span>eval (context)](#apidoc.element.less.tree.JavaScript.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var result = this.evaluateJavaScript(this.expression, context);

    if (typeof result === 'number') {
        return new Dimension(result);
    } else if (typeof result === 'string') {
        return new Quoted('"' + result + '"', result, this.escaped, this.index);
    } else if (Array.isArray(result)) {
        return new Anonymous(result.join(', '));
    } else {
        return new Anonymous(result);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Keyword"></a>[module less.tree.Keyword](#apidoc.module.less.tree.Keyword)

#### <a name="apidoc.element.less.tree.Keyword.Keyword"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Keyword (value)](#apidoc.element.less.tree.Keyword.Keyword)
- description and source-code
```javascript
Keyword = function (value) { this.value = value; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Keyword.prototype"></a>[module less.tree.Keyword.prototype](#apidoc.module.less.tree.Keyword.prototype)

#### <a name="apidoc.element.less.tree.Keyword.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Keyword.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Keyword.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    if (this.value === '%') { throw { type: "Syntax", message: "Invalid % without number" }; }
    output.add(this.value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Media"></a>[module less.tree.Media](#apidoc.module.less.tree.Media)

#### <a name="apidoc.element.less.tree.Media.Media"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Media (value, features, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Media.Media)
- description and source-code
```javascript
Media = function (value, features, index, currentFileInfo, visibilityInfo) {
    this.index = index;
    this.currentFileInfo = currentFileInfo;

    var selectors = (new Selector([], null, null, this.index, this.currentFileInfo)).createEmptySelectors();

    this.features = new Value(features);
    this.rules = [new Ruleset(selectors, value)];
    this.rules[0].allowImports = true;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Media.prototype"></a>[module less.tree.Media.prototype](#apidoc.module.less.tree.Media.prototype)

#### <a name="apidoc.element.less.tree.Media.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Media.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.features) {
        this.features = visitor.visit(this.features);
    }
    if (this.rules) {
        this.rules = visitor.visitArray(this.rules);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.bubbleSelectors"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>bubbleSelectors (selectors)](#apidoc.element.less.tree.Media.prototype.bubbleSelectors)
- description and source-code
```javascript
bubbleSelectors = function (selectors) {
    if (!selectors) {
        return;
    }
    this.rules = [new Ruleset(selectors.slice(0), [this.rules[0]])];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>eval (context)](#apidoc.element.less.tree.Media.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    if (!context.mediaBlocks) {
        context.mediaBlocks = [];
        context.mediaPath = [];
    }

    var media = new Media(null, [], this.index, this.currentFileInfo, this.visibilityInfo());
    if (this.debugInfo) {
        this.rules[0].debugInfo = this.debugInfo;
        media.debugInfo = this.debugInfo;
    }
    var strictMathBypass = false;
    if (!context.strictMath) {
        strictMathBypass = true;
        context.strictMath = true;
    }
    try {
        media.features = this.features.eval(context);
    }
    finally {
        if (strictMathBypass) {
            context.strictMath = false;
        }
    }

    context.mediaPath.push(media);
    context.mediaBlocks.push(media);

    this.rules[0].functionRegistry = context.frames[0].functionRegistry.inherit();
    context.frames.unshift(this.rules[0]);
    media.rules = [this.rules[0].eval(context)];
    context.frames.shift();

    context.mediaPath.pop();

    return context.mediaPath.length === 0 ? media.evalTop(context) :
                media.evalNested(context);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.evalNested"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>evalNested (context)](#apidoc.element.less.tree.Media.prototype.evalNested)
- description and source-code
```javascript
evalNested = function (context) {
    var i, value,
        path = context.mediaPath.concat([this]);

    // Extract the media-query conditions separated with ',' (OR).
    for (i = 0; i < path.length; i++) {
        value = path[i].features instanceof Value ?
                    path[i].features.value : path[i].features;
        path[i] = Array.isArray(value) ? value : [value];
    }

    // Trace all permutations to generate the resulting media-query.
    //
    // (a, b and c) with nested (d, e) ->
    //    a and d
    //    a and e
    //    b and c and d
    //    b and c and e
    this.features = new Value(this.permute(path).map(function (path) {
        path = path.map(function (fragment) {
            return fragment.toCSS ? fragment : new Anonymous(fragment);
        });

        for (i = path.length - 1; i > 0; i--) {
            path.splice(i, 0, new Anonymous("and"));
        }

        return new Expression(path);
    }));

    // Fake a tree-node that doesn't output anything.
    return new Ruleset([], []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.evalTop"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>evalTop (context)](#apidoc.element.less.tree.Media.prototype.evalTop)
- description and source-code
```javascript
evalTop = function (context) {
    var result = this;

    // Render all dependent Media blocks.
    if (context.mediaBlocks.length > 1) {
        var selectors = (new Selector([], null, null, this.index, this.currentFileInfo)).createEmptySelectors();
        result = new Ruleset(selectors, context.mediaBlocks);
        result.multiMedia = true;
        result.copyVisibilityInfo(this.visibilityInfo());
    }

    delete context.mediaBlocks;
    delete context.mediaPath;

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Media.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add('@media ', this.currentFileInfo, this.index);
    this.features.genCSS(context, output);
    this.outputRuleset(context, output, this.rules);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Media.prototype.permute"></a>[function <span class="apidocSignatureSpan">less.tree.Media.prototype.</span>permute (arr)](#apidoc.element.less.tree.Media.prototype.permute)
- description and source-code
```javascript
permute = function (arr) {
    if (arr.length === 0) {
        return [];
    } else if (arr.length === 1) {
        return arr[0];
    } else {
        var result = [];
        var rest = this.permute(arr.slice(1));
        for (var i = 0; i < rest.length; i++) {
            for (var j = 0; j < arr[0].length; j++) {
                result.push([arr[0][j]].concat(rest[i]));
            }
        }
        return result;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Negative"></a>[module less.tree.Negative](#apidoc.module.less.tree.Negative)

#### <a name="apidoc.element.less.tree.Negative.Negative"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Negative (node)](#apidoc.element.less.tree.Negative.Negative)
- description and source-code
```javascript
Negative = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Negative.prototype"></a>[module less.tree.Negative.prototype](#apidoc.module.less.tree.Negative.prototype)

#### <a name="apidoc.element.less.tree.Negative.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Negative.prototype.</span>eval (context)](#apidoc.element.less.tree.Negative.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    if (context.isMathOn()) {
        return (new Operation('*', [new Dimension(-1), this.value])).eval(context);
    }
    return new Negative(this.value.eval(context));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Negative.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Negative.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Negative.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add('-');
    this.value.genCSS(context, output);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Node"></a>[module less.tree.Node](#apidoc.module.less.tree.Node)

#### <a name="apidoc.element.less.tree.Node.Node"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Node ()](#apidoc.element.less.tree.Node.Node)
- description and source-code
```javascript
Node = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Node.</span>compare (a, b)](#apidoc.element.less.tree.Node.compare)
- description and source-code
```javascript
compare = function (a, b) {
<span class="apidocCodeCommentSpan">    /* returns:
     -1: a < b
     0: a = b
     1: a > b
     and *any* other value for a != b (e.g. undefined, NaN, -2 etc.) */
</span>
    if ((a.compare) &&
        // for "symmetric results" force toCSS-based comparison
        // of Quoted or Anonymous if either value is one of those
        !(b.type === "Quoted" || b.type === "Anonymous")) {
        return a.compare(b);
    } else if (b.compare) {
        return -b.compare(a);
    } else if (a.type !== b.type) {
        return undefined;
    }

    a = a.value;
    b = b.value;
    if (!Array.isArray(a)) {
        return a === b ? 0 : undefined;
    }
    if (a.length !== b.length) {
        return undefined;
    }
    for (var i = 0; i < a.length; i++) {
        if (Node.compare(a[i], b[i]) !== 0) {
            return undefined;
        }
    }
    return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.numericCompare"></a>[function <span class="apidocSignatureSpan">less.tree.Node.</span>numericCompare (a, b)](#apidoc.element.less.tree.Node.numericCompare)
- description and source-code
```javascript
numericCompare = function (a, b) {
    return a  <  b ? -1
        : a === b ?  0
        : a  >  b ?  1 : undefined;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Node.prototype"></a>[module less.tree.Node.prototype](#apidoc.module.less.tree.Node.prototype)

#### <a name="apidoc.element.less.tree.Node.prototype._operate"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>_operate (context, op, a, b)](#apidoc.element.less.tree.Node.prototype._operate)
- description and source-code
```javascript
_operate = function (context, op, a, b) {
    switch (op) {
        case '+': return a + b;
        case '-': return a - b;
        case '*': return a * b;
        case '/': return a / b;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Node.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.value = visitor.visit(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.addVisibilityBlock"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>addVisibilityBlock ()](#apidoc.element.less.tree.Node.prototype.addVisibilityBlock)
- description and source-code
```javascript
addVisibilityBlock = function () {
    if (this.visibilityBlocks == null) {
        this.visibilityBlocks = 0;
    }
    this.visibilityBlocks = this.visibilityBlocks + 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.blocksVisibility"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>blocksVisibility ()](#apidoc.element.less.tree.Node.prototype.blocksVisibility)
- description and source-code
```javascript
blocksVisibility = function () {
    if (this.visibilityBlocks == null) {
        this.visibilityBlocks = 0;
    }
    return this.visibilityBlocks !== 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.copyVisibilityInfo"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>copyVisibilityInfo (info)](#apidoc.element.less.tree.Node.prototype.copyVisibilityInfo)
- description and source-code
```javascript
copyVisibilityInfo = function (info) {
    if (!info) {
        return;
    }
    this.visibilityBlocks = info.visibilityBlocks;
    this.nodeVisible = info.nodeVisible;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.ensureInvisibility"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>ensureInvisibility ()](#apidoc.element.less.tree.Node.prototype.ensureInvisibility)
- description and source-code
```javascript
ensureInvisibility = function () {
    this.nodeVisible = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.ensureVisibility"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>ensureVisibility ()](#apidoc.element.less.tree.Node.prototype.ensureVisibility)
- description and source-code
```javascript
ensureVisibility = function () {
    this.nodeVisible = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>eval ()](#apidoc.element.less.tree.Node.prototype.eval)
- description and source-code
```javascript
eval = function () { return this; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.fround"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>fround (context, value)](#apidoc.element.less.tree.Node.prototype.fround)
- description and source-code
```javascript
fround = function (context, value) {
    var precision = context && context.numPrecision;
    //add "epsilon" to ensure numbers like 1.000000005 (represented as 1.000000004999....) are properly rounded...
    return (precision == null) ? value : Number((value + 2e-16).toFixed(precision));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Node.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.isVisible"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>isVisible ()](#apidoc.element.less.tree.Node.prototype.isVisible)
- description and source-code
```javascript
isVisible = function () {
    return this.nodeVisible;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.removeVisibilityBlock"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>removeVisibilityBlock ()](#apidoc.element.less.tree.Node.prototype.removeVisibilityBlock)
- description and source-code
```javascript
removeVisibilityBlock = function () {
    if (this.visibilityBlocks == null) {
        this.visibilityBlocks = 0;
    }
    this.visibilityBlocks = this.visibilityBlocks - 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.toCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>toCSS (context)](#apidoc.element.less.tree.Node.prototype.toCSS)
- description and source-code
```javascript
toCSS = function (context) {
    var strs = [];
    this.genCSS(context, {
        add: function(chunk, fileInfo, index) {
            strs.push(chunk);
        },
        isEmpty: function () {
            return strs.length === 0;
        }
    });
    return strs.join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Node.prototype.visibilityInfo"></a>[function <span class="apidocSignatureSpan">less.tree.Node.prototype.</span>visibilityInfo ()](#apidoc.element.less.tree.Node.prototype.visibilityInfo)
- description and source-code
```javascript
visibilityInfo = function () {
    return {
        visibilityBlocks: this.visibilityBlocks,
        nodeVisible: this.nodeVisible
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Operation"></a>[module less.tree.Operation](#apidoc.module.less.tree.Operation)

#### <a name="apidoc.element.less.tree.Operation.Operation"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Operation (op, operands, isSpaced)](#apidoc.element.less.tree.Operation.Operation)
- description and source-code
```javascript
Operation = function (op, operands, isSpaced) {
    this.op = op.trim();
    this.operands = operands;
    this.isSpaced = isSpaced;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Operation.prototype"></a>[module less.tree.Operation.prototype](#apidoc.module.less.tree.Operation.prototype)

#### <a name="apidoc.element.less.tree.Operation.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Operation.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.operands = visitor.visit(this.operands);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Operation.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>eval (context)](#apidoc.element.less.tree.Operation.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var a = this.operands[0].eval(context),
        b = this.operands[1].eval(context);

    if (context.isMathOn()) {
        if (a instanceof Dimension && b instanceof Color) {
            a = a.toColor();
        }
        if (b instanceof Dimension && a instanceof Color) {
            b = b.toColor();
        }
        if (!a.operate) {
            throw { type: "Operation",
                    message: "Operation on an invalid type" };
        }

        return a.operate(context, this.op, b);
    } else {
        return new Operation(this.op, [a, b], this.isSpaced);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Operation.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Operation.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Operation.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    this.operands[0].genCSS(context, output);
    if (this.isSpaced) {
        output.add(" ");
    }
    output.add(this.op);
    if (this.isSpaced) {
        output.add(" ");
    }
    this.operands[1].genCSS(context, output);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Paren"></a>[module less.tree.Paren](#apidoc.module.less.tree.Paren)

#### <a name="apidoc.element.less.tree.Paren.Paren"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Paren (node)](#apidoc.element.less.tree.Paren.Paren)
- description and source-code
```javascript
Paren = function (node) {
    this.value = node;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Paren.prototype"></a>[module less.tree.Paren.prototype](#apidoc.module.less.tree.Paren.prototype)

#### <a name="apidoc.element.less.tree.Paren.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Paren.prototype.</span>eval (context)](#apidoc.element.less.tree.Paren.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return new Paren(this.value.eval(context));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Paren.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Paren.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Paren.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add('(');
    this.value.genCSS(context, output);
    output.add(')');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Quoted"></a>[module less.tree.Quoted](#apidoc.module.less.tree.Quoted)

#### <a name="apidoc.element.less.tree.Quoted.Quoted"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Quoted (str, content, escaped, index, currentFileInfo)](#apidoc.element.less.tree.Quoted.Quoted)
- description and source-code
```javascript
Quoted = function (str, content, escaped, index, currentFileInfo) {
    this.escaped = (escaped == null) ? true : escaped;
    this.value = content || '';
    this.quote = str.charAt(0);
    this.index = index;
    this.currentFileInfo = currentFileInfo;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Quoted.prototype"></a>[module less.tree.Quoted.prototype](#apidoc.module.less.tree.Quoted.prototype)

#### <a name="apidoc.element.less.tree.Quoted.prototype.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>compare (other)](#apidoc.element.less.tree.Quoted.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
    // when comparing quoted strings allow the quote to differ
    if (other.type === "Quoted" && !this.escaped && !other.escaped) {
        return Node.numericCompare(this.value, other.value);
    } else {
        return other.toCSS && this.toCSS() === other.toCSS() ? 0 : undefined;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Quoted.prototype.containsVariables"></a>[function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>containsVariables ()](#apidoc.element.less.tree.Quoted.prototype.containsVariables)
- description and source-code
```javascript
containsVariables = function () {
    return this.value.match(/('([^']+)')|@\{([\w-]+)\}/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Quoted.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>eval (context)](#apidoc.element.less.tree.Quoted.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var that = this, value = this.value;
    var javascriptReplacement = function (_, exp) {
        return String(that.evaluateJavaScript(exp, context));
    };
    var interpolationReplacement = function (_, name) {
        var v = new Variable('@' + name, that.index, that.currentFileInfo).eval(context, true);
        return (v instanceof Quoted) ? v.value : v.toCSS();
    };
    function iterativeReplace(value, regexp, replacementFnc) {
        var evaluatedValue = value;
        do {
            value = evaluatedValue;
            evaluatedValue = value.replace(regexp, replacementFnc);
        } while (value !== evaluatedValue);
        return evaluatedValue;
    }
    value = iterativeReplace(value, /'([^']+)'/g, javascriptReplacement);
    value = iterativeReplace(value, /@\{([\w-]+)\}/g, interpolationReplacement);
    return new Quoted(this.quote + value + this.quote, value, this.escaped, this.index, this.currentFileInfo);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Quoted.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Quoted.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Quoted.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    if (!this.escaped) {
        output.add(this.quote, this.currentFileInfo, this.index);
    }
    output.add(this.value);
    if (!this.escaped) {
        output.add(this.quote);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Rule"></a>[module less.tree.Rule](#apidoc.module.less.tree.Rule)

#### <a name="apidoc.element.less.tree.Rule.Rule"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Rule (name, value, important, merge, index, currentFileInfo, inline, variable)](#apidoc.element.less.tree.Rule.Rule)
- description and source-code
```javascript
Rule = function (name, value, important, merge, index, currentFileInfo, inline, variable) {
    this.name = name;
    this.value = (value instanceof Node) ? value : new Value([value]); //value instanceof tree.Value || value instanceof tree.Ruleset
 ??
    this.important = important ? ' ' + important.trim() : '';
    this.merge = merge;
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.inline = inline || false;
    this.variable = (variable !== undefined) ? variable
        : (name.charAt && (name.charAt(0) === '@'));
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Rule.prototype"></a>[module less.tree.Rule.prototype](#apidoc.module.less.tree.Rule.prototype)

#### <a name="apidoc.element.less.tree.Rule.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>eval (context)](#apidoc.element.less.tree.Rule.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var strictMathBypass = false, name = this.name, evaldValue, variable = this.variable;
    if (typeof name !== "string") {
        // expand 'primitive' name directly to get
        // things faster (~10% for benchmark.less):
        name = (name.length === 1) && (name[0] instanceof Keyword) ?
                name[0].value : evalName(context, name);
        variable = false; // never treat expanded interpolation as new variable name
    }
    if (name === "font" && !context.strictMath) {
        strictMathBypass = true;
        context.strictMath = true;
    }
    try {
        context.importantScope.push({});
        evaldValue = this.value.eval(context);

        if (!this.variable && evaldValue.type === "DetachedRuleset") {
            throw { message: "Rulesets cannot be evaluated on a property.",
                    index: this.index, filename: this.currentFileInfo.filename };
        }
        var important = this.important,
            importantResult = context.importantScope.pop();
        if (!important && importantResult.important) {
            important = importantResult.important;
        }

        return new Rule(name,
                          evaldValue,
                          important,
                          this.merge,
                          this.index, this.currentFileInfo, this.inline,
                              variable);
    }
    catch(e) {
        if (typeof e.index !== 'number') {
            e.index = this.index;
            e.filename = this.currentFileInfo.filename;
        }
        throw e;
    }
    finally {
        if (strictMathBypass) {
            context.strictMath = false;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Rule.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Rule.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add(this.name + (context.compress ? ':' : ': '), this.currentFileInfo, this.index);
    try {
        this.value.genCSS(context, output);
    }
    catch(e) {
        e.index = this.index;
        e.filename = this.currentFileInfo.filename;
        throw e;
    }
    output.add(this.important + ((this.inline || (context.lastRule && context.compress)) ? "" : ";"), this.currentFileInfo, this
.index);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Rule.prototype.makeImportant"></a>[function <span class="apidocSignatureSpan">less.tree.Rule.prototype.</span>makeImportant ()](#apidoc.element.less.tree.Rule.prototype.makeImportant)
- description and source-code
```javascript
makeImportant = function () {
    return new Rule(this.name,
                          this.value,
                          "!important",
                          this.merge,
                          this.index, this.currentFileInfo, this.inline);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Ruleset"></a>[module less.tree.Ruleset](#apidoc.module.less.tree.Ruleset)

#### <a name="apidoc.element.less.tree.Ruleset.Ruleset"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Ruleset (selectors, rules, strictImports, visibilityInfo)](#apidoc.element.less.tree.Ruleset.Ruleset)
- description and source-code
```javascript
Ruleset = function (selectors, rules, strictImports, visibilityInfo) {
    this.selectors = selectors;
    this.rules = rules;
    this._lookups = {};
    this.strictImports = strictImports;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Ruleset.prototype"></a>[module less.tree.Ruleset.prototype](#apidoc.module.less.tree.Ruleset.prototype)

#### <a name="apidoc.element.less.tree.Ruleset.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Ruleset.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.paths) {
        this.paths = visitor.visitArray(this.paths, true);
    } else if (this.selectors) {
        this.selectors = visitor.visitArray(this.selectors);
    }
    if (this.rules && this.rules.length) {
        this.rules = visitor.visitArray(this.rules);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>eval (context)](#apidoc.element.less.tree.Ruleset.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var thisSelectors = this.selectors, selectors,
        selCnt, selector, i, hasOnePassingSelector = false;

    if (thisSelectors && (selCnt = thisSelectors.length)) {
        selectors = [];
        defaultFunc.error({
            type: "Syntax",
            message: "it is currently only allowed in parametric mixin guards,"
        });
        for (i = 0; i < selCnt; i++) {
            selector = thisSelectors[i].eval(context);
            selectors.push(selector);
            if (selector.evaldCondition) {
                hasOnePassingSelector = true;
            }
        }
        defaultFunc.reset();
    } else {
        hasOnePassingSelector = true;
    }

    var rules = this.rules ? this.rules.slice(0) : null,
        ruleset = new Ruleset(selectors, rules, this.strictImports, this.visibilityInfo()),
        rule, subRule;

    ruleset.originalRuleset = this;
    ruleset.root = this.root;
    ruleset.firstRoot = this.firstRoot;
    ruleset.allowImports = this.allowImports;

    if (this.debugInfo) {
        ruleset.debugInfo = this.debugInfo;
    }

    if (!hasOnePassingSelector) {
        rules.length = 0;
    }

    // inherit a function registry from the frames stack when possible;
    // otherwise from the global registry
    ruleset.functionRegistry = (function (frames) {
        var i = 0,
            n = frames.length,
            found;
        for ( ; i !== n ; ++i ) {
            found = frames[ i ].functionRegistry;
            if ( found ) { return found; }
        }
        return globalFunctionRegistry;
    }(context.frames)).inherit();

    // push the current ruleset to the frames stack
    var ctxFrames = context.frames;
    ctxFrames.unshift(ruleset);

    // currrent selectors
    var ctxSelectors = context.selectors;
    if (!ctxSelectors) {
        context.selectors = ctxSelectors = [];
    }
    ctxSelectors.unshift(this.selectors);

    // Evaluate imports
    if (ruleset.root || ruleset.allowImports || !ruleset.strictImports) {
        ruleset.evalImports(context);
    }

    // Store the frames around mixin definitions,
    // so they can be evaluated like closures when the time comes.
    var rsRules = ruleset.rules, rsRuleCnt = rsRules ? rsRules.length : 0;
    for (i = 0; i < rsRuleCnt; i++) {
        if (rsRules[i].evalFirst) {
            rsRules[i] = rsRules[i].eval(context);
        }
    }

    var mediaBlockCount = (context.mediaBlocks && context.mediaBlocks.length) || 0;

    // Evaluate mixin calls.
    for (i = 0; i < rsRuleCnt; i++) {
        if (rsRules[i].type === "MixinCall") {
<span class="apidocCodeCommentSpan">            /*jshint loopfunc:true */
</span>            rules = rsRules[i].eval(context).filter(function(r) {
                if ((r instanceof Rule) && r.variable) {
                    // do not pollute the scope if the variable is
                    // already there. consider returning false here
                    // but we need a way to "return" variable from mixins
                    return !(ruleset.variable(r.name));
                }
                return true;
            });
            rsRules.splice.apply(rsRules, [i, 1].concat(rules));
            rsRuleCnt += rules.length - 1;
            i += rules.length - 1;
            ruleset.resetCache();
        } else if (rsRules[i].type === "RulesetCall") {
            /*jshint loopfunc:true */
            rules = rsRules[i].eval(context).rules.filter(function(r) {
                if ((r instanceof Rule) && r.variable) {
                    // do not pollute the scope at all
                    return false;
                }
                return true;
            });
            rsRules.splice.apply(rsRules, [i, 1].concat(rules));
            rsRuleCnt += rules.length - 1;
            i += rules.length - 1;
            ruleset.resetCache();
        }
    }

    // Evaluate everything else
    for (i = 0; i < rsRules.length; i++) {
        rule = rsRules[i];
        if (!rule.evalFirst) {
            rsRules[i] = rule = rule.eval ? rule.eval(context) : rule;
        }
    }

    // Evaluate everything else
    for ( ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.evalImports"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>evalImports (context)](#apidoc.element.less.tree.Ruleset.prototype.evalImports)
- description and source-code
```javascript
evalImports = function (context) {
    var rules = this.rules, i, importRules;
    if (!rules) { return; }

    for (i = 0; i < rules.length; i++) {
        if (rules[i].type === "Import") {
            importRules = rules[i].eval(context);
            if (importRules && (importRules.length || importRules.length === 0)) {
                rules.splice.apply(rules, [i, 1].concat(importRules));
                i+= importRules.length - 1;
            } else {
                rules.splice(i, 1, importRules);
            }
            this.resetCache();
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.find"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>find (selector, self, filter)](#apidoc.element.less.tree.Ruleset.prototype.find)
- description and source-code
```javascript
find = function (selector, self, filter) {
    self = self || this;
    var rules = [], match, foundMixins,
        key = selector.toCSS();

    if (key in this._lookups) { return this._lookups[key]; }

    this.rulesets().forEach(function (rule) {
        if (rule !== self) {
            for (var j = 0; j < rule.selectors.length; j++) {
                match = selector.match(rule.selectors[j]);
                if (match) {
                    if (selector.elements.length > match) {
                        if (!filter || filter(rule)) {
                            foundMixins = rule.find(new Selector(selector.elements.slice(match)), self, filter);
                            for (var i = 0; i < foundMixins.length; ++i) {
                                foundMixins[i].path.push(rule);
                            }
                            Array.prototype.push.apply(rules, foundMixins);
                        }
                    } else {
                        rules.push({ rule: rule, path: []});
                    }
                    break;
                }
            }
        }
    });
    this._lookups[key] = rules;
    return rules;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Ruleset.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    var i, j,
        charsetRuleNodes = [],
        ruleNodes = [],
        debugInfo,     // Line number debugging
        rule,
        path;

    context.tabLevel = (context.tabLevel || 0);

    if (!this.root) {
        context.tabLevel++;
    }

    var tabRuleStr = context.compress ? '' : Array(context.tabLevel + 1).join("  "),
        tabSetStr = context.compress ? '' : Array(context.tabLevel).join("  "),
        sep;

    function isRulesetLikeNode(rule) {
        // if it has nested rules, then it should be treated like a ruleset
        // medias and comments do not have nested rules, but should be treated like rulesets anyway
        // some directives and anonymous nodes are ruleset like, others are not
        if (typeof rule.isRulesetLike === "boolean") {
            return rule.isRulesetLike;
        } else if (typeof rule.isRulesetLike === "function") {
            return rule.isRulesetLike();
        }

        //anything else is assumed to be a rule
        return false;
    }

    var charsetNodeIndex = 0;
    var importNodeIndex = 0;
    for (i = 0; i < this.rules.length; i++) {
        rule = this.rules[i];
        if (rule.type === "Comment") {
            if (importNodeIndex === i) {
                importNodeIndex++;
            }
            ruleNodes.push(rule);
        } else if (rule.isCharset && rule.isCharset()) {
            ruleNodes.splice(charsetNodeIndex, 0, rule);
            charsetNodeIndex++;
            importNodeIndex++;
        } else if (rule.type === "Import") {
            ruleNodes.splice(importNodeIndex, 0, rule);
            importNodeIndex++;
        } else {
            ruleNodes.push(rule);
        }
    }
    ruleNodes = charsetRuleNodes.concat(ruleNodes);

    // If this is the root node, we don't render
    // a selector, or {}.
    if (!this.root) {
        debugInfo = getDebugInfo(context, this, tabSetStr);

        if (debugInfo) {
            output.add(debugInfo);
            output.add(tabSetStr);
        }

        var paths = this.paths, pathCnt = paths.length,
            pathSubCnt;

        sep = context.compress ? ',' : (',\n' + tabSetStr);

        for (i = 0; i < pathCnt; i++) {
            path = paths[i];
            if (!(pathSubCnt = path.length)) { continue; }
            if (i > 0) { output.add(sep); }

            context.firstSelector = true;
            path[0].genCSS(context, output);

            context.firstSelector = false;
            for (j = 1; j < pathSubCnt; j++) {
                path[j].genCSS(context, output);
            }
        }

        output.add((context.compress ? '{' : ' {\n') + tabRuleStr);
    }

    // Compile rules and rulesets
    for (i = 0; i < ruleNodes.length; i++) {
        rule = ruleNodes[i];

        if (i + 1 === ruleNodes.length) {
            context.lastRule = true;
        }

        var currentLastRule = context.lastRule;
        if (isRulesetLikeNode(rule)) {
            context.lastRule = false;
        }

        if (rule.genCSS) {
            rule.genCSS(context, output);
        } else if (rule.value) {
            output.add(rule.value.toString());
        }

        context.lastRule = currentLastRule;

        if (!context.lastRule) {
            output.add(context.compress ? '' : ('\n' + tabRuleStr));
        } else {
            context.lastRule = false;
        }
    }

    if (!this.root) {
        output.add((context.compress ? '}' : '\n' + tabSetStr + '}'));
        context.tabLevel--;
    }

    if (!output.isEmpty() && !context.compress && this.firstRoot) {
        output.add('\n');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.joinSelector"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>joinSelector (paths, context, selector)](#apidoc.element.less.tree.Ruleset.prototype.joinSelector)
- description and source-code
```javascript
joinSelector = function (paths, context, selector) {

    function createParenthesis(elementsToPak, originalElement) {
        var replacementParen, j;
        if (elementsToPak.length === 0) {
            replacementParen = new Paren(elementsToPak[0]);
        } else {
            var insideParent = [];
            for (j = 0; j < elementsToPak.length; j++) {
                insideParent.push(new Element(null, elementsToPak[j], originalElement.index, originalElement.currentFileInfo));
            }
            replacementParen = new Paren(new Selector(insideParent));
        }
        return replacementParen;
    }

    function createSelector(containedElement, originalElement) {
        var element, selector;
        element = new Element(null, containedElement, originalElement.index, originalElement.currentFileInfo);
        selector = new Selector([element]);
        return selector;
    }

    // joins selector path from 'beginningPath' with selector path in 'addPath'
    // 'replacedElement' contains element that is being replaced by 'addPath'
    // returns concatenated path
    function addReplacementIntoPath(beginningPath, addPath, replacedElement, originalSelector) {
        var newSelectorPath, lastSelector, newJoinedSelector;
        // our new selector path
        newSelectorPath = [];

        //construct the joined selector - if & is the first thing this will be empty,
        // if not newJoinedSelector will be the last set of elements in the selector
        if (beginningPath.length > 0) {
            newSelectorPath = beginningPath.slice(0);
            lastSelector = newSelectorPath.pop();
            newJoinedSelector = originalSelector.createDerived(lastSelector.elements.slice(0));
        }
        else {
            newJoinedSelector = originalSelector.createDerived([]);
        }

        if (addPath.length > 0) {
            // /deep/ is a combinator that is valid without anything in front of it
            // so if the & does not have a combinator that is "" or " " then
            // and there is a combinator on the parent, then grab that.
            // this also allows + a { & .b { .a & { ... though not sure why you would want to do that
            var combinator = replacedElement.combinator, parentEl = addPath[0].elements[0];
            if (combinator.emptyOrWhitespace && !parentEl.combinator.emptyOrWhitespace) {
                combinator = parentEl.combinator;
            }
            // join the elements so far with the first part of the parent
            newJoinedSelector.elements.push(new Element(combinator, parentEl.value, replacedElement.index, replacedElement.currentFileInfo
));
            newJoinedSelector.elements = newJoinedSelector.elements.concat(addPath[0].elements.slice(1));
        }

        // now add the joined selector - but only if it is not empty
        if (newJoinedSelector.elements.length !== 0) {
            newSelectorPath.push(newJoinedSelector);
        }

        //put together the parent selectors after the join (e.g. the rest of the parent)
        if (addPath.length > 1) {
            var restOfPath = addPath.slice(1);
            restOfPath = restOfPath.map(function (selector) {
                return selector.createDerived(selector.elements, []);
            });
            newSelectorPath = newSelectorPath.concat(restOfPath);
        }
        return newSelectorPath;
    }

    // joins selector path from 'beginningPath' with every selector path in 'addPaths' array
    // 'replacedElement' contains element that is being replaced by 'addPath'
    // returns array with all concatenated paths
    function addAllReplacementsIntoPath( beginningPath, addPaths, replacedElement, originalSelector, result) {
        var j;
        for (j = 0; j < beginningPath.length; j++) {
            var newSelectorPath = addReplacementIntoPath(beginningPath[j], addPaths, replacedElement, originalSelector);
            result.push(newSelectorPath);
        }
        return result;
    }

    function mergeElementsOnToSelectors(elements, selectors) {
        var i, sel;

        if (elemen ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.joinSelectors"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>joinSelectors (paths, context, selectors)](#apidoc.element.less.tree.Ruleset.prototype.joinSelectors)
- description and source-code
```javascript
joinSelectors = function (paths, context, selectors) {
    for (var s = 0; s < selectors.length; s++) {
        this.joinSelector(paths, context, selectors[s]);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.makeImportant"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>makeImportant ()](#apidoc.element.less.tree.Ruleset.prototype.makeImportant)
- description and source-code
```javascript
makeImportant = function () {
    var result = new Ruleset(this.selectors, this.rules.map(function (r) {
        if (r.makeImportant) {
            return r.makeImportant();
        } else {
            return r;
        }
    }), this.strictImports, this.visibilityInfo());

    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.matchArgs"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>matchArgs (args)](#apidoc.element.less.tree.Ruleset.prototype.matchArgs)
- description and source-code
```javascript
matchArgs = function (args) {
    return !args || args.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.matchCondition"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>matchCondition (args, context)](#apidoc.element.less.tree.Ruleset.prototype.matchCondition)
- description and source-code
```javascript
matchCondition = function (args, context) {
    var lastSelector = this.selectors[this.selectors.length - 1];
    if (!lastSelector.evaldCondition) {
        return false;
    }
    if (lastSelector.condition &&
        !lastSelector.condition.eval(
            new contexts.Eval(context,
                context.frames))) {
        return false;
    }
    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.prependRule"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>prependRule (rule)](#apidoc.element.less.tree.Ruleset.prototype.prependRule)
- description and source-code
```javascript
prependRule = function (rule) {
    var rules = this.rules;
    if (rules) {
        rules.unshift(rule);
    } else {
        this.rules = [ rule ];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.resetCache"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>resetCache ()](#apidoc.element.less.tree.Ruleset.prototype.resetCache)
- description and source-code
```javascript
resetCache = function () {
    this._rulesets = null;
    this._variables = null;
    this._lookups = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.rulesets"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>rulesets ()](#apidoc.element.less.tree.Ruleset.prototype.rulesets)
- description and source-code
```javascript
rulesets = function () {
    if (!this.rules) { return []; }

    var filtRules = [], rules = this.rules, cnt = rules.length,
        i, rule;

    for (i = 0; i < cnt; i++) {
        rule = rules[i];
        if (rule.isRuleset) {
            filtRules.push(rule);
        }
    }

    return filtRules;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.variable"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>variable (name)](#apidoc.element.less.tree.Ruleset.prototype.variable)
- description and source-code
```javascript
variable = function (name) {
    return this.variables()[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Ruleset.prototype.variables"></a>[function <span class="apidocSignatureSpan">less.tree.Ruleset.prototype.</span>variables ()](#apidoc.element.less.tree.Ruleset.prototype.variables)
- description and source-code
```javascript
variables = function () {
    if (!this._variables) {
        this._variables = !this.rules ? {} : this.rules.reduce(function (hash, r) {
            if (r instanceof Rule && r.variable === true) {
                hash[r.name] = r;
            }
            // when evaluating variables in an import statement, imports have not been eval'd
            // so we need to go inside import statements.
            // guard against root being a string (in the case of inlined less)
            if (r.type === "Import" && r.root && r.root.variables) {
                var vars = r.root.variables();
                for (var name in vars) {
                    if (vars.hasOwnProperty(name)) {
                        hash[name] = vars[name];
                    }
                }
            }
            return hash;
        }, {});
    }
    return this._variables;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.RulesetCall"></a>[module less.tree.RulesetCall](#apidoc.module.less.tree.RulesetCall)

#### <a name="apidoc.element.less.tree.RulesetCall.RulesetCall"></a>[function <span class="apidocSignatureSpan">less.tree.</span>RulesetCall (variable)](#apidoc.element.less.tree.RulesetCall.RulesetCall)
- description and source-code
```javascript
RulesetCall = function (variable) {
    this.variable = variable;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.RulesetCall.prototype"></a>[module less.tree.RulesetCall.prototype](#apidoc.module.less.tree.RulesetCall.prototype)

#### <a name="apidoc.element.less.tree.RulesetCall.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.RulesetCall.prototype.</span>eval (context)](#apidoc.element.less.tree.RulesetCall.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var detachedRuleset = new Variable(this.variable).eval(context);
    return detachedRuleset.callEval(context);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Selector"></a>[module less.tree.Selector](#apidoc.module.less.tree.Selector)

#### <a name="apidoc.element.less.tree.Selector.Selector"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Selector (elements, extendList, condition, index, currentFileInfo, visibilityInfo)](#apidoc.element.less.tree.Selector.Selector)
- description and source-code
```javascript
Selector = function (elements, extendList, condition, index, currentFileInfo, visibilityInfo) {
    this.elements = elements;
    this.extendList = extendList;
    this.condition = condition;
    this.currentFileInfo = currentFileInfo || {};
    if (!condition) {
        this.evaldCondition = true;
    }
    this.copyVisibilityInfo(visibilityInfo);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Selector.prototype"></a>[module less.tree.Selector.prototype](#apidoc.module.less.tree.Selector.prototype)

#### <a name="apidoc.element.less.tree.Selector.prototype.CacheElements"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>CacheElements ()](#apidoc.element.less.tree.Selector.prototype.CacheElements)
- description and source-code
```javascript
CacheElements = function () {
    if (this._elements) {
        return;
    }

    var elements = this.elements.map( function(v) {
        return v.combinator.value + (v.value.value || v.value);
    }).join("").match(/[,&#\*\.\w-]([\w-]|(\\.))*/g);

    if (elements) {
        if (elements[0] === "&") {
            elements.shift();
        }
    } else {
        elements = [];
    }

    this._elements = elements;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Selector.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.elements) {
        this.elements = visitor.visitArray(this.elements);
    }
    if (this.extendList) {
        this.extendList = visitor.visitArray(this.extendList);
    }
    if (this.condition) {
        this.condition = visitor.visit(this.condition);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.createDerived"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>createDerived (elements, extendList, evaldCondition)](#apidoc.element.less.tree.Selector.prototype.createDerived)
- description and source-code
```javascript
createDerived = function (elements, extendList, evaldCondition) {
    var info = this.visibilityInfo();
    evaldCondition = (evaldCondition != null) ? evaldCondition : this.evaldCondition;
    var newSelector = new Selector(elements, extendList || this.extendList, null, this.index, this.currentFileInfo, info);
    newSelector.evaldCondition = evaldCondition;
    newSelector.mediaEmpty = this.mediaEmpty;
    return newSelector;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.createEmptySelectors"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>createEmptySelectors ()](#apidoc.element.less.tree.Selector.prototype.createEmptySelectors)
- description and source-code
```javascript
createEmptySelectors = function () {
    var el = new Element('', '&', this.index, this.currentFileInfo),
        sels = [new Selector([el], null, null, this.index, this.currentFileInfo)];
    sels[0].mediaEmpty = true;
    return sels;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>eval (context)](#apidoc.element.less.tree.Selector.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var evaldCondition = this.condition && this.condition.eval(context),
        elements = this.elements, extendList = this.extendList;

    elements = elements && elements.map(function (e) { return e.eval(context); });
    extendList = extendList && extendList.map(function(extend) { return extend.eval(context); });

    return this.createDerived(elements, extendList, evaldCondition);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Selector.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    var i, element;
    if ((!context || !context.firstSelector) && this.elements[0].combinator.value === "") {
        output.add(' ', this.currentFileInfo, this.index);
    }
    if (!this._css) {
        //TODO caching? speed comparison?
        for (i = 0; i < this.elements.length; i++) {
            element = this.elements[i];
            element.genCSS(context, output);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.getIsOutput"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>getIsOutput ()](#apidoc.element.less.tree.Selector.prototype.getIsOutput)
- description and source-code
```javascript
getIsOutput = function () {
    return this.evaldCondition;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.isJustParentSelector"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>isJustParentSelector ()](#apidoc.element.less.tree.Selector.prototype.isJustParentSelector)
- description and source-code
```javascript
isJustParentSelector = function () {
    return !this.mediaEmpty &&
        this.elements.length === 1 &&
        this.elements[0].value === '&' &&
        (this.elements[0].combinator.value === ' ' || this.elements[0].combinator.value === '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Selector.prototype.match"></a>[function <span class="apidocSignatureSpan">less.tree.Selector.prototype.</span>match (other)](#apidoc.element.less.tree.Selector.prototype.match)
- description and source-code
```javascript
match = function (other) {
    var elements = this.elements,
        len = elements.length,
        olen, i;

    other.CacheElements();

    olen = other._elements.length;
    if (olen === 0 || len < olen) {
        return 0;
    } else {
        for (i = 0; i < olen; i++) {
            if (elements[i].value !== other._elements[i]) {
                return 0;
            }
        }
    }

    return olen; // return number of matched elements
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.URL"></a>[module less.tree.URL](#apidoc.module.less.tree.URL)

#### <a name="apidoc.element.less.tree.URL.URL"></a>[function <span class="apidocSignatureSpan">less.tree.</span>URL (val, index, currentFileInfo, isEvald)](#apidoc.element.less.tree.URL.URL)
- description and source-code
```javascript
URL = function (val, index, currentFileInfo, isEvald) {
    this.value = val;
    this.currentFileInfo = currentFileInfo;
    this.index = index;
    this.isEvald = isEvald;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.URL.prototype"></a>[module less.tree.URL.prototype](#apidoc.module.less.tree.URL.prototype)

#### <a name="apidoc.element.less.tree.URL.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>accept (visitor)](#apidoc.element.less.tree.URL.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    this.value = visitor.visit(this.value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.URL.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>eval (context)](#apidoc.element.less.tree.URL.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var val = this.value.eval(context),
        rootpath;

    if (!this.isEvald) {
        // Add the base path if the URL is relative
        rootpath = this.currentFileInfo && this.currentFileInfo.rootpath;
        if (rootpath &&
            typeof val.value === "string" &&
            context.isPathRelative(val.value)) {

            if (!val.quote) {
                rootpath = rootpath.replace(/[\(\)'"\s]/g, function(match) { return "\\" + match; });
            }
            val.value = rootpath + val.value;
        }

        val.value = context.normalizePath(val.value);

        // Add url args if enabled
        if (context.urlArgs) {
            if (!val.value.match(/^\s*data:/)) {
                var delimiter = val.value.indexOf('?') === -1 ? '?' : '&';
                var urlArgs = delimiter + context.urlArgs;
                if (val.value.indexOf('#') !== -1) {
                    val.value = val.value.replace('#', urlArgs + '#');
                } else {
                    val.value += urlArgs;
                }
            }
        }
    }

    return new URL(val, this.index, this.currentFileInfo, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.URL.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.URL.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.URL.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    output.add("url(");
    this.value.genCSS(context, output);
    output.add(")");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Unit"></a>[module less.tree.Unit](#apidoc.module.less.tree.Unit)

#### <a name="apidoc.element.less.tree.Unit.Unit"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Unit (numerator, denominator, backupUnit)](#apidoc.element.less.tree.Unit.Unit)
- description and source-code
```javascript
Unit = function (numerator, denominator, backupUnit) {
    this.numerator = numerator ? numerator.slice(0).sort() : [];
    this.denominator = denominator ? denominator.slice(0).sort() : [];
    if (backupUnit) {
        this.backupUnit = backupUnit;
    } else if (numerator && numerator.length) {
        this.backupUnit = numerator[0];
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Unit.prototype"></a>[module less.tree.Unit.prototype](#apidoc.module.less.tree.Unit.prototype)

#### <a name="apidoc.element.less.tree.Unit.prototype.cancel"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>cancel ()](#apidoc.element.less.tree.Unit.prototype.cancel)
- description and source-code
```javascript
cancel = function () {
    var counter = {}, atomicUnit, i;

    for (i = 0; i < this.numerator.length; i++) {
        atomicUnit = this.numerator[i];
        counter[atomicUnit] = (counter[atomicUnit] || 0) + 1;
    }

    for (i = 0; i < this.denominator.length; i++) {
        atomicUnit = this.denominator[i];
        counter[atomicUnit] = (counter[atomicUnit] || 0) - 1;
    }

    this.numerator = [];
    this.denominator = [];

    for (atomicUnit in counter) {
        if (counter.hasOwnProperty(atomicUnit)) {
            var count = counter[atomicUnit];

            if (count > 0) {
                for (i = 0; i < count; i++) {
                    this.numerator.push(atomicUnit);
                }
            } else if (count < 0) {
                for (i = 0; i < -count; i++) {
                    this.denominator.push(atomicUnit);
                }
            }
        }
    }

    this.numerator.sort();
    this.denominator.sort();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.clone"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>clone ()](#apidoc.element.less.tree.Unit.prototype.clone)
- description and source-code
```javascript
clone = function () {
    return new Unit(this.numerator.slice(0), this.denominator.slice(0), this.backupUnit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.compare"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>compare (other)](#apidoc.element.less.tree.Unit.prototype.compare)
- description and source-code
```javascript
compare = function (other) {
    return this.is(other.toString()) ? 0 : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Unit.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    // Dimension checks the unit is singular and throws an error if in strict math mode.
    var strictUnits = context && context.strictUnits;
    if (this.numerator.length === 1) {
        output.add(this.numerator[0]); // the ideal situation
    } else if (!strictUnits && this.backupUnit) {
        output.add(this.backupUnit);
    } else if (!strictUnits && this.denominator.length) {
        output.add(this.denominator[0]);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.is"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>is (unitString)](#apidoc.element.less.tree.Unit.prototype.is)
- description and source-code
```javascript
is = function (unitString) {
    return this.toString().toUpperCase() === unitString.toUpperCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isEmpty ()](#apidoc.element.less.tree.Unit.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
    return this.numerator.length === 0 && this.denominator.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.isLength"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isLength ()](#apidoc.element.less.tree.Unit.prototype.isLength)
- description and source-code
```javascript
isLength = function () {
    return Boolean(this.toCSS().match(/px|em|%|in|cm|mm|pc|pt|ex/));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.isSingular"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>isSingular ()](#apidoc.element.less.tree.Unit.prototype.isSingular)
- description and source-code
```javascript
isSingular = function () {
    return this.numerator.length <= 1 && this.denominator.length === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.map"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>map (callback)](#apidoc.element.less.tree.Unit.prototype.map)
- description and source-code
```javascript
map = function (callback) {
    var i;

    for (i = 0; i < this.numerator.length; i++) {
        this.numerator[i] = callback(this.numerator[i], false);
    }

    for (i = 0; i < this.denominator.length; i++) {
        this.denominator[i] = callback(this.denominator[i], true);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.toString"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>toString ()](#apidoc.element.less.tree.Unit.prototype.toString)
- description and source-code
```javascript
toString = function () {
    var i, returnStr = this.numerator.join("*");
    for (i = 0; i < this.denominator.length; i++) {
        returnStr += "/" + this.denominator[i];
    }
    return returnStr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Unit.prototype.usedUnits"></a>[function <span class="apidocSignatureSpan">less.tree.Unit.prototype.</span>usedUnits ()](#apidoc.element.less.tree.Unit.prototype.usedUnits)
- description and source-code
```javascript
usedUnits = function () {
    var group, result = {}, mapUnit, groupName;

    mapUnit = function (atomicUnit) {
<span class="apidocCodeCommentSpan">        /*jshint loopfunc:true */
</span>        if (group.hasOwnProperty(atomicUnit) && !result[groupName]) {
            result[groupName] = atomicUnit;
        }

        return atomicUnit;
    };

    for (groupName in unitConversions) {
        if (unitConversions.hasOwnProperty(groupName)) {
            group = unitConversions[groupName];

            this.map(mapUnit);
        }
    }

    return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Value"></a>[module less.tree.Value](#apidoc.module.less.tree.Value)

#### <a name="apidoc.element.less.tree.Value.Value"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Value (value)](#apidoc.element.less.tree.Value.Value)
- description and source-code
```javascript
Value = function (value) {
    this.value = value;
    if (!value) {
        throw new Error("Value requires an array argument");
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Value.prototype"></a>[module less.tree.Value.prototype](#apidoc.module.less.tree.Value.prototype)

#### <a name="apidoc.element.less.tree.Value.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>accept (visitor)](#apidoc.element.less.tree.Value.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.value) {
        this.value = visitor.visitArray(this.value);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Value.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>eval (context)](#apidoc.element.less.tree.Value.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    if (this.value.length === 1) {
        return this.value[0].eval(context);
    } else {
        return new Value(this.value.map(function (v) {
            return v.eval(context);
        }));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Value.prototype.genCSS"></a>[function <span class="apidocSignatureSpan">less.tree.Value.prototype.</span>genCSS (context, output)](#apidoc.element.less.tree.Value.prototype.genCSS)
- description and source-code
```javascript
genCSS = function (context, output) {
    var i;
    for (i = 0; i < this.value.length; i++) {
        this.value[i].genCSS(context, output);
        if (i + 1 < this.value.length) {
            output.add((context && context.compress) ? ',' : ', ');
        }
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Variable"></a>[module less.tree.Variable](#apidoc.module.less.tree.Variable)

#### <a name="apidoc.element.less.tree.Variable.Variable"></a>[function <span class="apidocSignatureSpan">less.tree.</span>Variable (name, index, currentFileInfo)](#apidoc.element.less.tree.Variable.Variable)
- description and source-code
```javascript
Variable = function (name, index, currentFileInfo) {
    this.name = name;
    this.index = index;
    this.currentFileInfo = currentFileInfo || {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.Variable.prototype"></a>[module less.tree.Variable.prototype](#apidoc.module.less.tree.Variable.prototype)

#### <a name="apidoc.element.less.tree.Variable.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.Variable.prototype.</span>eval (context)](#apidoc.element.less.tree.Variable.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var variable, name = this.name;

    if (name.indexOf('@@') === 0) {
        name = '@' + new Variable(name.slice(1), this.index, this.currentFileInfo).eval(context).value;
    }

    if (this.evaluating) {
        throw { type: 'Name',
                message: "Recursive variable definition for " + name,
                filename: this.currentFileInfo.filename,
                index: this.index };
    }

    this.evaluating = true;

    variable = this.find(context.frames, function (frame) {
        var v = frame.variable(name);
        if (v) {
            if (v.important) {
                var importantScope = context.importantScope[context.importantScope.length - 1];
                importantScope.important = v.important;
            }
            return v.value.eval(context);
        }
    });
    if (variable) {
        this.evaluating = false;
        return variable;
    } else {
        throw { type: 'Name',
                message: "variable " + name + " is undefined",
                filename: this.currentFileInfo.filename,
                index: this.index };
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.Variable.prototype.find"></a>[function <span class="apidocSignatureSpan">less.tree.Variable.prototype.</span>find (obj, fun)](#apidoc.element.less.tree.Variable.prototype.find)
- description and source-code
```javascript
find = function (obj, fun) {
    for (var i = 0, r; i < obj.length; i++) {
        r = fun.call(obj, obj[i]);
        if (r) { return r; }
    }
    return null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.mixin"></a>[module less.tree.mixin](#apidoc.module.less.tree.mixin)

#### <a name="apidoc.element.less.tree.mixin.Call"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.</span>Call (elements, args, index, currentFileInfo, important)](#apidoc.element.less.tree.mixin.Call)
- description and source-code
```javascript
Call = function (elements, args, index, currentFileInfo, important) {
    this.selector = new Selector(elements);
    this.arguments = args || [];
    this.index = index;
    this.currentFileInfo = currentFileInfo;
    this.important = important;
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.</span>Definition (name, params, rules, condition, variadic, frames, visibilityInfo)](#apidoc.element.less.tree.mixin.Definition)
- description and source-code
```javascript
Definition = function (name, params, rules, condition, variadic, frames, visibilityInfo) {
    this.name = name;
    this.selectors = [new Selector([new Element(null, name, this.index, this.currentFileInfo)])];
    this.params = params;
    this.condition = condition;
    this.variadic = variadic;
    this.arity = params.length;
    this.rules = rules;
    this._lookups = {};
    var optionalParameters = [];
    this.required = params.reduce(function (count, p) {
        if (!p.name || (p.name && !p.value)) {
            return count + 1;
        }
        else {
            optionalParameters.push(p.name);
            return count;
        }
    }, 0);
    this.optionalParameters = optionalParameters;
    this.frames = frames;
    this.copyVisibilityInfo(visibilityInfo);
    this.allowRoot = true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.mixin.Call.prototype"></a>[module less.tree.mixin.Call.prototype](#apidoc.module.less.tree.mixin.Call.prototype)

#### <a name="apidoc.element.less.tree.mixin.Call.prototype._setVisibilityToReplacement"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>_setVisibilityToReplacement (replacement)](#apidoc.element.less.tree.mixin.Call.prototype._setVisibilityToReplacement)
- description and source-code
```javascript
_setVisibilityToReplacement = function (replacement) {
    var i, rule;
    if (this.blocksVisibility()) {
        for (i = 0; i < replacement.length; i++) {
            rule = replacement[i];
            rule.addVisibilityBlock();
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Call.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>accept (visitor)](#apidoc.element.less.tree.mixin.Call.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.selector) {
        this.selector = visitor.visit(this.selector);
    }
    if (this.arguments.length) {
        this.arguments = visitor.visitArray(this.arguments);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Call.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>eval (context)](#apidoc.element.less.tree.mixin.Call.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    var mixins, mixin, mixinPath, args = [], arg, argValue,
        rules = [], match = false, i, m, f, isRecursive, isOneFound,
        candidates = [], candidate, conditionResult = [], defaultResult, defFalseEitherCase = -1,
        defNone = 0, defTrue = 1, defFalse = 2, count, originalRuleset, noArgumentsFilter;

    function calcDefGroup(mixin, mixinPath) {
        var f, p, namespace;

        for (f = 0; f < 2; f++) {
            conditionResult[f] = true;
            defaultFunc.value(f);
            for (p = 0; p < mixinPath.length && conditionResult[f]; p++) {
                namespace = mixinPath[p];
                if (namespace.matchCondition) {
                    conditionResult[f] = conditionResult[f] && namespace.matchCondition(null, context);
                }
            }
            if (mixin.matchCondition) {
                conditionResult[f] = conditionResult[f] && mixin.matchCondition(args, context);
            }
        }
        if (conditionResult[0] || conditionResult[1]) {
            if (conditionResult[0] != conditionResult[1]) {
                return conditionResult[1] ?
                    defTrue : defFalse;
            }

            return defNone;
        }
        return defFalseEitherCase;
    }

    for (i = 0; i < this.arguments.length; i++) {
        arg = this.arguments[i];
        argValue = arg.value.eval(context);
        if (arg.expand && Array.isArray(argValue.value)) {
            argValue = argValue.value;
            for (m = 0; m < argValue.length; m++) {
                args.push({value: argValue[m]});
            }
        } else {
            args.push({name: arg.name, value: argValue});
        }
    }

    noArgumentsFilter = function(rule) {return rule.matchArgs(null, context);};

    for (i = 0; i < context.frames.length; i++) {
        if ((mixins = context.frames[i].find(this.selector, null, noArgumentsFilter)).length > 0) {
            isOneFound = true;

            // To make 'default()' function independent of definition order we have two "subpasses" here.
            // At first we evaluate each guard *twice* (with 'default() == true' and 'default() == false'),
            // and build candidate list with corresponding flags. Then, when we know all possible matches,
            // we make a final decision.

            for (m = 0; m < mixins.length; m++) {
                mixin = mixins[m].rule;
                mixinPath = mixins[m].path;
                isRecursive = false;
                for (f = 0; f < context.frames.length; f++) {
                    if ((!(mixin instanceof MixinDefinition)) && mixin === (context.frames[f].originalRuleset || context.frames[
f])) {
                        isRecursive = true;
                        break;
                    }
                }
                if (isRecursive) {
                    continue;
                }

                if (mixin.matchArgs(args, context)) {
                    candidate = {mixin: mixin, group: calcDefGroup(mixin, mixinPath)};

                    if (candidate.group !== defFalseEitherCase) {
                        candidates.push(candidate);
                    }

                    match = true;
                }
            }

            defaultFunc.reset();

            count = [0, 0, 0];
            for (m = 0; m < candidates.length; m++) {
                count[candidates[m].group]++;
            }

            if (count[defNone] > 0) {
                defaultResult = defFalse;
            } else {
                defaultResult = defTrue;
                if ((count[defTrue] + count[defFalse]) > 1) {
                    throw { type: 'Runtime',
                        message: 'Ambiguous use of 'default()' found when matching for '' + this.format(args) + ''',
                        index: this.index, filename: this.currentFileInfo.filename };
                }
            }

            for (m = 0; m < candidates.length; m++) {
                candidate = candidates[m].group;
                if ((candidate === defNone) || (candidate === defaultResu ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Call.prototype.format"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Call.prototype.</span>format (args)](#apidoc.element.less.tree.mixin.Call.prototype.format)
- description and source-code
```javascript
format = function (args) {
    return this.selector.toCSS().trim() + '(' +
        (args ? args.map(function (a) {
            var argValue = "";
            if (a.name) {
                argValue += a.name + ":";
            }
            if (a.value.toCSS) {
                argValue += a.value.toCSS();
            } else {
                argValue += "???";
            }
            return argValue;
        }).join(', ') : "") + ")";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.tree.mixin.Definition.prototype"></a>[module less.tree.mixin.Definition.prototype](#apidoc.module.less.tree.mixin.Definition.prototype)

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.accept"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>accept (visitor)](#apidoc.element.less.tree.mixin.Definition.prototype.accept)
- description and source-code
```javascript
accept = function (visitor) {
    if (this.params && this.params.length) {
        this.params = visitor.visitArray(this.params);
    }
    this.rules = visitor.visitArray(this.rules);
    if (this.condition) {
        this.condition = visitor.visit(this.condition);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.eval"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>eval (context)](#apidoc.element.less.tree.mixin.Definition.prototype.eval)
- description and source-code
```javascript
eval = function (context) {
    return new Definition(this.name, this.params, this.rules, this.condition, this.variadic, this.frames || context.frames.slice
(0));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.evalCall"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>evalCall (context, args, important)](#apidoc.element.less.tree.mixin.Definition.prototype.evalCall)
- description and source-code
```javascript
evalCall = function (context, args, important) {
    var _arguments = [],
        mixinFrames = this.frames ? this.frames.concat(context.frames) : context.frames,
        frame = this.evalParams(context, new contexts.Eval(context, mixinFrames), args, _arguments),
        rules, ruleset;

    frame.prependRule(new Rule('@arguments', new Expression(_arguments).eval(context)));

    rules = this.rules.slice(0);

    ruleset = new Ruleset(null, rules);
    ruleset.originalRuleset = this;
    ruleset = ruleset.eval(new contexts.Eval(context, [this, frame].concat(mixinFrames)));
    if (important) {
        ruleset = ruleset.makeImportant();
    }
    return ruleset;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.evalParams"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>evalParams (context, mixinEnv, args, evaldArguments)](#apidoc.element.less.tree.mixin.Definition.prototype.evalParams)
- description and source-code
```javascript
evalParams = function (context, mixinEnv, args, evaldArguments) {
<span class="apidocCodeCommentSpan">    /*jshint boss:true */
</span>    var frame = new Ruleset(null, null),
        varargs, arg,
        params = this.params.slice(0),
        i, j, val, name, isNamedFound, argIndex, argsLength = 0;

    if (mixinEnv.frames && mixinEnv.frames[0] && mixinEnv.frames[0].functionRegistry) {
        frame.functionRegistry = mixinEnv.frames[0].functionRegistry.inherit();
    }
    mixinEnv = new contexts.Eval(mixinEnv, [frame].concat(mixinEnv.frames));

    if (args) {
        args = args.slice(0);
        argsLength = args.length;

        for (i = 0; i < argsLength; i++) {
            arg = args[i];
            if (name = (arg && arg.name)) {
                isNamedFound = false;
                for (j = 0; j < params.length; j++) {
                    if (!evaldArguments[j] && name === params[j].name) {
                        evaldArguments[j] = arg.value.eval(context);
                        frame.prependRule(new Rule(name, arg.value.eval(context)));
                        isNamedFound = true;
                        break;
                    }
                }
                if (isNamedFound) {
                    args.splice(i, 1);
                    i--;
                    continue;
                } else {
                    throw { type: 'Runtime', message: "Named argument for " + this.name +
                        ' ' + args[i].name + ' not found' };
                }
            }
        }
    }
    argIndex = 0;
    for (i = 0; i < params.length; i++) {
        if (evaldArguments[i]) { continue; }

        arg = args && args[argIndex];

        if (name = params[i].name) {
            if (params[i].variadic) {
                varargs = [];
                for (j = argIndex; j < argsLength; j++) {
                    varargs.push(args[j].value.eval(context));
                }
                frame.prependRule(new Rule(name, new Expression(varargs).eval(context)));
            } else {
                val = arg && arg.value;
                if (val) {
                    val = val.eval(context);
                } else if (params[i].value) {
                    val = params[i].value.eval(mixinEnv);
                    frame.resetCache();
                } else {
                    throw { type: 'Runtime', message: "wrong number of arguments for " + this.name +
                        ' (' + argsLength + ' for ' + this.arity + ')' };
                }

                frame.prependRule(new Rule(name, val));
                evaldArguments[i] = val;
            }
        }

        if (params[i].variadic && args) {
            for (j = argIndex; j < argsLength; j++) {
                evaldArguments[j] = args[j].value.eval(context);
            }
        }
        argIndex++;
    }

    return frame;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.makeImportant"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>makeImportant ()](#apidoc.element.less.tree.mixin.Definition.prototype.makeImportant)
- description and source-code
```javascript
makeImportant = function () {
    var rules = !this.rules ? this.rules : this.rules.map(function (r) {
        if (r.makeImportant) {
            return r.makeImportant(true);
        } else {
            return r;
        }
    });
    var result = new Definition(this.name, this.params, rules, this.condition, this.variadic, this.frames);
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.matchArgs"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>matchArgs (args, context)](#apidoc.element.less.tree.mixin.Definition.prototype.matchArgs)
- description and source-code
```javascript
matchArgs = function (args, context) {
    var allArgsCnt = (args && args.length) || 0, len, optionalParameters = this.optionalParameters;
    var requiredArgsCnt = !args ? 0 : args.reduce(function (count, p) {
        if (optionalParameters.indexOf(p.name) < 0) {
            return count + 1;
        } else {
            return count;
        }
    }, 0);

    if (! this.variadic) {
        if (requiredArgsCnt < this.required) {
            return false;
        }
        if (allArgsCnt > this.params.length) {
            return false;
        }
    } else {
        if (requiredArgsCnt < (this.required - 1)) {
            return false;
        }
    }

    // check patterns
    len = Math.min(requiredArgsCnt, this.arity);

    for (var i = 0; i < len; i++) {
        if (!this.params[i].name && !this.params[i].variadic) {
            if (args[i].value.eval(context).toCSS() != this.params[i].value.eval(context).toCSS()) {
                return false;
            }
        }
    }
    return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.tree.mixin.Definition.prototype.matchCondition"></a>[function <span class="apidocSignatureSpan">less.tree.mixin.Definition.prototype.</span>matchCondition (args, context)](#apidoc.element.less.tree.mixin.Definition.prototype.matchCondition)
- description and source-code
```javascript
matchCondition = function (args, context) {
    if (this.condition && !this.condition.eval(
        new contexts.Eval(context,
            [this.evalParams(context,<span class="apidocCodeCommentSpan"> /* the parameter variables*/
</span>                new contexts.Eval(context, this.frames ? this.frames.concat(context.frames) : context.frames), args, [])]
            .concat(this.frames || []) // the parent namespace/mixin frames
            .concat(context.frames)))) { // the current environment frames
        return false;
    }
    return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.utils"></a>[module less.utils](#apidoc.module.less.utils)

#### <a name="apidoc.element.less.utils.getLocation"></a>[function <span class="apidocSignatureSpan">less.utils.</span>getLocation (index, inputStream)](#apidoc.element.less.utils.getLocation)
- description and source-code
```javascript
getLocation = function (index, inputStream) {
    var n = index + 1,
        line = null,
        column = -1;

    while (--n >= 0 && inputStream.charAt(n) !== '\n') {
        column++;
    }

    if (typeof index === 'number') {
        line = (inputStream.slice(0, index).match(/\n/g) || "").length;
    }

    return {
        line: line,
        column: column
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors"></a>[module less.visitors](#apidoc.module.less.visitors)

#### <a name="apidoc.element.less.visitors.ExtendVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor)
- description and source-code
```javascript
ExtendVisitor = function () {
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor)
- description and source-code
```javascript
ImportVisitor = function (importer, finish) {

    this._visitor = new Visitor(this);
    this._importer = importer;
    this._finish = finish;
    this.context = new contexts.Eval();
    this.importCount = 0;
    this.onceFileDetectionMap = {};
    this.recursionDetector = {};
    this._sequencer = new ImportSequencer(this._onSequencerEmpty.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor)
- description and source-code
```javascript
JoinSelectorVisitor = function () {
    this.contexts = [[]];
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor)
- description and source-code
```javascript
MarkVisibleSelectorsVisitor = function (visible) {
    this.visible = visible;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor)
- description and source-code
```javascript
ToCSSVisitor = function (context) {
    this._visitor = new Visitor(this);
    this._context = context;
    this.utils = new CSSVisitorUtils(context);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.Visitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>Visitor (implementation)](#apidoc.element.less.visitors.Visitor)
- description and source-code
```javascript
Visitor = function (implementation) {
    this._implementation = implementation;
    this._visitFnCache = [];

    if (!_hasIndexed) {
        indexNodeTypes(tree, 1);
        _hasIndexed = true;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ExtendVisitor"></a>[module less.visitors.ExtendVisitor](#apidoc.module.less.visitors.ExtendVisitor)

#### <a name="apidoc.element.less.visitors.ExtendVisitor.ExtendVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ExtendVisitor ()](#apidoc.element.less.visitors.ExtendVisitor.ExtendVisitor)
- description and source-code
```javascript
ExtendVisitor = function () {
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ExtendVisitor.prototype"></a>[module less.visitors.ExtendVisitor.prototype](#apidoc.module.less.visitors.ExtendVisitor.prototype)

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.checkExtendsForNonMatched"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>checkExtendsForNonMatched (extendList)](#apidoc.element.less.visitors.ExtendVisitor.prototype.checkExtendsForNonMatched)
- description and source-code
```javascript
checkExtendsForNonMatched = function (extendList) {
    var indices = this.extendIndices;
    extendList.filter(function(extend) {
        return !extend.hasFoundMatches && extend.parent_ids.length == 1;
    }).forEach(function(extend) {
            var selector = "_unknown_";
            try {
                selector = extend.selector.toCSS({});
            }
            catch(_) {}

            if (!indices[extend.index + ' ' + selector]) {
                indices[extend.index + ' ' + selector] = true;
                logger.warn("extend '" + selector + "' has no matches");
            }
        });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.doExtendChaining"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>doExtendChaining (extendsList, extendsListTarget, iterationCount)](#apidoc.element.less.visitors.ExtendVisitor.prototype.doExtendChaining)
- description and source-code
```javascript
doExtendChaining = function (extendsList, extendsListTarget, iterationCount) {
    //
    // chaining is different from normal extension.. if we extend an extend then we are not just copying, altering
    // and pasting the selector we would do normally, but we are also adding an extend with the same target selector
    // this means this new extend can then go and alter other extends
    //
    // this method deals with all the chaining work - without it, extend is flat and doesn't work on other extend selectors
    // this is also the most expensive.. and a match on one selector can cause an extension of a selector we had already
    // processed if we look at each selector at a time, as is done in visitRuleset

    var extendIndex, targetExtendIndex, matches, extendsToAdd = [], newSelector, extendVisitor = this, selectorPath,
        extend, targetExtend, newExtend;

    iterationCount = iterationCount || 0;

    //loop through comparing every extend with every target extend.
    // a target extend is the one on the ruleset we are looking at copy/edit/pasting in place
    // e.g.  .a:extend(.b) {}  and .b:extend(.c) {} then the first extend extends the second one
    // and the second is the target.
    // the separation into two lists allows us to process a subset of chains with a bigger set, as is the
    // case when processing media queries
    for (extendIndex = 0; extendIndex < extendsList.length; extendIndex++) {
        for (targetExtendIndex = 0; targetExtendIndex < extendsListTarget.length; targetExtendIndex++) {

            extend = extendsList[extendIndex];
            targetExtend = extendsListTarget[targetExtendIndex];

            // look for circular references
            if ( extend.parent_ids.indexOf( targetExtend.object_id ) >= 0 ) { continue; }

            // find a match in the target extends self selector (the bit before :extend)
            selectorPath = [targetExtend.selfSelectors[0]];
            matches = extendVisitor.findMatch(extend, selectorPath);

            if (matches.length) {
                extend.hasFoundMatches = true;

                // we found a match, so for each self selector..
                extend.selfSelectors.forEach(function(selfSelector) {
                    var info = targetExtend.visibilityInfo();

                    // process the extend as usual
                    newSelector = extendVisitor.extendSelector(matches, selectorPath, selfSelector, extend.isVisible());

                    // but now we create a new extend from it
                    newExtend = new(tree.Extend)(targetExtend.selector, targetExtend.option, 0, targetExtend.currentFileInfo, info
);
                    newExtend.selfSelectors = newSelector;

                    // add the extend onto the list of extends for that selector
                    newSelector[newSelector.length - 1].extendList = [newExtend];

                    // record that we need to add it.
                    extendsToAdd.push(newExtend);
                    newExtend.ruleset = targetExtend.ruleset;

                    //remember its parents for circular references
                    newExtend.parent_ids = newExtend.parent_ids.concat(targetExtend.parent_ids, extend.parent_ids);

                    // only process the selector once.. if we have :extend(.a,.b) then multiple
                    // extends will look at the same selector path, so when extending
                    // we know that any others will be duplicates in terms of what is added to the css
                    if (targetExtend.firstExtendOnThisSelectorPath) {
                        newExtend.firstExtendOnThisSelectorPath = true;
                        targetExtend.ruleset.paths.push(newSelector);
                    }
                });
            }
        }
    }

    if (extendsToAdd.length) {
        // try to detect circular references to stop a stack overflow.
        // may no longer be needed.
        this.extendChainCount++;
        if (iterationCount > 100) {
            var selectorOne = "{unable to calculate}";
            var selectorTwo = "{unable ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.extendSelector"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>extendSelector (matches, selectorPath, replacementSelector, isVisible)](#apidoc.element.less.visitors.ExtendVisitor.prototype.extendSelector)
- description and source-code
```javascript
extendSelector = function (matches, selectorPath, replacementSelector, isVisible) {

    //for a set of matches, replace each match with the replacement selector

    var currentSelectorPathIndex = 0,
        currentSelectorPathElementIndex = 0,
        path = [],
        matchIndex,
        selector,
        firstElement,
        match,
        newElements;

    for (matchIndex = 0; matchIndex < matches.length; matchIndex++) {
        match = matches[matchIndex];
        selector = selectorPath[match.pathIndex];
        firstElement = new tree.Element(
            match.initialCombinator,
            replacementSelector.elements[0].value,
            replacementSelector.elements[0].index,
            replacementSelector.elements[0].currentFileInfo
        );

        if (match.pathIndex > currentSelectorPathIndex && currentSelectorPathElementIndex > 0) {
            path[path.length - 1].elements = path[path.length - 1]
                .elements.concat(selectorPath[currentSelectorPathIndex].elements.slice(currentSelectorPathElementIndex));
            currentSelectorPathElementIndex = 0;
            currentSelectorPathIndex++;
        }

        newElements = selector.elements
            .slice(currentSelectorPathElementIndex, match.index)
            .concat([firstElement])
            .concat(replacementSelector.elements.slice(1));

        if (currentSelectorPathIndex === match.pathIndex && matchIndex > 0) {
            path[path.length - 1].elements =
                path[path.length - 1].elements.concat(newElements);
        } else {
            path = path.concat(selectorPath.slice(currentSelectorPathIndex, match.pathIndex));

            path.push(new tree.Selector(
                newElements
            ));
        }
        currentSelectorPathIndex = match.endPathIndex;
        currentSelectorPathElementIndex = match.endPathElementIndex;
        if (currentSelectorPathElementIndex >= selectorPath[currentSelectorPathIndex].elements.length) {
            currentSelectorPathElementIndex = 0;
            currentSelectorPathIndex++;
        }
    }

    if (currentSelectorPathIndex < selectorPath.length && currentSelectorPathElementIndex > 0) {
        path[path.length - 1].elements = path[path.length - 1]
            .elements.concat(selectorPath[currentSelectorPathIndex].elements.slice(currentSelectorPathElementIndex));
        currentSelectorPathIndex++;
    }

    path = path.concat(selectorPath.slice(currentSelectorPathIndex, selectorPath.length));
    path = path.map(function (currentValue) {
        // we can re-use elements here, because the visibility property matters only for selectors
        var derived = currentValue.createDerived(currentValue.elements);
        if (isVisible) {
            derived.ensureVisibility();
        } else {
            derived.ensureInvisibility();
        }
        return derived;
    });
    return path;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.findMatch"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>findMatch (extend, haystackSelectorPath)](#apidoc.element.less.visitors.ExtendVisitor.prototype.findMatch)
- description and source-code
```javascript
findMatch = function (extend, haystackSelectorPath) {
    //
    // look through the haystack selector path to try and find the needle - extend.selector
    // returns an array of selector matches that can then be replaced
    //
    var haystackSelectorIndex, hackstackSelector, hackstackElementIndex, haystackElement,
        targetCombinator, i,
        extendVisitor = this,
        needleElements = extend.selector.elements,
        potentialMatches = [], potentialMatch, matches = [];

    // loop through the haystack elements
    for (haystackSelectorIndex = 0; haystackSelectorIndex < haystackSelectorPath.length; haystackSelectorIndex++) {
        hackstackSelector = haystackSelectorPath[haystackSelectorIndex];

        for (hackstackElementIndex = 0; hackstackElementIndex < hackstackSelector.elements.length; hackstackElementIndex++) {

            haystackElement = hackstackSelector.elements[hackstackElementIndex];

            // if we allow elements before our match we can add a potential match every time. otherwise only at the first element
.
            if (extend.allowBefore || (haystackSelectorIndex === 0 && hackstackElementIndex === 0)) {
                potentialMatches.push({pathIndex: haystackSelectorIndex, index: hackstackElementIndex, matched: 0,
                    initialCombinator: haystackElement.combinator});
            }

            for (i = 0; i < potentialMatches.length; i++) {
                potentialMatch = potentialMatches[i];

                // selectors add " " onto the first element. When we use & it joins the selectors together, but if we don't
                // then each selector in haystackSelectorPath has a space before it added in the toCSS phase. so we need to
                // work out what the resulting combinator will be
                targetCombinator = haystackElement.combinator.value;
                if (targetCombinator === '' && hackstackElementIndex === 0) {
                    targetCombinator = ' ';
                }

                // if we don't match, null our match to indicate failure
                if (!extendVisitor.isElementValuesEqual(needleElements[potentialMatch.matched].value, haystackElement.value) ||
                    (potentialMatch.matched > 0 && needleElements[potentialMatch.matched].combinator.value !== targetCombinator)) {
                    potentialMatch = null;
                } else {
                    potentialMatch.matched++;
                }

                // if we are still valid and have finished, test whether we have elements after and whether these are allowed
                if (potentialMatch) {
                    potentialMatch.finished = potentialMatch.matched === needleElements.length;
                    if (potentialMatch.finished &&
                        (!extend.allowAfter &&
                            (hackstackElementIndex + 1 < hackstackSelector.elements.length || haystackSelectorIndex + 1 < haystackSelectorPath
.length))) {
                        potentialMatch = null;
                    }
                }
                // if null we remove, if not, we are still valid, so either push as a valid match or continue
                if (potentialMatch) {
                    if (potentialMatch.finished) {
                        potentialMatch.length = needleElements.length;
                        potentialMatch.endPathIndex = haystackSelectorIndex;
                        potentialMatch.endPathElementIndex = hackstackElementIndex + 1; // index after end of match
                        potentialMatches.length = 0; // we don't allow matches to overlap, so start matching again
                        matches.push(potentialMatch);
                    }
                } else {
                    potentialMatches.splice(i, 1);
                    i--;
                }
            }
        }
    }
    return matches;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.isElementValuesEqual"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>isElementValuesEqual (elementValue1, elementValue2)](#apidoc.element.less.visitors.ExtendVisitor.prototype.isElementValuesEqual)
- description and source-code
```javascript
isElementValuesEqual = function (elementValue1, elementValue2) {
    if (typeof elementValue1 === "string" || typeof elementValue2 === "string") {
        return elementValue1 === elementValue2;
    }
    if (elementValue1 instanceof tree.Attribute) {
        if (elementValue1.op !== elementValue2.op || elementValue1.key !== elementValue2.key) {
            return false;
        }
        if (!elementValue1.value || !elementValue2.value) {
            if (elementValue1.value || elementValue2.value) {
                return false;
            }
            return true;
        }
        elementValue1 = elementValue1.value.value || elementValue1.value;
        elementValue2 = elementValue2.value.value || elementValue2.value;
        return elementValue1 === elementValue2;
    }
    elementValue1 = elementValue1.value;
    elementValue2 = elementValue2.value;
    if (elementValue1 instanceof tree.Selector) {
        if (!(elementValue2 instanceof tree.Selector) || elementValue1.elements.length !== elementValue2.elements.length) {
            return false;
        }
        for (var i = 0; i  < elementValue1.elements.length; i++) {
            if (elementValue1.elements[i].combinator.value !== elementValue2.elements[i].combinator.value) {
                if (i !== 0 || (elementValue1.elements[i].combinator.value || ' ') !== (elementValue2.elements[i].combinator.value
 || ' ')) {
                    return false;
                }
            }
            if (!this.isElementValuesEqual(elementValue1.elements[i].value, elementValue2.elements[i].value)) {
                return false;
            }
        }
        return true;
    }
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.run"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ExtendVisitor.prototype.run)
- description and source-code
```javascript
run = function (root) {
    var extendFinder = new ExtendFinderVisitor();
    this.extendIndices = {};
    extendFinder.run(root);
    if (!extendFinder.foundExtends) { return root; }
    root.allExtends = root.allExtends.concat(this.doExtendChaining(root.allExtends, root.allExtends));
    this.allExtendsStack = [root.allExtends];
    var newRoot = this._visitor.visit(root);
    this.checkExtendsForNonMatched(root.allExtends);
    return newRoot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirective"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirective)
- description and source-code
```javascript
visitDirective = function (directiveNode, visitArgs) {
    var newAllExtends = directiveNode.allExtends.concat(this.allExtendsStack[this.allExtendsStack.length - 1]);
    newAllExtends = newAllExtends.concat(this.doExtendChaining(newAllExtends, directiveNode.allExtends));
    this.allExtendsStack.push(newAllExtends);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirectiveOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitDirectiveOut (directiveNode)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitDirectiveOut)
- description and source-code
```javascript
visitDirectiveOut = function (directiveNode) {
    var lastIndex = this.allExtendsStack.length - 1;
    this.allExtendsStack.length = lastIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitMedia"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMedia)
- description and source-code
```javascript
visitMedia = function (mediaNode, visitArgs) {
    var newAllExtends = mediaNode.allExtends.concat(this.allExtendsStack[this.allExtendsStack.length - 1]);
    newAllExtends = newAllExtends.concat(this.doExtendChaining(newAllExtends, mediaNode.allExtends));
    this.allExtendsStack.push(newAllExtends);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitMediaOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMediaOut (mediaNode)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMediaOut)
- description and source-code
```javascript
visitMediaOut = function (mediaNode) {
    var lastIndex = this.allExtendsStack.length - 1;
    this.allExtendsStack.length = lastIndex;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitMixinDefinition"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitMixinDefinition)
- description and source-code
```javascript
visitMixinDefinition = function (mixinDefinitionNode, visitArgs) {
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitRule"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitRule)
- description and source-code
```javascript
visitRule = function (ruleNode, visitArgs) {
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitRuleset"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitRuleset)
- description and source-code
```javascript
visitRuleset = function (rulesetNode, visitArgs) {
    if (rulesetNode.root) {
        return;
    }
    var matches, pathIndex, extendIndex, allExtends = this.allExtendsStack[this.allExtendsStack.length - 1],
        selectorsToAdd = [], extendVisitor = this, selectorPath;

    // look at each selector path in the ruleset, find any extend matches and then copy, find and replace

    for (extendIndex = 0; extendIndex < allExtends.length; extendIndex++) {
        for (pathIndex = 0; pathIndex < rulesetNode.paths.length; pathIndex++) {
            selectorPath = rulesetNode.paths[pathIndex];

            // extending extends happens initially, before the main pass
            if (rulesetNode.extendOnEveryPath) { continue; }
            var extendList = selectorPath[selectorPath.length - 1].extendList;
            if (extendList && extendList.length) { continue; }

            matches = this.findMatch(allExtends[extendIndex], selectorPath);

            if (matches.length) {
                allExtends[extendIndex].hasFoundMatches = true;

                allExtends[extendIndex].selfSelectors.forEach(function(selfSelector) {
                    var extendedSelectors;
                    extendedSelectors = extendVisitor.extendSelector(matches, selectorPath, selfSelector, allExtends[extendIndex
].isVisible());
                    selectorsToAdd.push(extendedSelectors);
                });
            }
        }
    }
    rulesetNode.paths = rulesetNode.paths.concat(selectorsToAdd);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ExtendVisitor.prototype.visitSelector"></a>[function <span class="apidocSignatureSpan">less.visitors.ExtendVisitor.prototype.</span>visitSelector (selectorNode, visitArgs)](#apidoc.element.less.visitors.ExtendVisitor.prototype.visitSelector)
- description and source-code
```javascript
visitSelector = function (selectorNode, visitArgs) {
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ImportVisitor"></a>[module less.visitors.ImportVisitor](#apidoc.module.less.visitors.ImportVisitor)

#### <a name="apidoc.element.less.visitors.ImportVisitor.ImportVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ImportVisitor (importer, finish)](#apidoc.element.less.visitors.ImportVisitor.ImportVisitor)
- description and source-code
```javascript
ImportVisitor = function (importer, finish) {

    this._visitor = new Visitor(this);
    this._importer = importer;
    this._finish = finish;
    this.context = new contexts.Eval();
    this.importCount = 0;
    this.onceFileDetectionMap = {};
    this.recursionDetector = {};
    this._sequencer = new ImportSequencer(this._onSequencerEmpty.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ImportVisitor.prototype"></a>[module less.visitors.ImportVisitor.prototype](#apidoc.module.less.visitors.ImportVisitor.prototype)

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype._onSequencerEmpty"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>_onSequencerEmpty ()](#apidoc.element.less.visitors.ImportVisitor.prototype._onSequencerEmpty)
- description and source-code
```javascript
_onSequencerEmpty = function () {
    if (!this.isFinished) {
        return;
    }
    this._finish(this.error);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.onImported"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>onImported (importNode, context, e, root, importedAtRoot, fullPath)](#apidoc.element.less.visitors.ImportVisitor.prototype.onImported)
- description and source-code
```javascript
onImported = function (importNode, context, e, root, importedAtRoot, fullPath) {
    if (e) {
        if (!e.filename) {
            e.index = importNode.index; e.filename = importNode.currentFileInfo.filename;
        }
        this.error = e;
    }

    var importVisitor = this,
        inlineCSS = importNode.options.inline,
        isPlugin = importNode.options.plugin,
        isOptional = importNode.options.optional,
        duplicateImport = importedAtRoot || fullPath in importVisitor.recursionDetector;

    if (!context.importMultiple) {
        if (duplicateImport) {
            importNode.skip = true;
        } else {
            importNode.skip = function() {
                if (fullPath in importVisitor.onceFileDetectionMap) {
                    return true;
                }
                importVisitor.onceFileDetectionMap[fullPath] = true;
                return false;
            };
        }
    }

    if (!fullPath && isOptional) {
        importNode.skip = true;
    }

    if (root) {
        importNode.root = root;
        importNode.importedFilename = fullPath;

        if (!inlineCSS && !isPlugin && (context.importMultiple || !duplicateImport)) {
            importVisitor.recursionDetector[fullPath] = true;

            var oldContext = this.context;
            this.context = context;
            try {
                this._visitor.visit(root);
            } catch (e) {
                this.error = e;
            }
            this.context = oldContext;
        }
    }

    importVisitor.importCount--;

    if (importVisitor.isFinished) {
        importVisitor._sequencer.tryRun();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.processImportNode"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>processImportNode (importNode, context, importParent)](#apidoc.element.less.visitors.ImportVisitor.prototype.processImportNode)
- description and source-code
```javascript
processImportNode = function (importNode, context, importParent) {
    var evaldImportNode,
        inlineCSS = importNode.options.inline;

    try {
        evaldImportNode = importNode.evalForImport(context);
    } catch(e) {
        if (!e.filename) { e.index = importNode.index; e.filename = importNode.currentFileInfo.filename; }
        // attempt to eval properly and treat as css
        importNode.css = true;
        // if that fails, this error will be thrown
        importNode.error = e;
    }

    if (evaldImportNode && (!evaldImportNode.css || inlineCSS)) {

        if (evaldImportNode.options.multiple) {
            context.importMultiple = true;
        }

        // try appending if we haven't determined if it is css or not
        var tryAppendLessExtension = evaldImportNode.css === undefined;

        for (var i = 0; i < importParent.rules.length; i++) {
            if (importParent.rules[i] === importNode) {
                importParent.rules[i] = evaldImportNode;
                break;
            }
        }

        var onImported = this.onImported.bind(this, evaldImportNode, context),
            sequencedOnImported = this._sequencer.addImport(onImported);

        this._importer.push(evaldImportNode.getPath(), tryAppendLessExtension, evaldImportNode.currentFileInfo,
            evaldImportNode.options, sequencedOnImported);
    } else {
        this.importCount--;
        if (this.isFinished) {
            this._sequencer.tryRun();
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.run"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ImportVisitor.prototype.run)
- description and source-code
```javascript
run = function (root) {
    try {
        // process the contents
        this._visitor.visit(root);
    }
    catch(e) {
        this.error = e;
    }

    this.isFinished = true;
    this._sequencer.tryRun();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitDirective"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitDirective)
- description and source-code
```javascript
visitDirective = function (directiveNode, visitArgs) {
    this.context.frames.unshift(directiveNode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitDirectiveOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitDirectiveOut (directiveNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitDirectiveOut)
- description and source-code
```javascript
visitDirectiveOut = function (directiveNode) {
    this.context.frames.shift();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitImport"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitImport (importNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitImport)
- description and source-code
```javascript
visitImport = function (importNode, visitArgs) {
    var inlineCSS = importNode.options.inline;

    if (!importNode.css || inlineCSS) {

        var context = new contexts.Eval(this.context, this.context.frames.slice(0));
        var importParent = context.frames[0];

        this.importCount++;
        if (importNode.isVariableImport()) {
            this._sequencer.addVariableImport(this.processImportNode.bind(this, importNode, context, importParent));
        } else {
            this.processImportNode(importNode, context, importParent);
        }
    }
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitMedia"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMedia)
- description and source-code
```javascript
visitMedia = function (mediaNode, visitArgs) {
    this.context.frames.unshift(mediaNode.rules[0]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitMediaOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMediaOut (mediaNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMediaOut)
- description and source-code
```javascript
visitMediaOut = function (mediaNode) {
    this.context.frames.shift();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinition"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinition)
- description and source-code
```javascript
visitMixinDefinition = function (mixinDefinitionNode, visitArgs) {
    this.context.frames.unshift(mixinDefinitionNode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinitionOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitMixinDefinitionOut (mixinDefinitionNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitMixinDefinitionOut)
- description and source-code
```javascript
visitMixinDefinitionOut = function (mixinDefinitionNode) {
    this.context.frames.shift();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitRule"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRule)
- description and source-code
```javascript
visitRule = function (ruleNode, visitArgs) {
    if (ruleNode.value.type === "DetachedRuleset") {
        this.context.frames.unshift(ruleNode);
    } else {
        visitArgs.visitDeeper = false;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRuleOut (ruleNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleOut)
- description and source-code
```javascript
visitRuleOut = function (ruleNode) {
    if (ruleNode.value.type === "DetachedRuleset") {
        this.context.frames.shift();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleset"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRuleset)
- description and source-code
```javascript
visitRuleset = function (rulesetNode, visitArgs) {
    this.context.frames.unshift(rulesetNode);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ImportVisitor.prototype.visitRulesetOut"></a>[function <span class="apidocSignatureSpan">less.visitors.ImportVisitor.prototype.</span>visitRulesetOut (rulesetNode)](#apidoc.element.less.visitors.ImportVisitor.prototype.visitRulesetOut)
- description and source-code
```javascript
visitRulesetOut = function (rulesetNode) {
    this.context.frames.shift();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.JoinSelectorVisitor"></a>[module less.visitors.JoinSelectorVisitor](#apidoc.module.less.visitors.JoinSelectorVisitor)

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.JoinSelectorVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>JoinSelectorVisitor ()](#apidoc.element.less.visitors.JoinSelectorVisitor.JoinSelectorVisitor)
- description and source-code
```javascript
JoinSelectorVisitor = function () {
    this.contexts = [[]];
    this._visitor = new Visitor(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.JoinSelectorVisitor.prototype"></a>[module less.visitors.JoinSelectorVisitor.prototype](#apidoc.module.less.visitors.JoinSelectorVisitor.prototype)

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.run"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.run)
- description and source-code
```javascript
run = function (root) {
    return this._visitor.visit(root);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitDirective"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitDirective)
- description and source-code
```javascript
visitDirective = function (directiveNode, visitArgs) {
    var context = this.contexts[this.contexts.length - 1];
    if (directiveNode.rules && directiveNode.rules.length) {
        directiveNode.rules[0].root = (directiveNode.isRooted || context.length === 0 || null);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMedia"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMedia)
- description and source-code
```javascript
visitMedia = function (mediaNode, visitArgs) {
    var context = this.contexts[this.contexts.length - 1];
    mediaNode.rules[0].root = (context.length === 0 || context[0].multiMedia);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMixinDefinition"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitMixinDefinition (mixinDefinitionNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitMixinDefinition)
- description and source-code
```javascript
visitMixinDefinition = function (mixinDefinitionNode, visitArgs) {
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRule"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRule)
- description and source-code
```javascript
visitRule = function (ruleNode, visitArgs) {
    visitArgs.visitDeeper = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRuleset"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRuleset)
- description and source-code
```javascript
visitRuleset = function (rulesetNode, visitArgs) {
    var context = this.contexts[this.contexts.length - 1],
        paths = [], selectors;

    this.contexts.push(paths);

    if (! rulesetNode.root) {
        selectors = rulesetNode.selectors;
        if (selectors) {
            selectors = selectors.filter(function(selector) { return selector.getIsOutput(); });
            rulesetNode.selectors = selectors.length ? selectors : (selectors = null);
            if (selectors) { rulesetNode.joinSelectors(paths, context, selectors); }
        }
        if (!selectors) { rulesetNode.rules = null; }
        rulesetNode.paths = paths;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRulesetOut"></a>[function <span class="apidocSignatureSpan">less.visitors.JoinSelectorVisitor.prototype.</span>visitRulesetOut (rulesetNode)](#apidoc.element.less.visitors.JoinSelectorVisitor.prototype.visitRulesetOut)
- description and source-code
```javascript
visitRulesetOut = function (rulesetNode) {
    this.contexts.length = this.contexts.length - 1;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.MarkVisibleSelectorsVisitor"></a>[module less.visitors.MarkVisibleSelectorsVisitor](#apidoc.module.less.visitors.MarkVisibleSelectorsVisitor)

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.MarkVisibleSelectorsVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>MarkVisibleSelectorsVisitor (visible)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.MarkVisibleSelectorsVisitor)
- description and source-code
```javascript
MarkVisibleSelectorsVisitor = function (visible) {
    this.visible = visible;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.MarkVisibleSelectorsVisitor.prototype"></a>[module less.visitors.MarkVisibleSelectorsVisitor.prototype](#apidoc.module.less.visitors.MarkVisibleSelectorsVisitor.prototype)

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.run"></a>[function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.run)
- description and source-code
```javascript
run = function (root) {
    this.visit(root);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visit"></a>[function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>visit (node)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visit)
- description and source-code
```javascript
visit = function (node) {
    if (!node) {
        return node;
    }
    if (node.constructor === Array) {
        return this.visitArray(node);
    }

    if (!node.blocksVisibility || node.blocksVisibility()) {
        return node;
    }
    if (this.visible) {
        node.ensureVisibility();
    } else {
        node.ensureInvisibility();
    }

    node.accept(this);
    return node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visitArray"></a>[function <span class="apidocSignatureSpan">less.visitors.MarkVisibleSelectorsVisitor.prototype.</span>visitArray (nodes)](#apidoc.element.less.visitors.MarkVisibleSelectorsVisitor.prototype.visitArray)
- description and source-code
```javascript
visitArray = function (nodes) {
    if (!nodes) {
        return nodes;
    }

    var cnt = nodes.length, i;
    for (i = 0; i < cnt; i++) {
        this.visit(nodes[i]);
    }
    return nodes;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ToCSSVisitor"></a>[module less.visitors.ToCSSVisitor](#apidoc.module.less.visitors.ToCSSVisitor)

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.ToCSSVisitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>ToCSSVisitor (context)](#apidoc.element.less.visitors.ToCSSVisitor.ToCSSVisitor)
- description and source-code
```javascript
ToCSSVisitor = function (context) {
    this._visitor = new Visitor(this);
    this._context = context;
    this.utils = new CSSVisitorUtils(context);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.ToCSSVisitor.prototype"></a>[module less.visitors.ToCSSVisitor.prototype](#apidoc.module.less.visitors.ToCSSVisitor.prototype)

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype._compileRulesetPaths"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_compileRulesetPaths (rulesetNode)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._compileRulesetPaths)
- description and source-code
```javascript
_compileRulesetPaths = function (rulesetNode) {
    if (rulesetNode.paths) {
        rulesetNode.paths = rulesetNode.paths
            .filter(function(p) {
                var i;
                if (p[0].elements[0].combinator.value === ' ') {
                    p[0].elements[0].combinator = new(tree.Combinator)('');
                }
                for (i = 0; i < p.length; i++) {
                    if (p[i].isVisible() && p[i].getIsOutput()) {
                        return true;
                    }
                }
                return false;
            });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype._mergeRules"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_mergeRules (rules)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._mergeRules)
- description and source-code
```javascript
_mergeRules = function (rules) {
    if (!rules) { return; }

    var groups = {},
        parts,
        rule,
        key;

    for (var i = 0; i < rules.length; i++) {
        rule = rules[i];

        if ((rule instanceof tree.Rule) && rule.merge) {
            key = [rule.name,
                rule.important ? "!" : ""].join(",");

            if (!groups[key]) {
                groups[key] = [];
            } else {
                rules.splice(i--, 1);
            }

            groups[key].push(rule);
        }
    }

    Object.keys(groups).map(function (k) {

        function toExpression(values) {
            return new (tree.Expression)(values.map(function (p) {
                return p.value;
            }));
        }

        function toValue(values) {
            return new (tree.Value)(values.map(function (p) {
                return p;
            }));
        }

        parts = groups[k];

        if (parts.length > 1) {
            rule = parts[0];
            var spacedGroups = [];
            var lastSpacedGroup = [];
            parts.map(function (p) {
                if (p.merge === "+") {
                    if (lastSpacedGroup.length > 0) {
                        spacedGroups.push(toExpression(lastSpacedGroup));
                    }
                    lastSpacedGroup = [];
                }
                lastSpacedGroup.push(p);
            });
            spacedGroups.push(toExpression(lastSpacedGroup));
            rule.value = toValue(spacedGroups);
        }
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype._removeDuplicateRules"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>_removeDuplicateRules (rules)](#apidoc.element.less.visitors.ToCSSVisitor.prototype._removeDuplicateRules)
- description and source-code
```javascript
_removeDuplicateRules = function (rules) {
    if (!rules) { return; }

    // remove duplicates
    var ruleCache = {},
        ruleList, rule, i;

    for (i = rules.length - 1; i >= 0 ; i--) {
        rule = rules[i];
        if (rule instanceof tree.Rule) {
            if (!ruleCache[rule.name]) {
                ruleCache[rule.name] = rule;
            } else {
                ruleList = ruleCache[rule.name];
                if (ruleList instanceof tree.Rule) {
                    ruleList = ruleCache[rule.name] = [ruleCache[rule.name].toCSS(this._context)];
                }
                var ruleCSS = rule.toCSS(this._context);
                if (ruleList.indexOf(ruleCSS) !== -1) {
                    rules.splice(i, 1);
                } else {
                    ruleList.push(ruleCSS);
                }
            }
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.checkValidNodes"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>checkValidNodes (rules, isRoot)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.checkValidNodes)
- description and source-code
```javascript
checkValidNodes = function (rules, isRoot) {
    if (!rules) {
        return;
    }

    for (var i = 0; i < rules.length; i++) {
        var ruleNode = rules[i];
        if (isRoot && ruleNode instanceof tree.Rule && !ruleNode.variable) {
            throw { message: "Properties must be inside selector blocks. They cannot be in the root",
                index: ruleNode.index, filename: ruleNode.currentFileInfo && ruleNode.currentFileInfo.filename};
        }
        if (ruleNode instanceof tree.Call) {
            throw { message: "Function '" + ruleNode.name + "' is undefined",
                index: ruleNode.index, filename: ruleNode.currentFileInfo && ruleNode.currentFileInfo.filename};
        }
        if (ruleNode.type && !ruleNode.allowRoot) {
            throw { message: ruleNode.type + " node returned by a function is not valid here",
                index: ruleNode.index, filename: ruleNode.currentFileInfo && ruleNode.currentFileInfo.filename};
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.run"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>run (root)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.run)
- description and source-code
```javascript
run = function (root) {
    return this._visitor.visit(root);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitAnonymous"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitAnonymous (anonymousNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitAnonymous)
- description and source-code
```javascript
visitAnonymous = function (anonymousNode, visitArgs) {
    if (anonymousNode.blocksVisibility()) {
        return ;
    }
    anonymousNode.accept(this._visitor);
    return anonymousNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitComment"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitComment (commentNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitComment)
- description and source-code
```javascript
visitComment = function (commentNode, visitArgs) {
    if (commentNode.blocksVisibility() || commentNode.isSilent(this._context)) {
        return;
    }
    return commentNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirective"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirective (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirective)
- description and source-code
```javascript
visitDirective = function (directiveNode, visitArgs) {
    if (directiveNode.rules && directiveNode.rules.length) {
        return this.visitDirectiveWithBody(directiveNode, visitArgs);
    } else {
        return this.visitDirectiveWithoutBody(directiveNode, visitArgs);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithBody"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirectiveWithBody (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithBody)
- description and source-code
```javascript
visitDirectiveWithBody = function (directiveNode, visitArgs) {
    //if there is only one nested ruleset and that one has no path, then it is
    //just fake ruleset
    function hasFakeRuleset(directiveNode) {
        var bodyRules = directiveNode.rules;
        return bodyRules.length === 1 && (!bodyRules[0].paths || bodyRules[0].paths.length === 0);
    }
    function getBodyRules(directiveNode) {
        var nodeRules = directiveNode.rules;
        if (hasFakeRuleset(directiveNode)) {
            return nodeRules[0].rules;
        }

        return nodeRules;
    }
    //it is still true that it is only one ruleset in array
    //this is last such moment
    //process childs
    var originalRules = getBodyRules(directiveNode);
    directiveNode.accept(this._visitor);
    visitArgs.visitDeeper = false;

    if (!this.utils.isEmpty(directiveNode)) {
        this._mergeRules(directiveNode.rules[0].rules);
    }

    return this.utils.resolveVisibility(directiveNode, originalRules);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithoutBody"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitDirectiveWithoutBody (directiveNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitDirectiveWithoutBody)
- description and source-code
```javascript
visitDirectiveWithoutBody = function (directiveNode, visitArgs) {
    if (directiveNode.blocksVisibility()) {
        return;
    }

    if (directiveNode.name === "@charset") {
        // Only output the debug info together with subsequent @charset definitions
        // a comment (or @media statement) before the actual @charset directive would
        // be considered illegal css as it has to be on the first line
        if (this.charset) {
            if (directiveNode.debugInfo) {
                var comment = new tree.Comment("/* " + directiveNode.toCSS(this._context).replace(/\n/g, "") + " */\n");
                comment.debugInfo = directiveNode.debugInfo;
                return this._visitor.visit(comment);
            }
            return;
        }
        this.charset = true;
    }

    return directiveNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitExtend"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitExtend (extendNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitExtend)
- description and source-code
```javascript
visitExtend = function (extendNode, visitArgs) {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitImport"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitImport (importNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitImport)
- description and source-code
```javascript
visitImport = function (importNode, visitArgs) {
    if (importNode.blocksVisibility()) {
        return ;
    }
    return importNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMedia"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitMedia (mediaNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMedia)
- description and source-code
```javascript
visitMedia = function (mediaNode, visitArgs) {
    var originalRules = mediaNode.rules[0].rules;
    mediaNode.accept(this._visitor);
    visitArgs.visitDeeper = false;

    return this.utils.resolveVisibility(mediaNode, originalRules);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMixinDefinition"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitMixinDefinition (mixinNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitMixinDefinition)
- description and source-code
```javascript
visitMixinDefinition = function (mixinNode, visitArgs) {
    // mixin definitions do not get eval'd - this means they keep state
    // so we have to clear that state here so it isn't used if toCSS is called twice
    mixinNode.frames = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRule"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitRule (ruleNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRule)
- description and source-code
```javascript
visitRule = function (ruleNode, visitArgs) {
    if (ruleNode.blocksVisibility() || ruleNode.variable) {
        return;
    }
    return ruleNode;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRuleset"></a>[function <span class="apidocSignatureSpan">less.visitors.ToCSSVisitor.prototype.</span>visitRuleset (rulesetNode, visitArgs)](#apidoc.element.less.visitors.ToCSSVisitor.prototype.visitRuleset)
- description and source-code
```javascript
visitRuleset = function (rulesetNode, visitArgs) {
    //at this point rulesets are nested into each other
    var rule, rulesets = [];

    this.checkValidNodes(rulesetNode.rules, rulesetNode.firstRoot);

    if (! rulesetNode.root) {
        //remove invisible paths
        this._compileRulesetPaths(rulesetNode);

        // remove rulesets from this ruleset body and compile them separately
        var nodeRules = rulesetNode.rules, nodeRuleCnt = nodeRules ? nodeRules.length : 0;
        for (var i = 0; i < nodeRuleCnt; ) {
            rule = nodeRules[i];
            if (rule && rule.rules) {
                // visit because we are moving them out from being a child
                rulesets.push(this._visitor.visit(rule));
                nodeRules.splice(i, 1);
                nodeRuleCnt--;
                continue;
            }
            i++;
        }
        // accept the visitor to remove rules and refactor itself
        // then we can decide nogw whether we want it or not
        // compile body
        if (nodeRuleCnt > 0) {
            rulesetNode.accept(this._visitor);
        } else {
            rulesetNode.rules = null;
        }
        visitArgs.visitDeeper = false;

    } else { //if (! rulesetNode.root) {
        rulesetNode.accept(this._visitor);
        visitArgs.visitDeeper = false;
    }

    if (rulesetNode.rules) {
        this._mergeRules(rulesetNode.rules);
        this._removeDuplicateRules(rulesetNode.rules);
    }

    //now decide whether we keep the ruleset
    if (this.utils.isVisibleRuleset(rulesetNode)) {
        rulesetNode.ensureVisibility();
        rulesets.splice(0, 0, rulesetNode);
    }

    if (rulesets.length === 1) {
        return rulesets[0];
    }
    return rulesets;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.Visitor"></a>[module less.visitors.Visitor](#apidoc.module.less.visitors.Visitor)

#### <a name="apidoc.element.less.visitors.Visitor.Visitor"></a>[function <span class="apidocSignatureSpan">less.visitors.</span>Visitor (implementation)](#apidoc.element.less.visitors.Visitor.Visitor)
- description and source-code
```javascript
Visitor = function (implementation) {
    this._implementation = implementation;
    this._visitFnCache = [];

    if (!_hasIndexed) {
        indexNodeTypes(tree, 1);
        _hasIndexed = true;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.less.visitors.Visitor.prototype"></a>[module less.visitors.Visitor.prototype](#apidoc.module.less.visitors.Visitor.prototype)

#### <a name="apidoc.element.less.visitors.Visitor.prototype.flatten"></a>[function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>flatten (arr, out)](#apidoc.element.less.visitors.Visitor.prototype.flatten)
- description and source-code
```javascript
flatten = function (arr, out) {
    if (!out) {
        out = [];
    }

    var cnt, i, item,
        nestedCnt, j, nestedItem;

    for (i = 0, cnt = arr.length; i < cnt; i++) {
        item = arr[i];
        if (item === undefined) {
            continue;
        }
        if (!item.splice) {
            out.push(item);
            continue;
        }

        for (j = 0, nestedCnt = item.length; j < nestedCnt; j++) {
            nestedItem = item[j];
            if (nestedItem === undefined) {
                continue;
            }
            if (!nestedItem.splice) {
                out.push(nestedItem);
            } else if (nestedItem.length) {
                this.flatten(nestedItem, out);
            }
        }
    }

    return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.Visitor.prototype.visit"></a>[function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>visit (node)](#apidoc.element.less.visitors.Visitor.prototype.visit)
- description and source-code
```javascript
visit = function (node) {
    if (!node) {
        return node;
    }

    var nodeTypeIndex = node.typeIndex;
    if (!nodeTypeIndex) {
        return node;
    }

    var visitFnCache = this._visitFnCache,
        impl = this._implementation,
        aryIndx = nodeTypeIndex << 1,
        outAryIndex = aryIndx | 1,
        func = visitFnCache[aryIndx],
        funcOut = visitFnCache[outAryIndex],
        visitArgs = _visitArgs,
        fnName;

    visitArgs.visitDeeper = true;

    if (!func) {
        fnName = "visit" + node.type;
        func = impl[fnName] || _noop;
        funcOut = impl[fnName + "Out"] || _noop;
        visitFnCache[aryIndx] = func;
        visitFnCache[outAryIndex] = funcOut;
    }

    if (func !== _noop) {
        var newNode = func.call(impl, node, visitArgs);
        if (impl.isReplacing) {
            node = newNode;
        }
    }

    if (visitArgs.visitDeeper && node && node.accept) {
        node.accept(this);
    }

    if (funcOut != _noop) {
        funcOut.call(impl, node);
    }

    return node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.less.visitors.Visitor.prototype.visitArray"></a>[function <span class="apidocSignatureSpan">less.visitors.Visitor.prototype.</span>visitArray (nodes, nonReplacing)](#apidoc.element.less.visitors.Visitor.prototype.visitArray)
- description and source-code
```javascript
visitArray = function (nodes, nonReplacing) {
    if (!nodes) {
        return nodes;
    }

    var cnt = nodes.length, i;

    // Non-replacing
    if (nonReplacing || !this._implementation.isReplacing) {
        for (i = 0; i < cnt; i++) {
            this.visit(nodes[i]);
        }
        return nodes;
    }

    // Replacing
    var out = [];
    for (i = 0; i < cnt; i++) {
        var evald = this.visit(nodes[i]);
        if (evald === undefined) { continue; }
        if (!evald.splice) {
            out.push(evald);
        } else if (evald.length) {
            this.flatten(evald, out);
        }
    }
    return out;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# Change Log - @microsoft/api-extractor

This log was last generated on Thu, 09 Aug 2018 21:03:22 GMT and should not be manually modified.

## 5.10.3
Thu, 09 Aug 2018 21:03:22 GMT

*Version update only*

## 5.10.2
Thu, 09 Aug 2018 16:04:24 GMT

### Patches

- Update lodash.

## 5.10.1
Thu, 26 Jul 2018 16:04:17 GMT

*Version update only*

## 5.10.0
Tue, 17 Jul 2018 16:02:52 GMT

### Minor changes

- Add support for new "@eventproperty" AEDoc tag, which indicates that a class/interface property should be documented as an event

## 5.9.1
Tue, 03 Jul 2018 21:03:31 GMT

*Version update only*

## 5.9.0
Sat, 23 Jun 2018 02:21:20 GMT

### Minor changes

- Add new IMarkupHtmlTag API
- AEDoc now allows HTML tags inside doc comments, which can be disabled using a backslash escape

## 5.8.1
Thu, 21 Jun 2018 08:27:29 GMT

*Version update only*

## 5.8.0
Tue, 19 Jun 2018 19:35:11 GMT

### Minor changes

- For namespaceSupport=permissive, allow arbitrary nesting of namespaces

### Patches

- Fix an issue where multi-line type literals sometimes had inconsistent newlines in the *.api.json file

## 5.7.3
Fri, 08 Jun 2018 08:43:52 GMT

*Version update only*

## 5.7.2
Thu, 31 May 2018 01:39:33 GMT

*Version update only*

## 5.7.1
Tue, 15 May 2018 02:26:45 GMT

*Version update only*

## 5.7.0
Tue, 15 May 2018 00:18:10 GMT

### Minor changes

- Add support for new AEDoc tags @sealed, @virtual, and @override

## 5.6.8
Fri, 04 May 2018 00:42:38 GMT

### Patches

- Fix the formatting of a log message.

## 5.6.7
Tue, 01 May 2018 22:03:20 GMT

### Patches

- Fix an issue where the *.d.ts rollup trimming did not trim import statements

## 5.6.6
Fri, 27 Apr 2018 03:04:32 GMT

*Version update only*

## 5.6.5
Thu, 19 Apr 2018 21:25:56 GMT

*Version update only*

## 5.6.4
Thu, 19 Apr 2018 17:02:06 GMT

### Patches

- Fix errors in schema documentation

## 5.6.3
Tue, 03 Apr 2018 16:05:29 GMT

*Version update only*

## 5.6.2
Mon, 02 Apr 2018 16:05:24 GMT

### Patches

- Refactor to use new @microsoft/node-core-library

## 5.6.1
Tue, 27 Mar 2018 01:34:25 GMT

### Patches

- Update build config so API Extractor builds using the latest version of itself

## 5.6.0
Sun, 25 Mar 2018 01:26:19 GMT

### Minor changes

- Improve the api-extractor.json config file so that *.d.ts rollups go in separate folders, and trimming can now be disabled

### Patches

- In preparation for initial release, the "Package Typings" feature was renamed to "DTS Rollup"
- Fix an issue where the @packagedocumentation comment was sometimes getting mixed into the middle of the rollup *.d.ts file

## 5.5.2
Fri, 23 Mar 2018 00:34:53 GMT

### Patches

- Upgrade colors to version ~1.2.1

## 5.5.1
Tue, 20 Mar 2018 02:44:45 GMT

### Patches

- Improve packageTypings generator to trim nested members according to their release tag
- Fix a bug where packageTypings failed to handle merged declarations properly

## 5.5.0
Sat, 17 Mar 2018 02:54:22 GMT

### Minor changes

- Overhaul the packageTypings generator analysis to get ready for the upcoming nested member trimming
- Breaking change: Any projects using the package typings feature must now have a "tsdoc" section in their package.json

### Patches

- Add "--debug" flag for debugging

## 5.4.0
Thu, 15 Mar 2018 20:00:50 GMT

### Minor changes

- Add a new setting validationRules.missingReleaseTags to optionally remove the requirement that every API item should have a release tag
- Add new API "Markup.formatApiItemReference()"

### Patches

- Fix an issue where the automatically generated documentation for class constructors sometimes had a broken hyperlink

## 5.3.9
Thu, 15 Mar 2018 16:05:43 GMT

*Version update only*

## 5.3.8
Mon, 12 Mar 2018 20:36:19 GMT

### Patches

- Locked down some "@types/" dependency versions to avoid upgrade conflicts

## 5.3.7
Tue, 06 Mar 2018 17:04:51 GMT

### Patches

- Add preliminary support for preview and public outputs for packageTypings generator

## 5.3.6
Fri, 02 Mar 2018 01:13:59 GMT

*Version update only*

## 5.3.5
Tue, 27 Feb 2018 22:05:57 GMT

*Version update only*

## 5.3.4
Wed, 21 Feb 2018 22:04:19 GMT

*Version update only*

## 5.3.3
Wed, 21 Feb 2018 03:13:28 GMT

*Version update only*

## 5.3.2
Sat, 17 Feb 2018 02:53:49 GMT

### Patches

- Fix several bugs with the way that imports were being deduplicated by the packageTypings feature

## 5.3.1
Fri, 16 Feb 2018 22:05:23 GMT

*Version update only*

## 5.3.0
Fri, 16 Feb 2018 17:05:11 GMT

### Minor changes

- Fix an issue where the packageTypings feature didn't handle some import/export patterns

### Patches

- Fix an issue where the packageTypings feature sometimes emitted "default" instead of the class name
- Improve the packageTypings feature to support triple-slash references to typings

## 5.2.7
Wed, 07 Feb 2018 17:05:11 GMT

*Version update only*

## 5.2.6
Fri, 26 Jan 2018 22:05:30 GMT

*Version update only*

## 5.2.5
Fri, 26 Jan 2018 17:53:38 GMT

### Patches

- Force a patch bump in case the previous version was an empty package

## 5.2.4
Fri, 26 Jan 2018 00:36:51 GMT

*Version update only*

## 5.2.3
Tue, 23 Jan 2018 17:05:28 GMT

*Version update only*

## 5.2.2
Thu, 18 Jan 2018 03:23:46 GMT

### Patches

- Enable package typings generated by api-extractor

## 5.2.1
Thu, 18 Jan 2018 00:48:06 GMT

*Version update only*

## 5.2.0
Thu, 18 Jan 2018 00:27:23 GMT

### Minor changes

- Improve the packageTypings feature to support abstract classes and "import * as X" imports

## 5.1.3
Wed, 17 Jan 2018 10:49:31 GMT

*Version update only*

## 5.1.2
Fri, 12 Jan 2018 03:35:22 GMT

### Patches

- Add some incremental improvements for the experimental PackageTypingsGenerator feature

## 5.1.1
Thu, 11 Jan 2018 22:31:51 GMT

*Version update only*

## 5.1.0
Wed, 10 Jan 2018 20:40:01 GMT

### Minor changes

- Upgrade to Node 8

### Patches

- Continued progress for the experimental PackageTypingsGenerator

## 5.0.1
Tue, 09 Jan 2018 17:05:51 GMT

### Patches

- Get web-build-tools building with pnpm

## 5.0.0
Sun, 07 Jan 2018 05:12:08 GMT

### Breaking changes

- API Extractor now processes *.d.ts files instead of *.ts files

### Minor changes

- Introduced new tag @packagedocumentation which replaces the earlier approach that used a "packageDescription" variable

## 4.3.7
Fri, 05 Jan 2018 20:26:45 GMT

*Version update only*

## 4.3.6
Fri, 05 Jan 2018 00:48:41 GMT

### Patches

- Update Jest to ~21.2.1

## 4.3.5
Fri, 22 Dec 2017 17:04:46 GMT

### Patches

- Fixed an issue where warnings would cause the api-extractor tool to return a nonzero exit code for a "--local" build; warnings should not fail the build in this scenario

## 4.3.4
Tue, 12 Dec 2017 03:33:26 GMT

*Version update only*

## 4.3.3
Thu, 30 Nov 2017 23:59:09 GMT

*Version update only*

## 4.3.2
Thu, 30 Nov 2017 23:12:21 GMT

*Version update only*

## 4.3.1
Wed, 29 Nov 2017 17:05:37 GMT

*Version update only*

## 4.3.0
Tue, 28 Nov 2017 23:43:55 GMT

### Minor changes

- Add Extractor.processProject() whose return value indicates success

### Patches

- Deprecate Extractor.analyzeProject() API

## 4.2.6
Mon, 13 Nov 2017 17:04:50 GMT

*Version update only*

## 4.2.5
Mon, 06 Nov 2017 17:04:18 GMT

*Version update only*

## 4.2.4
Thu, 02 Nov 2017 16:05:24 GMT

### Patches

- lock the reference version between web build tools projects

## 4.2.3
Wed, 01 Nov 2017 21:06:08 GMT

### Patches

- Upgrade cyclic dependencies

## 4.2.2
Tue, 31 Oct 2017 21:04:04 GMT

*Version update only*

## 4.2.1
Tue, 31 Oct 2017 16:04:55 GMT

*Version update only*

## 4.2.0
Wed, 25 Oct 2017 20:03:59 GMT

### Minor changes

- Improved the way API JSON represents documentation markup; this is a file format change

## 4.1.2
Tue, 24 Oct 2017 18:17:12 GMT

*Version update only*

## 4.1.1
Mon, 23 Oct 2017 21:53:12 GMT

### Patches

- Updated cyclic dependencies

## 4.1.0
Fri, 20 Oct 2017 19:57:12 GMT

### Minor changes

- Add policies.namespaceSupport option to API Extractor config

### Patches

- Fixed an issue where properties were sometimes marked as readonly; a remark is automatically generated for classes with internal constructors

## 4.0.1
Fri, 20 Oct 2017 01:52:54 GMT

### Patches

- Rename ApiExtractor class to Extractor

## 4.0.0
Fri, 20 Oct 2017 01:04:44 GMT

### Breaking changes

- Redesigned interface for invoking API Extractor

## 3.4.2
Thu, 05 Oct 2017 01:05:02 GMT

*Version update only*

## 3.4.1
Fri, 29 Sep 2017 01:03:42 GMT

### Patches

- Removed IMarkupPage.docId

## 3.4.0
Thu, 28 Sep 2017 01:04:28 GMT

### Minor changes

- Skipping two lines in an AEDoc comment now creates a paragraph separator for the generated documentation

### Patches

- The *.api.json "linkDocElement" type now always explicitly specifies the package name, rather than expecting the reader to infer it
- The *.api.json file format now exposes "signature" information for properties, functions, and module variables

## 3.3.0
Fri, 22 Sep 2017 01:04:02 GMT

### Minor changes

- Upgrade to es6

## 3.2.6
Wed, 20 Sep 2017 22:10:17 GMT

*Version update only*

## 3.2.5
Mon, 11 Sep 2017 13:04:55 GMT

### Patches

- The isBeta and deprecatedMessage fields are now inherited in the *.api.json files
- Fix an issue where the *.api.json file was sometimes missing function parameters

## 3.2.4
Fri, 08 Sep 2017 01:28:04 GMT

### Patches

- Deprecate @types/es6-coll ections in favor of built-in typescript typings 'es2015.collection' a nd 'es2015.iterable'

## 3.2.3
Thu, 07 Sep 2017 13:04:35 GMT

### Patches

- Fix incorrect schema/typings for enum members

## 3.2.2
Thu, 07 Sep 2017 00:11:11 GMT

### Patches

-  Add $schema field to all schemas

## 3.2.1
Wed, 06 Sep 2017 13:03:42 GMT

### Patches

- Converted IMarkupDocumentationLink to IMarkupApiLink, which exposes the underlying IApiItemReference rather than assuming a particular "document ID" model

## 3.2.0
Tue, 05 Sep 2017 19:03:56 GMT

### Minor changes

- Add the constructor signature and package name to the exported API signature

## 3.1.0
Sat, 02 Sep 2017 01:04:26 GMT

### Minor changes

- Expanded the api-extractor API to expose interfaces for the *.api.json file fileformat

## 3.0.0
Thu, 31 Aug 2017 18:41:18 GMT

### Breaking changes

- Fix compatibility issues with old releases, by incrementing the major version number

## 2.3.7
Thu, 31 Aug 2017 17:46:25 GMT

### Patches

- Fix issue where node-core-library was not an explicit dependency

## 2.3.6
Wed, 30 Aug 2017 01:04:34 GMT

*Version update only*

## 2.3.5
Thu, 24 Aug 2017 22:44:12 GMT

### Patches

- Update the schema validator.

## 2.3.4
Thu, 24 Aug 2017 01:04:33 GMT

*Version update only*

## 2.3.3
Tue, 22 Aug 2017 13:04:22 GMT

### Patches

- Added "api-documenter" code sample

## 2.3.2
Tue, 15 Aug 2017 01:29:31 GMT

### Patches

- Introduce Span parser for upcoming *.d.ts generator

## 2.3.1
Thu, 27 Jul 2017 01:04:48 GMT

### Patches

- Upgrade to the TS2.4 version of the build tools.

## 2.3.0
Tue, 25 Jul 2017 20:03:31 GMT

### Minor changes

- Upgrade to TypeScript 2.4

## 2.2.0
Wed, 21 Jun 2017 04:19:35 GMT

### Minor changes

- Add two new features: An error is reported if a top-level definition is missing its release tag. The constructor summary will now be autogenerated if omitted.

## 2.0.10
Tue, 20 Jun 2017 01:04:54 GMT

### Patches

- Improve the wording of many error messages
- Fix a bug with parsing of @link tags
- Issue warnings for @internal definitions that are not prefixed with an underscore

## 2.0.9
Sat, 17 Jun 2017 01:02:59 GMT

### Patches

- The unsupported @summary tag is now reported as an error
- Use a cache to speed up package.json lookups

## 2.0.8
Wed, 14 Jun 2017 13:03:40 GMT

### Patches

- Definitions marked as @beta are now included in the *.api.json files for documentation

## 2.0.7
Thu, 08 Jun 2017 05:15:52 GMT

### Patches

- Updated README.md

## 2.0.6
Mon, 15 May 2017 21:59:43 GMT

### Patches

- Added support for Namespace with ApiNamespace

## 2.0.5
Sat, 22 Apr 2017 01:02:03 GMT

### Patches

- Added check for API names that are not supported (only letters and numbers supported)

## 2.0.4
Wed, 19 Apr 2017 20:18:06 GMT

### Patches

- Remove ES6 Promise & @types/es6-promise typings

## 2.0.3
Fri, 14 Apr 2017 17:44:08 GMT

### Patches

- Added collect references ability to detect determine type information of return types and parameter types.

## 2.0.2
Fri, 07 Apr 2017 21:43:16 GMT

### Patches

- Adjusted the version specifier for typescript to ~2.2.2

## 2.0.1
Thu, 06 Apr 2017 01:32:23 GMT

### Patches

- Removed hard coding of @public for ApiPackage

## 2.0.0
Mon, 20 Mar 2017 21:52:20 GMT

### Breaking changes

- Fixing whitespace, also a variable that was shadowing another variable.

## 1.1.19
Mon, 20 Mar 2017 04:20:13 GMT

### Patches

- Reverting change.

## 1.1.18
Mon, 20 Mar 2017 03:50:55 GMT

### Patches

- Reverting previous change, which causes a regression in SPFx yeoman sc enario.

## 1.1.17
Mon, 20 Mar 2017 00:54:03 GMT

### Patches

- Fixing lint whitespace issues.

## 1.1.16
Sun, 19 Mar 2017 19:10:30 GMT

### Patches

- Fixing variable that was shadowing another variable.

## 1.1.15
Wed, 15 Mar 2017 01:32:09 GMT

### Patches

- Locking `@types` packages. Synchronizing version specifiers for dependencies with other `web-build-tools` projects.

## 1.1.14
Sat, 18 Feb 2017 02:32:06 GMT

### Patches

- Seperated the ApiItem initialization into 3 stages: create documentation that doesn't require resolution, then complete initialization by resolving links and inheritdocs. This allows us to ignore harmless cycles like type references"

## 1.1.13
Thu, 16 Feb 2017 22:10:39 GMT

### Patches

- Fixed Api-Extractor error message, changed apostrophe to backtick.

## 1.1.12
Thu, 16 Feb 2017 18:56:57 GMT

### Patches

- Added support for local API definition resolution"

## 1.1.11
Sat, 11 Feb 2017 02:32:35 GMT

### Patches

- Changed dependency for ApiDocumentation to abstract the resolving of API definition references.

## 1.1.10
Fri, 10 Feb 2017 20:01:30 GMT

### Patches

-  Added support to not throw error, instead report error if no type is declared on properties and parameters

## 1.1.9
Tue, 07 Feb 2017 20:37:06 GMT

### Patches

- Fixing issue where undocumented comment was not being emitted.

## 1.1.8
Sat, 04 Feb 2017 02:32:05 GMT

### Patches

- Moved ApiItem references within ApiDocumentation, to ApiItem caller.

## 1.1.7
Thu, 02 Feb 2017 14:05:53 GMT

### Patches

- Refactored ApiDocumentation creation to resolve references method.

## 1.1.6
Wed, 01 Feb 2017 20:09:30 GMT

### Patches

- Added ApiItemKind enum and refactored child classes.

## 1.1.5
Fri, 27 Jan 2017 20:04:15 GMT

### Patches

- Changed name of Analyzer to Extractor, added support for external api json doc loading.

## 1.1.4
Fri, 27 Jan 2017 02:35:10 GMT

### Patches

- Added ExternalApiHelper class to be used in generating api documentation json files for external types.
- Added description for packages implementation.
- Added config folder with file to enable api-extractor on itself. rebuild project on previous build.

## 1.1.3
Tue, 24 Jan 2017 01:36:35 GMT

### Patches

- Json schema was updated to reflect feature additions to linkDocElement. The linkDocElement can now be of type 'code' which refers to an API definition reference.

## 1.1.2
Fri, 20 Jan 2017 01:46:41 GMT

*Version update only*

## 1.1.1
Thu, 19 Jan 2017 20:04:40 GMT

### Patches

- Check for missing JSDoc sequences changed.
- Improved error messages

## 1.1.0
Wed, 18 Jan 2017 20:04:29 GMT

### Minor changes

- Updating API Extractor to work with TypeScript 2.1

## 1.0.2
Mon, 16 Jan 2017 20:04:15 GMT

### Patches

- @link capability for href and API definition references

## 1.0.1
Fri, 13 Jan 2017 06:46:05 GMT

*Version update only*

## 1.0.0
Wed, 11 Jan 2017 14:11:26 GMT

### Breaking changes

- Introducing API Extractor


Getting Started with the Creative Cloud Extension SDK
==============

This page provides resources you need to get started creating extensions for Adobe Creative Cloud applications, using the new HTML5/JavaScript interface model. The Flash/ActionScript interface model for extensions is deprecated in the Creative Cloud release; support has already been removed in Adobe Photoshop CC2014, Adobe Flash CC2015 and Adobe Dreamweaver CC2015.

* In the Creative Cloud 2015 release extensions and add-ins must be built on the CEP 6 infrastructure.

* In the Creative Cloud 2014 release, extensions and add-ins must be built on the CEP 5 infrastructure and loaded with Extension Manager. The current releases either do not now or soon will not support CEP 4 and Flash/ActionScript extensions.

* The Creative Suite 6 and the Creative Cloud 2013 releases of Adobe desktop applications support CEP 4, which allows you to build extensions using the older Flash/ActionScript interface model. However, the new HTML5/JavaScript model is preferred. It is recommended that you port existing Flash/ActionScript extensions to the new model.

This SDK provides the low-level tools that you need to build extensions. Extensions that you build using these tools must be packaged as ZXP files in order to be seen and loaded by Extension Manager. You can offer extensions as free or paid products through our marketing portals (Adobe Exchange, the Add-ins website, the Creative Cloud desktop app). When you do this, you upload the extension to Adobe as a single ZXP file. 

Resources you will need include:
* CEP JavaScript libraries for communicating  with the operating system and Extension Manager and for communicating wtih the host application and other extensions.
* Sample code for how to use these libraries
* The ZXP packager, a command-line utility

---

For developing CEP6 HTML/JavaScript extensions for CC2015 host applications

**Documentation**
* [CEP 6 HTML Extension Cookbook for CC 2015](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-6-HTML-Extension-Cookbook-for-CC-2015)

**APIs** (https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_6.x)
* Include these files in your extension project if you need to use the APIs.
  * AgoraLib.js
  * CSInterface.js
* Do NOT include this file in your extension project. It is already integrated into CEP.
  * CEPEngine_extensions.js
* Extension Manifest (unchanged in CEP 6.0)
  * ExtensionManifest_v_5_0.xsd

**Samples**
* [Sample extensions](https://github.com/Adobe-CEP/Samples)

----

For developing CEP5 HTML/JavaScript extensions for CC2014 host applications

**Documentation**
* [Offical Adobe Extension SDK Documentation for CC 2014](http://adobe.ly/1rin38t)
* [CEP 5 HTML Extension Cookbook for CC 2014](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-HTML-Extension-Cookbook-for-CC-2014)
* [CEP 5 Flash Extension Cookbook for CC 2014](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-Flash-Extension-Cookbook-for-CC-2014)

**APIs** (https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_5.x)
* Include these files in your extension project if you need to use the APIs.
  * AgoraLib.js
  * CSInterface.js
  * Vulcan.js
* Do NOT include this file in your extension project. It is already integrated into CEP.
  * CEPEngine_extensions.js
* Extension Manifest
  * ExtensionManifest_v_5_0.xsd
* PlugPlugExternalObject
  * [PlugPlugExternalObject for InDesign CC 2014](http://bit.ly/1qlnKOb)

**Samples**
* [Sample extensions](https://github.com/Adobe-CEP/Samples)

**Other Documents**
* [CEP for the InDesign Developer](http://adobe.ly/1xXkviH)
* [Extending Adobe CC 2014 apps using Node.js](http://bit.ly/1yAR0T9)
* [A short guide to HTML5 extensions](http://adobe.ly/Nk1EK7)
   (NOTE:  For CEP 4.0 but still mostly relevant)
* [Guide to signing extensions](http://adobe.ly/1oiS4FE)
   (NOTE:  For CEP 4.0 but valid for CEP 5)

----

For developing CEP 4.x and extensions for CS6/CC host applications

**Documentation**
* [Documentation for CEP 4.2](http://adobe.ly/1cWBggl)
* [Tutorial](http://bit.ly/1nNLqH4)
   (NOTE: A bit old)

**APIs** (https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_4.x)
* Include these files in your extension project if you need to use the APIs.
  * CSInterface.js
  * Vulcan.js
* Do NOT include this file in your extension project. It is already integrated into CEP.
  * CEPEngine_extensions.js
* Extension Manifest
  * ExtensionManifest_v_4_0.xsd

**Tooling**
* [Extension Builder 3 Preview](http://adobe.ly/1pho2QU)
* [Extension Builder 3 forums - get help from the developer community](http://adobe.ly/1mgZ2xe)
   (NOTE: EB3 is compatible with CEP 4.x only. You can [tweak it](http://adobe.ly/1v3wgiq) so that it supports CC 2014 (with limitations))

----

Miscellaneous help
* [Andy Hall's Super Mega Guide (English)] (http://bit.ly/XQn9IV) [ (Japanese)] (http://bit.ly/XQnB9P) 
* [Davide Barranca’s blog](http://bit.ly/Nk1Mta)
* [David Deraedt’s plugin for Adobe Brackets](http://bit.ly/QKWWYL)
* [Olav Martin Kvern's article on extensibility and InDesign](http://bit.ly/1zEa9Ef)
* [The other API (Article on Medium)](http://bit.ly/1hIFZay)
* [Adobe Exchange](http://bit.ly/1mHVksI)
* [Photoshop CC 2014 CEP samples by John Peterson](http://bit.ly/1nGAWYN)

----




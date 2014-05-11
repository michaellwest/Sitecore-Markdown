Markdown for Sitecore
====

Markdown is Sitecore provides a sophisticated balance between multi-line & rich-text fields in Sitecore.  Created by Dan Cruickshank for Fishtank Consulting.

Contents
----

###Ready-to-Install

Contains ready-to-deploy binaries, configs and Sitecore package to get Markdown for Sitecore running in your Sitecore 6 & Sitecore 7 instances with minimum effort.

###Sitecore-6

Contains the Visual Studio project, configs and Sitecore package to build & integrate Markdown for Sitecore into your Sitecore 6 solution. 

###Sitecore-7

Contains the Visual Studio project, configs and Sitecore package to build & integrate Markdown for Sitecore into your Sitecore 7 solution.  This includes support using Markdown for Sitecore with the ContentSearch API.

Notes
----

- *Sitecore.Kernel.dll* cannot be deployed with this project. When using the *Fishtank.CustomFields.Markdown* Visual Studio project, re-add the reference to your local *Sitecore.Kernel.dll* library.
- *Sitecore.ContentSearch.dll* will also need to be re-added if using Sitecore 7.
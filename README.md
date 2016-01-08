# TSL_Tools, Code Snippets, Templates and Perfmon Countersets

http://blogs.msdn.com/b/geoffgr/archive/2014/10/08/code-snippets-templates-and-perfmon-countersets-download.aspx
geoffgr 8 Oct 2014

I am sharing a set of tools I use during many of my engagements and projects. These tools have been written by myself and my [ITSM teammates](http://blogs.msdn.com/b/testingspot/) over the past several years.  The zip file includes the following (each item has a Word document explaining how to install and use):

### C# Project and Item Templates

Templates that allow you to create your own custom plugins and rules for web and load testing, as well as a project template to create a custom data collector. Item templates include:

*   ConditionalRule
*   ExtractionRule
*   LoadTestPlugin
*   ValidationRule
*   WebTestPlugin
*   WebTestRequestPlugin

### C# Code Snippets

These code snippets allow you to easily insert code snippets for things like public property and methods descriptions, code for enumerating various test contexts, and many other useful items:

*   **TSL_CodePieces.snippet**

  *   TSL_Snip_ContextAddOrUpdate
  *   TSL_Snip_HandleContextParams
  *   TSL_Snip_FailTheIteration
  *   TSL_Snip_ForEach_HTMLTagInnerText
  *   TSL_Snip_ForEach_StringSplit
  *   TSL_Snip_FormPostHttpBody
  *   TSL_Snip_LoadTestUserContextExistsInUnitTest
  *   TSL_Snip_LoadTestUserContextExistsInWebtest
  *   SQLConnectionWithDataReader

*   **TSL_Declarations.snippet**

  *   TSL_Snip_CopyrightText
  *   TSL_Snip_ClassLabels
  *   TSL_Snip_MethodLabels
  *   TSL_Snip_ProjectComments
  *   TSL_Snip_PropertyLabels_bool
  *   TSL_Snip_PropertyLabels_int
  *   TSL_Snip_PropertyLabels_string

### Visual Studio custom Perfmon Counter sets

These counter sets are a little different than the built in counter sets. They also can give you a good starting point for modifying or creating your own custom perfmon counters:

*   TSL Application.counterset
*   TSL ASP.Net.counterset
*   TSL DotNet.counterset
*   TSL IIS.counterset
*   TSL SQL.counterset

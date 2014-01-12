Fancy
==================================

Fancy is designed to act as a type-safe, F# orientated wrapper around the Nancy. 

<div class="row">
  <div class="span1"></div>
  <div class="span6">
    <div class="well well-small" id="nuget">
      The Fancy Library is available as <a href="https://nuget.org/packages/Fanciful">Fancy on NuGet</a>.
      To install it, run the following command in the <a href="http://docs.nuget.org/docs/start-here/using-the-package-manager-console">Package Manager Console</a>:
      <pre>PM> Install-Package Fanciful</pre>
    </div>
  </div>
  <div class="span1"></div>
</div>

Alternatively, you can download the [source as a ZIP file](https://github.com/tpetricek/FSharp.Formatting/zipball/master)
or download the [compiled binaries](https://github.com/tpetricek/FSharp.Formatting/archive/release.zip) as a ZIP.

Documentation
-------------

The documentation for this library is generated automatically (using the literate programming 
tools that are built on top of it and are described in [literate programming page](demo.html).
If you spot a typo, please submit a pull request! The source Markdown and F# script files are
available in the [docs folder on GitHub](https://github.com/tpetricek/FSharp.Formatting/tree/master/docs).
I hope it is also a good sample showing how to write documentation for F# projects.

 - [Literate programming](demo.html) - if you want to use the library to generate documentation
   for your projects or if you want to use it to write nicely formatted F# blog posts, then
   start here! This page describes the literate programming sample.

 - [Markdown parser](markdown.html) - this page provides more details about the F# Markdown
   processor that is available in this library. It includes some basic examples of
   document processing.

 - [F# code formatting](codeformat.html) - this page provides more details about the F# code
   formatter; it discusses how to call it to obtain information about F# source files.

 - [Library documentation tool](metadata.html) - provides a brief documentation for a tool
   that generates nice HTML documentation from "XML comments" in your (not just) F# libraries.
   The tool is a replacement of `FsHtmlDoc` - it uses Razor for easy templating and handles
   comments written in Markdown too. 

More information
----------------

The project is hosted on [GitHub](https://github.com/tpetricek/FSharp.Formatting) where you can 
[report issues](https://github.com/tpetricek/FSharp.Formatting/issues), fork the project and submit pull requests.
Thanks to [Gustavo Guerra](https://github.com/ovatsus) for a great build script and 
[Steffen Forkmann](https://github.com/forki) for the great build tool [FAKE](https://github.com/fsharp/FAKE).
The library is available under Apache 2.0. For more information see the 
[License file](https://github.com/tpetricek/FSharp.Formatting/blob/master/LICENSE.md) in the GitHub repository.

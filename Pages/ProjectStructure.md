#! {{$Site.Name}}- Project Structure

## Directory Overview

![Folder structure diagram](assets/folders.png)


----


## Property Access and Updates

Reference site properties using `{{$PropertyName}}` to pull values directly from your sitekit.xdsl file. Any changes there automatically update all instances, ensuring consistency and easier maintenance across your project.


----


## Adding New Pages

![New page illustration](assets/new-page.png)

To add a new page, simply create a file in the Pages folder. You can use either HTML or Markdown (with Markdown being the preferred option for its simplicity). SiteKit also supports hybrid Markdown, allowing you to incorporate HTML tags within your Markdown content.


----


## Overview of the sitekit.xdsl File

The `sitekit.xdsl` file contains metadata about your site, including user-defined properties. Xdsl (Extensible Data Structure Language) is a custom markup language developed by Realtin; in most cases, valid XML is also acceptable as Xdsl.
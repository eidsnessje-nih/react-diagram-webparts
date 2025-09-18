# React Diagram Web Parts

An SPFx Web Part that generates Diagrams using the Mermaid language and javasscript library.

## Summary

This solution contains a collection of web parts that make it easy
to embed various types of diagrams in pages.

![Diagram Web Parts](./assets/DiagramWebParts.gif)

### Flowchart

![Flowchart Web Part](./assets/FlowChartWebPart.gif)

The Flowchart web part allows you to use simple text to create flowchart diagrams in a page.

It uses the [js-flowchart](https://github.com/adrai/flowchart.js) syntax to quickly create diagrams.

### Mermaid diagram

![Mermaid Web Part](./assets/MermaidWebPart.gif)

The Mermaid diagram web part allows you to use simple text to create flowcharts, gantt charts, and sequence diagrams and control their appearance.

It uses the [mermaidjs](https://mermaidjs.github.io/) syntax to create awesome diagrams.

### Sequence diagram

![Sequence Diagram Web Part](./assets/SequenceWebPart.gif)

The Sequence diagram web part allows you to create sequence diagrams using simple text.

It uses the [js-sequence-diagrams](https://bramp.github.io/js-sequence-diagrams/) syntax to make creating sequence diagrams intuitive.

## Used SharePoint Framework Version

![SPFx v1.8.1](https://img.shields.io/badge/SPFx-1.8.1-green.svg)

## Applies to

* [SharePoint Framework](https:/dev.office.com/sharepoint)
* [Office 365 tenant](https://dev.office.com/sharepoint/docs/spfx/set-up-your-development-environment)

## Solution

Solution|Author(s)
--------|---------
react-diagram-webparts | Hugo Bernier ([Tahoe Ninjas](http://tahoeninjas.blog), @bernierh)

## Version history

Version|Date|Comments
-------|----|--------
1.0|Feb 8, 2019|Initial release
1.1|Feb 12, 2019|Added Mermaid diagram web part.
1.2|Apr 16, 2019|Upgraded to SPFx 1.8
1.3|Apr 22, 2019|Upgraded to SPFx 1.8.1

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

* Clone this repository
* in the command line run:
  * `npm install`
  * `gulp serve`

## Features

This Web Part illustrates the following concepts:

* Using [react-sequence-diagram](https://github.com/zfanta/react-sequence-diagram) in a SPFx web part (React component based on [js-sequence-diagrams](https://bramp.github.io/js-sequence-diagrams/))
* Using [react-simple-flowchart](https://github.com/alwinn1977/react-simple-flowchart) in a SPFx web part (React component based on [js-flowchart](https://github.com/adrai/flowchart.js))
* Using [mermaid](https://github.com/knsv/mermaid) in a SPFx web part.
* Converting a static SVG to a responsive SVG post-render
* Improving accessibility on a SVG post-render
* Creating a custom code editor property pane that allows custom code/syntax
* Using [react-ace](https://github.com/securingsincity/react-ace) to embed an Ace Editor for code editing and syntax highlighting
* Creating custom syntax highlighting for react-ace
* Creating a custom Markdown property pane control that renders a read-only version of Markdown text in a property pane
* Using [markdown-to-jsx](https://github.com/probablyup/markdown-to-jsx) to render Markdown in a web part

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/react-diagram-webparts" />

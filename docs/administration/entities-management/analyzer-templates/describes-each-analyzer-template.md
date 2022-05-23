# Definition of an Analyzer Template

Analyzers templates are angular js code used to display a human-readable report of an analyzer job report.

In TheHive, you can add observables. They are technical elements that can be analyzed using analyzers. Analyzers will take the technical element as input and produce a JSON formatted report as output.

This JSON report may not be human-friendly when looking for information into this report, and this report can be very long. 

While analysts use these analyzers to get accurate information in a timely manner, we provide analyzers-template to format this JSON report and provide something more human-readable or put the most accurate information on the top of the list/more visible for the analysts.

This analyzers-template can be added, modified, or deleted in TheHive for each existing analyzer. 

There are two types of analyzers templates:

* Long template: The one you will see when opening the analysis report on an observable page
* Short template: Small tag that will be added to an observable. You can see them on the observables page.

## Long template example:

The following is a "raw" report. It is an analyzer report that hasn't been formatted by an analyzer template.

<img src="../images/unformatted-analyzer-report.png" alt="Unformatted Analyzer Report" width="1000" height="1000"/>

The same report after formatted by the "long" analyzer-template is:

<img src="../images/formatted-analyzer-report.png" alt="Formatted Analyzer Report" width="1000" height="1000"/>

## Short template example:

These are short reports, providing a very concise summary of the analysis report.

<img src="../images/short-report.png" alt="Short Report" width="1000" height="1000"/>


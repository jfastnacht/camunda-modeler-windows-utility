# Camunda-Modeler Windows Utility

> Registry entries and templates for simplification of Camunda-Modeler usage.

## Prerequisits

* Camunda-Modeler
* Inkscape
    * check whether the registry key at `HKEY_CLASSES_ROOT\inkscape.svg` exists

## Installation

* copy `Template.bpmn` to `C:\Windows\ShellNew`
* edit paths in `*.reg` files

## Troubleshooting

**SVG2PDF**
* check whether your `HKEY_CLASSES_ROOT\.svg` key exists and points to Inkscape
* if not, you can add the `HKEY_CLASSES_ROOT\shell\Convert to PDF` here
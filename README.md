# Trainz Config

Language definition for [Trainz Config.txt](http://online.ts2009.com/mediaWiki/index.php/ACS_Text_Format) files for Visual Studio Code

## Usage

This package is supposed to help you creating / editing Config.txt files for N3Vs Trainz Simulator.
If you open a Config.txt file in Sublime Text it will automaticly choose Trainz Config as language definition, so no work for you here!
For the best results set the indentation to spaces and set the tab size to 2.

The values are indented by 40 characters (20 tabs), containers are framed by curly brackets with a line break before and after them.

### Example

```text
kuid                                    <kuid:XXXXXX:XXXXXX>
kind                                    "track"
istrack                                 0
username                                "Demo Asset"
trainz-build                            3.9
category-era                            "2000s"
category-class                          "TR"
category-region                         "00"

mesh-table
{
  default
  {
    auto-create                         1
    mesh                                "mesh.im"
  }
}

kuid-table
{
}
```
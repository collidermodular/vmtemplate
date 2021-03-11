# vmtemplate
IntelliJ template for my typical Voltage Modular Designer JAR project

## What The Template Contains

 * Source and test directories
 * Maven support
 * JUnit / Jupiter / Mockito dependencies
 * Basic JAR artifact export setup
 
## Installation

 1. Clone this repository
 1. Open with IntelliJ
 1. Make any edits
 1. Tools > Save Project as Template

## Usage

Once installed (above)...

 1. New > Project
 1. Choose "User-Defined" from the left menu

## Using JARs with Voltage Modular Designer

#### From within IntelliJ
 1. Build > Build Artifacts
 1. Build (project name)

#### From within VM Designer
 1. De-select everything
 1. Within the properties pane "Additional JAR Files"
 1. Select project/out/artifacts/project.jar
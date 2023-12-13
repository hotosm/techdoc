# Overarching Architecture Folder
While today HOT architecture consists of a wide range of applications and modules, the vision for the future is a more unified ecosystem. 

The key features of this architecture are:
* An integrated set of back-end modules
* A common data model based on standards and only extending as required
* Fit for purpose front-ends, built on REACT

Please refer to the [decisions](/decisions) log for details about HOT architecture decisions. 

## Solution User View
LibreOffice Source(TBD)<br/>
![Solution User View](HOT_SolutionUser.drawio.svg)

## Information Flow
[LibreOffice Source](HOT%20Information%20Flow.odg)<br/>
![Information Flow Diagram](HOT%20Information%20Flow.png)

## Component Model
[LibreOffice Source](HOT%20Component%20Diagram.odg)<br/>
![Component Diagram](HOT%20Component%20Diagram.png)

## Integration Sequence Diagrams

|  |  |
|--|--|
| <img src="OSDs/Overarching%20OSD%20-%20TM%20User%20Profiles%20to%20FTM.png" width="90%"/> | <img src="OSDs/Overarching%20OSD%20-%20TM%20Org%20Profiles%20to%20FTM.png" width="90%"/> |
| <img src="OSDs/Overarching%20OSD%20-%20TM%20Projects%20to%20FTM.png" width="90%"/> | MAYBE DELETE<br/><img src="OSDs/Overarching%20OSD%20-%20FTM%20Invalidate%20Task%20to%20TM.png" width="90%"/> |
| MAYBE DELETE<br/><img src="OSDs/Overarching%20OSD%20-%20TM%20Tasks%20to%20FTM.png" width="90%"/> | MAYBE DELETE<br/><img src="OSDs/Overarching%20OSD%20-%20FTM%20Task%20Status%20to%20TM.png" width="90%"/> |
| MAYBE DELETE<br/><img src="OSDs/Overarching%20OSD%20-%20TM%20Project%20Members%20to%20FTM.png" width="90%"/> | . |

## Conceptual Data Model
[LibreOffice Source](Overarching%20Data%20Model.odg)<br/>
![Conceptual Data Model](Overarching%20Data%20Model.png)


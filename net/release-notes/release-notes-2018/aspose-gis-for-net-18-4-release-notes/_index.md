---
title: "Aspose.GIS for .NET 18.4 Release Notes"
type: docs
url: /net/aspose-gis-for-net-18-4-release-notes/
weight: 110
---

{{% alert color="primary" %}} 

This page contains release notes information for Aspose.GIS for .NET 18.4.

{{% /alert %}} 
## **Major Features**
Major features and improvements in this release:

- Spatial reference systems support
  - [Work with WKT](/gis/net/working-with-spatial-reference-system/#workingwithspatialreferencesystem-workingwithwkt) - Import spatial reference systems from WKT and export spatial reference systems to WKT
  - Create vector layers with [spatial reference system](/gis/net/working-with-layers/#workingwithlayers-createvectorlayerwithspatialreferencesystem)
  - Set desired spatial reference system when converting between layers
  - Transform [geometries](/gis/net/working-with-geometries/#workingwithgeometries-setspatialreferencesystemforgeometry) between spatial reference systems
## **Features and Improvements**

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|GISNET-165|Spatial reference systems support|New Feature|
|GISNET-170|Convert between spatial reference systems|New Feature|
|GISNET-167|Fix IGeometry methods visibility|Bug|
## **Public API and Backward Incompatible Changes**
###### **IGeometry has immutable HasZ and HasM**
IGeometry was designed to be immutable. Setters for HasZ and HasM were present there which have been removed now.



|**C# (before v18.4)**|
| :- |
|void HandleGeometry(IGeometry geometry)<br>{<br>`    `geometry.HasZ = true; // you could change HasZ directly on IGeometry<br>`    `// ...<br>}|
|**C# (since v18.4)**|
|void HandleGeometry(IGeometry geometry)<br>{<br>`    `Geometry clone = geometry.Clone(); // now, you must clone geometry to get mutable instance and change HasZ<br>`    `clone.HasZ = true;<br>`    `// ...<br>}|


---
title: "Aspose.GIS for .NET 22.9 Release Notes"
type: docs
url: /net/aspose-gis-for-net-22-9-release-notes/
weight: 140
---

{{% alert color="primary" %}} 

This page contains release notes information for [Aspose.GIS for .NET 22.9](https://www.nuget.org/packages/Aspose.GIS/22.9.0).

{{% /alert %}} 
## **Major Features**
- Support Esri Json Driver. 
## **Full List of Issues Covering all Changes in this Release**

|**Key**|**Summary**|**Category**|
| :- | :- | :- |
|GISNET-997|Read data from EsriJson|Feature|
|GISNET-1370|Write data to EsriJson|Feature|
## **Public API and Backward Incompatible Changes**
Following members have been added:

- P:Aspose.Gis.Drivers.EsriJson
- T:Aspose.Gis.Formats.EsriJson.EsriJsonDriver
- P:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CanCreateLayers
- P:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CanOpenLayers
- P:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CanCreateDatasets
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.SupportsSpatialReferenceSystem(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CreateLayer(System.String,Aspose.Gis.Formats.EsriJson.EsriJsonOptions)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CreateLayer(Aspose.Gis.AbstractPath,Aspose.Gis.Formats.EsriJson.EsriJsonOptions)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CreateLayer(Aspose.Gis.AbstractPath,Aspose.Gis.DriverOptions,Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.CreateLayer(Aspose.Gis.AbstractPath,Aspose.Gis.Formats.EsriJson.EsriJsonOptions,Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.OpenLayer(System.String,Aspose.Gis.Formats.EsriJson.EsriJsonOptions)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.OpenLayer(Aspose.Gis.AbstractPath,Aspose.Gis.DriverOptions)
- M:Aspose.Gis.Formats.EsriJson.EsriJsonDriver.OpenLayer(Aspose.Gis.AbstractPath,Aspose.Gis.Formats.EsriJson.EsriJsonOptions)
- T:Aspose.Gis.Formats.EsriJson.EsriJsonOptions
- M:Aspose.Gis.Formats.EsriJson.EsriJsonOptions.#ctor
- P:Aspose.Gis.Formats.EsriJson.EsriJsonOptions.NestedPropertiesSeparator

Following members have been removed:

- none
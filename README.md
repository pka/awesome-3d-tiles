# Awesome 3D Tiles [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome open source software, libraries, tools and resources for 3D tiles.

Contributions welcome. Add links through [pull requests](https://github.com/pka/awesome-3d-tiles/pulls) or create an [issue](https://github.com/pka/awesome-3d-tiles/issues) to start a discussion.

[3D Tiles](https://github.com/CesiumGS/3d-tiles) is an open specification for sharing, visualizing, fusing, and interacting with massive heterogenous 3D geospatial content across desktop, web, and mobile applications.

3D Tiles is an [OGC community standard](https://www.ogc.org/standard/3dtiles/).

## Viewers

* [CesiumJS](https://github.com/CesiumGS/cesium) - JavaScript library for creating 3D globes and 2D maps in a web browser.
* [3DCityDB-Web-Map-Client](https://github.com/3dcitydb/3dcitydb-web-map) - Cesium based Viewer for CityGML und 3D Tiles.
* [loaders.gl](https://loaders.gl/docs/specifications/category-3d-tiles) - Parsers and encoders for many major 3D, geospatial and tabular formats.
* [deck.gl](https://deck.gl/docs/api-reference/geo-layers/tile-3d-layer) - WebGL-powered framework for visual exploratory data analysis of large datasets.
* [3d-tiles-renderer](https://github.com/NASA-AMMOS/3DTilesRendererJS) - Three.js based renderer for 3D Tiles.
* [three-loader-3dtiles](https://github.com/nytimes/three-loader-3dtiles) - [Three.js](https://threejs.org/) loader module for handling OGC 3D Tiles.
* [threedtiles](https://github.com/ebeaufay/3DTilesViewer) - 3DTiles viewer for three.js.
* [mapbox-3dtiles](https://github.com/Geodan/mapbox-3dtiles) - Mapbox GL JS custom layer for 3D Tiles.
* [A-Frame component](https://github.com/nytimes/aframe-loader-3dtiles-component) - [A-Frame](https://aframe.io/) component using 3D-Tiles.
* [iTowns](https://github.com/iTowns/itowns) - Three.js based JS/WebGL framework.
* [giro3d](https://gitlab.com/giro3d/giro3d) - Three.js based JS/WebGL framework (successor of iTown).
* [UD-Viz](https://github.com/VCityTeam/UD-Viz) - Urban Data Vizualisation. Framework for creating web applications for visualizing and interacting with geospatial 3D urban data (based on iTowns/Tree.js).
* [vsgCs](https://github.com/timoore/vsgCs) - a library for using 3D Tiles and other geospatial content within a Vulkan Scene Graph (VSG) application

## Game engine, desktop GIS and 3D modeling tool integrations (Open source)

* [QGIS](https://www.qgis.org/) - Multi-platform desktop geographical information system (since version 3.34).
* [3D Tiles for Godot](https://github.com/Battle-Road-Labs/3D-Tiles-For-Godot) - Godot 4 extension that integrates Cesium 3D Tiles capabilities into Godot Engine
* [Open 3D Engine (O3DE)](https://github.com/CesiumGS/cesium-o3de) - Cesium for O3DE
* [blender-3d-tiler](https://gitee.com/cesium_processing/blender-3d-tiler) - [Blender](https://www.blender.org/) tool for tiling 3d models.

## Tile creation (Cesium GS Inc)

* Cesium Ion (SaaS)
* [CDB to 3D Tiles](https://github.com/CesiumGS/cdb-to-3dtiles) - OGC CDB → 3D Tiles.
* [Cesium Native](https://github.com/CesiumGS/cesium-native) - C++ library for 3D Tiles streaming, glTF processing.
* [3D Tiles Tools](https://github.com/CesiumGS/3d-tiles-tools) - Tools and utilities for converting, optimizing, processing and analyzing 3D Tiles data.
* [glTF Pipeline](https://github.com/CesiumGS/gltf-pipeline) - Javascript tools for glTF / GLB conversion and optimization.

## Tile creation (Community)

* [py3dtiles](https://gitlab.com/py3dtiles/py3dtiles) - Read and write pnts and b3dm via API or CLI.
* [Python 3DTiles Tilers](https://github.com/VCityTeam/py3dtilers) - Python tool and library allowing to build 3D Tiles tilesets out of various geometrical formats e.g. OBJ, GeoJSON, IFC or CityGML through 3dCityDB databases.
* [pg2b3dm](https://github.com/Geodan/pg2b3dm) - Conversion of PostGIS 3D geometries to b3dm tiles.
* [mago 3DTiler](https://github.com/Gaia3D/mago-3d-tiler) - mago 3DTiler converts various spatial data into OGC 3D Tiles.
* [PLATEAU GIS Converter](https://github.com/MIERUNE/plateau-gis-converter) - Convert 3D city models (CityGML) into various geospatial formats, including 3D Tiles, MVT, and GeoPackage.
* [Obj2Tiles](https://github.com/OpenDroneMap/Obj2Tiles) - Converts OBJ files to OGC 3D tiles.
* [3dtiles](https://github.com/fanvanzh/3dtiles) - Converts Osgb(OpenSceneGraph Binary), Esri Shapefile and Fbx files into 3D Tiles.
* [gltf-to-3d-tiles](https://github.com/xuzhusheng/gltf-to-3d-tiles) - Convert glTF model to Glb, b3dm or 3d tiles format.
* [citygml-to-3dtiles](https://github.com/njam/citygml-to-3dtiles) - Convert from CityGML to Cesium 3D Tiles.
* [vts23dtiles](https://github.com/melowntech/vts-tools) - Convert VTS tileset into 3D Tileset.
* [3D City Database](https://www.3dcitydb.org/) - Geo database to store, represent, and manage virtual 3D city models.
* [Cesium Point Cloud Generator](https://github.com/tum-gis/cesium-point-cloud-generator) - XYZ → 3D Point Cloud Tiles.
* [loaders.gl tile-converter](https://loaders.gl/docs/modules/tile-converter/cli-reference/tile-converter) - Convert I3S to 3D Tiles.
* [tyler](https://github.com/3DGI/tyler) - Tiling 3D city models encoded in CityJSON

## glTF tools

* [glTF-Transform](https://gltf-transform.donmccurdy.com/cli.html) - glTF-Transform supports reading, editing, and writing 3D models in glTF 2.0 format.
* [Open Asset Import Library (assimp)](https://github.com/assimp/assimp) - Library and converter for 40+ 3D-file-formats into glTF and more ([file formats](https://github.com/assimp/assimp/blob/master/doc/Fileformats.md)).
* [Blender exporter](https://docs.blender.org/manual/en/latest/addons/import_export/scene_gltf2.html#extensions) - Blender glTF 2.0 Exporter.

## Terrain

[Quantized Mesh](https://github.com/CesiumGS/quantized-mesh) is a format to encode terrain meshes for efficient client-side terrain rendering. Such files are supported in Cesium and deck.gl.

See [awesome-quantized-mesh-tiles](https://github.com/bertt/awesome-quantized-mesh-tiles#readme) for more resources.

## Demo applications

* [3D BAG](https://3dbag.nl/en/viewer)
* [Berlin 3D](https://berlin.virtualcitymap.de/#) | [Bremen 3D](https://bremen.virtualcitymap.de/#/) | [Helsinki 3D](https://kartta.hel.fi/3d/#/) | [Soest 3D](https://soest.virtualcitymap.de/#/)
* [basemap.de](https://basemap.de/beta/)
* [UnrealEngineDigitalTwinLowerSaxony](https://github.com/JulianMuellerLgln/UnrealEngineDigitalTwinLowerSaxony) - [Presentation (german)](https://pretalx.com/fossgis2025/talk/8P79JV/)
* [Google Photorealistic 3D Tiles](https://developers.google.com/maps/documentation/tile/3d-tiles)

## Learning material / Howtos

* [Rendering the World with 3D Tiles](https://cesium.com/learn/presentations/#rendering-the-world-with-3d-tiles).
* [mago3DTiler workshop](https://github.com/Gaia3D/mago3d-doc/blob/main/foss4g/Table_Of_Contents_En.md) - mago3DTiler technical workshop materials from FOSS4G-Asia (2024)

## Community

* [Discussions](https://github.com/pka/awesome-3d-tiles/discussions)

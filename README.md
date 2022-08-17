# Awesome 3D Tiles [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome open source software, libraries, tools and resources for 3D tiles.

Contributions welcome. Add links through [pull requests](https://github.com/pka/awesome-3d-tiles/pulls) or create an [issue](https://github.com/pka/awesome-3d-tiles/issues) to start a discussion.

[3D Tiles](https://github.com/CesiumGS/3d-tiles) is an open specification for sharing, visualizing, fusing, and interacting with massive heterogenous 3D geospatial content across desktop, web, and mobile applications.

[3D Tiles Next](https://github.com/CesiumGS/3d-tiles/tree/main/next) is a set of new capabilities for the future of 3D Tiles ([Blog post](https://cesium.com/blog/2021/11/10/introducing-3d-tiles-next/)).

3D Tiles is an [OGC community standard](https://www.opengeospatial.org/standards/3DTiles).

## Viewers

* [CesiumJS](https://github.com/CesiumGS/cesium) - JavaScript library for creating 3D globes and 2D maps in a web browser.
* [iTowns](https://github.com/iTowns/itowns) - Three.js based JS/WebGL framework.
* [mapbox-3dtiles](https://github.com/Geodan/mapbox-3dtiles) - Mapbox GL JS custom layer for 3D Tiles.
* [3DCityDB-Web-Map-Client](https://github.com/3dcitydb/3dcitydb-web-map) - Cesium based Viewer for CityGML und 3D Tiles.
* [3d-tiles-renderer](https://github.com/NASA-AMMOS/3DTilesRendererJS) - Three.js based renderer for 3D Tiles.
* [three-loader-3dtiles](https://github.com/nytimes/three-loader-3dtiles) - [Three.js](https://threejs.org/) loader module for handling OGC 3D Tiles.
* [threedtiles](https://github.com/ebeaufay/3DTilesViewer) - 3DTiles viewer for three.js.
* [A-Frame component](https://github.com/nytimes/aframe-loader-3dtiles-component) - [A-Frame](https://aframe.io/) component using 3D-Tiles.
* [loaders.gl](https://loaders.gl/docs/specifications/category-3d-tiles) - Parsers and encoders for many major 3D, geospatial and tabular formats.
* [deck.gl](https://deck.gl/docs/api-reference/geo-layers/tile-3d-layer) - WebGL-powered framework for visual exploratory data analysis of large datasets.

## Game engine and 3D modeling tool integrations (Open source)

* [Open 3D Engine (O3DE)](https://www.o3de.org/) - [blog post](https://cesium.com/blog/2022/02/16/announcing-cesium-for-o3de/)
* [blender-3d-tiler](https://gitee.com/cesium_processing/blender-3d-tiler) - [Blender](https://www.blender.org/) tool for tiling 3d models.

## Tile creation (Cesium GS Inc)

* Cesium Ion (proprietary)
* [CDB to 3D Tiles](https://github.com/CesiumGS/cdb-to-3dtiles) - OGC CDB → 3D Tiles.
* [Cesium Native](https://github.com/CesiumGS/cesium-native) - C++ library for 3D Tiles streaming, glTF processing.
* [glTF Pipeline](https://github.com/CesiumGS/gltf-pipeline) - Javascript tools for glTF / GLB conversion and optimization.

## Tile creation (Community)

* [3D City Database](https://www.3dcitydb.org/) - Geo database to store, represent, and manage virtual 3D city models.
* [py3dtiles](https://gitlab.com/Oslandia/py3dtiles) - LAS / XYZ → 3D Point Cloud Tiles, b3dm API.
* [pg2b3dm](https://github.com/Geodan/pg2b3dm) - Conversion of PostGIS 3D geometries to b3dm tiles.
* [Obj2Tiles](https://github.com/OpenDroneMap/Obj2Tiles) - Converts OBJ files to OGC 3D tiles.
* [3dtiles](https://github.com/fanvanzh/3dtiles) - Tools for 3D-Tiles conversion.
* [Cesium Point Cloud Generator](https://github.com/tum-gis/cesium-point-cloud-generator) - XYZ → 3D Point Cloud Tiles.

## glTF tools

* [glTF-Transform](https://gltf-transform.donmccurdy.com/cli.html) - glTF-Transform supports reading, editing, and writing 3D models in glTF 2.0 format.

## Terrain

[Quantized Mesh](https://github.com/CesiumGS/quantized-mesh) is a format to encode terrain meshes for efficient client-side terrain rendering. Such files are supported in Cesium and deck.gl.

* [Cesium Terrain Builder](https://github.com/geo-data/cesium-terrain-builder) - DEM → Cesium Terrain Tiles (old format).
* [quantized-mesh-encoder](https://github.com/kylebarron/quantized-mesh-encoder) - A fast Python Quantized Mesh encoder.

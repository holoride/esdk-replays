# Real World holoride Recordings

To test the experience you're building for the holoride in different real world situations, we recorded a variety of drives for you that you can easily play back with the Elastic SDK and the holoride App.  
The recordings (ending with .holo2/holoraw) contain all the data a real world drive provides and thus can be seen as a real world test case.

## Table of Content

- [List of Recordings](#list-of-recordings)
- [Recording Categorization](#recording-categorization)
- [What's inside the zip?](#whats-inside-the-zip)

## List of Recordings

| Preview | Recording | Description | Travel Duration | Travel Speed | Area | Road Curvature | Further Notes |
|----|------------|-----|----|----|----|----| --- |
| [![Forrest and Villages](recordings/Forrest_Villages/preview.png)](recordings/Forrest_Villages/preview.png) | [Forrest and Villages](recordings/Forrest_Villages/Forrest_Villages.zip) | A ride through a forrest and two small villages | medium | medium | countryside | straight | - |
| [![Highway A99 Munich](recordings/Highway_A99_Munich/preview.png)](recordings/Highway_A99_Munich/preview.png) | [Highway A99 Munich](recordings/Highway_A99_Munich/Highway_A99_Munich.zip) | Ride along the A99 close to Munich including the start and finish next to the highway | medium | fast | highway | straight | multi-lane road |
| [![Ingolstadt Donaumoos](recordings/Ingolstadt_Donaumoos/preview.png)](recordings/Ingolstadt_Donaumoos/preview.png) | [Ingolstadt Donaumoos](recordings/Ingolstadt_Donaumoos/Ingolstadt_Donaumoos.zip) | A longer ride through the countryside | long | fast | countryside | straight, long bends | - |
| [![Kreta](recordings/Kreta/preview.png)](recordings/Kreta/preview.png) | [Kreta](recordings/Kreta/Kreta.zip) | A ride along the coastline of Kreta | medium | medium | highway | bendy | - |
| [![Leaving Munich](recordings/Leaving_Munich/preview.png)](recordings/Leaving_Munich/preview.png) | [Leaving Munich](recordings/Leaving_Munich/Leaving_Munich.zip) | Leaving the center of munich via a city highway | medium | slow -> fast | downtown + highway | some bends | - |
| [![Munich Leonrodplatz](recordings/Munich_Leonrodplatz/preview.png)](recordings/Munich_Leonrodplatz/preview.png) | [Munich Leonrodplatz](recordings/Munich_Leonrodplatz/Munich_Leonrodplatz.zip) | A short ride through a residential area in munich | short | slow | downtown | sharp corners | narrow roads |
| [![Through the heart of Munich](recordings/Through_Heart_Munich/preview.png)](recordings/Through_Heart_Munich/preview.png) | [Through the heart of Munich](recordings/Through_Heart_Munich/Through_Heart_Munich.zip) | A ride through the center of munich | medium | slow | downtown | some bends | - |
| [![Tuscany Fornace Valdalena](recordings/Tuscany_Fornace_Valdalena/preview.png)](recordings/Tuscany_Fornace_Valdalena/preview.png) | [Tuscany Fornace Valdalena](recordings/Tuscany_Fornace_Valdalena/Tuscany_Fornace_Valdalena.zip) | Small roads between hills and through villages | medium | medium  | countryside | bendy | narrow road |
| [![Tuscany Londa Fornace](recordings/Tuscany_Londa_Fornace/preview.png)](recordings/Tuscany_Londa_Fornace/preview.png) | [Tuscany Londa Fornace](recordings/Tuscany_Londa_Fornace/Tuscany_Londa_Fornace.zip) | Small roads between hills and through villages | medium | medium  | countryside | bendy | narrow road |

## Recording Categorization

Explanations to the table can be read below:

- Travel Duration
  - `short (< 10 minutes)`
  - `medium (10-30 minutes)`
  - `long (> 30 minutes)`
- Travel Speed
  - `slow (0-50 km/h)`
  - `medium (40-80 km/h)`
  - `fast (70+ km/h)`
- Area
  - `downtown`
  - `suburban`
  - `countryside`
  - `highway`
- Road Curvature
  - `(mostly) straight`
  - `some/many bends`
  - `sharp turns`

## What's inside the zip?

Each archive contains the following files

- A .holo2 file to be used by the Elastic SDK
- A .holoraw file to be used by the holoride App
- A .kml file describing the route (for tools like [this](https://ivanrublev.me/kml/))
- A preview .png image

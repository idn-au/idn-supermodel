# Component Models

This section lists the various Component Models within this Supermodel.

## Profiles

Many of the Component Models here are defined as a _profile_, by which we mean that it is a model that draws from other Standard's models and constrains and extends their elements, rather than creating its own elements.

Profiles are used to specialise general-purpose models while remaining conformant with them.
 
Formally, any data created according to a _profile_ _MUST_ conform to all the models it profiles, as per the [Profiles Vocabulary](background.md#profiles-vocabulary-prof) rules.

Profiles may profile multiple Standards, bringing together all the parts needed for a particular task

## List of Component Models

Several of the Component Models within this Supermodel are full defined here. Others are defined elsewhere and just referred to from here. The table below lists the current Component Models.

**Model** | **Domain(s)** | **Persistent Identifier** | **Notes**
--- | --- | --- | --- 
[Catalogue Profile](components/cp.md) | cataloging, dataset metadata | `https://w3id.org/idn/def/cp` | 
[Agents Governance Profile](components/agp.md) | people, organisations & their relations to each other and data | `https://w3id.org/idn/def/agp` |
[Fuzzy Geometries Profile](components/fgp.md) | fuzzy geometries for geospatial features | - | Coming...

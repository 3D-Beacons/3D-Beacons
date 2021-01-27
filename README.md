# 3D-Beacons

## Background
3D-Beacons is an open collaboration between providers of macromolecular structure models. The goal of this 
collaboration is to provide model coordinates and meta-information from all the contributing data resources in a standardized data format and on a unified platform.

![Image](https://raw.githubusercontent.com/3D-Beacons/3d-beacons-documentation/main/assets/3d-beacons-summary.png)

**Schematical overview of the 3D-Beacons infrastructure**

3D-Beacons consists of a Registry, a Hub and Beacons who host Clients. The Registry is used by the [3D-Beacons Hub](https://github.com/3D-Beacons/3d-beacons-hub-api) to look up which API endpoints are supported by the various Beacons. The Beacons provide data according to the 3D-Beacons data specifications ([Current version: 0.3.1](https://app.swaggerhub.com/apis/3dbeacons/3D-Beacons/0.3.1)). The Hub collates the data from the Beacons and expose it via Hub API endpoints.

### Current 3D-Beacons

- [FoldX](http://foldxsuite.crg.eu/)
- [Genome3D](http://genome3d.eu/)
- [Protein Data Bank in Europe](https://pdbe.org)
- [Protein Data Bank in Europe - Knowledge Base](https://pdbe-kb.org)
- [Protein Ensemble Database](https://proteinensemble.org/)
- [SWISS-MODEL](https://swissmodel.expasy.org/)

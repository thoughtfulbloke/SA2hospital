# SA2hospital

A csv file with the driving distance to every hospital for every SA2 statistical area. Deliberately made with open data licensed sources.

The fields in the csv are the distance in kilometres, the SA2 area, and the hospital (all 80 hospitals from the hospital source are included and people can use their own judgement about excluding various ones or building models where capacity collapses)

The route information comes from Open Street Map, via the geofabrik New Zealand specific .pbf download http://download.geofabrik.de/australia-oceania.html Open Street Map data is © OpenStreetMap contributors, licensed under the Open Data Commons Open Database License (ODbL) by the OpenStreetMap Foundation (OSMF). The New Zealand data is specifically from LINZ and licensed for reuse under CC BY 4.0.

SA2 centroids were obtained from Statistical Area 2 2018 (Centroid True) from Statsnz https://datafinder.stats.govt.nz/layer/93620-statistical-area-2-2018-centroid-true/ Creative commons licenced for resuse with attribution, Attribution 4.0 International (CC BY 4.0)

The Hospital data is the Public Hospital Subset of NZ Facilities from the National Topographic Office https://data.linz.govt.nz/layer/105588-nz-facilities/  Creative commons licenced for resuse with attribution, Attribution 4.0 International (CC BY 4.0)

Routes were calculated using the OSRM project backend https://github.com/Project-OSRM/osrm-backend, gratefully using their docker container instructions.


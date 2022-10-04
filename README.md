# France Overseas Geojson

This project contains the shape of French regions and departments in GeoJSON format.

In this project, coordinates of overseas regions and departments have been modified in order to allow plotting overseas and metropolitan regions next to each other. 

This project was inspired by [Gregoire David](https://github.com/gregoiredavid) repository [France-Geojson](https://github.com/gregoiredavid/france-geojson). Base Geojson have been downloaded from the same repository. 

## Organization of files 

- regions with overseas included
- departments with overseas included
- notebook 

## How the new coordinates have generated

- Coordinates of overseas region have been shifted to attach to "anchor points" close to metropolitan France.
- Guyane's size have been reduced by 55%
- Other overseas regions' size have then been increased by 200%

## Metadata 

To each territory is associated following properties:
- INSEE code 
- Region or department name

## Sources/ update 
- INSEE Code, territories' name (2018)
- See Gregoire David's France-Geojson repository [README](https://github.com/gregoiredavid/france-geojson/blob/master/README.md) for original sources 


## License

[Open-License](https://www.etalab.gouv.fr/licence-ouverte-open-licence/)
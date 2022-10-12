# ILIAD OGC SensorThings API 
OGC SensorThings API for ILIAD ocean twin project.
Source data is modelled according to the Ocean Information Model (OIM).
Data is retrieved from a semantic store (Virtuoso triplestore).

!! Methods require 'application/json' in accept header, i.e., -H "accept: application/json"

## Base Resource Path
```
https://w3id.org/iliad/api/v1.0
```
## Observations
### Retrieve all observations
```
https://w3id.org/iliad/api/v1.0/Observations
```
### Retrieve a specific Observation
```
https://w3id.org/iliad/api/v1.0/Observations(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Observations(3-10-361-Rhopilema%2520nomadica)
```
### Retrieve Observations for a specific Datastream.
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/Observations
```
For example:
```
https://w3id.org/iliad/api/v1.0/Datastreams(3-jellyFishAbundanceProperty)/Observations
```

## Datastreams
### Retrieve all the Datastreams
```
https://w3id.org/iliad/api/v1.0/Datastreams
```
### Retrieve a specific Datastream.
```
https://w3id.org/iliad/api/v1.0/Datastreams(id)
```
For example:
```
https://w3id.org/iliad/api/v1.0/Datastreams(3-jellyFishAbundanceProperty)
```
### Retrieve DataStream for a specific Observation
```
https://w3id.org/iliad/api/v1.0/Observations(id)/Datastream
```


## Features of Interest
### Retrieve all FeaturesOfInterest

### Retrieve a specific FeatureOfInterest

### Retrieve FeatureOfInterest for a specific Observation
```
https://w3id.org/iliad/api/v1.0/Observations(id)/FeatureOfInterest
```

## Observed properties
### Retrieve all the Observed properties

### Retrieve the ObservedProperty of a specific Datastream.
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/ObservedProperty
```

## Sensors
### Retrieve all Sensors

### Retrieve a specific Sensor

### Retrieve the Sensor of a specific Datastream.
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/Sensor
```

## Things
### Retrieve all Things

### Retrieve a specific Thing

### Retrieve the Thing of a specific Datastream.
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/Thing
```


For more information about OGC API please refer to:
* [GitHub repository](https://github.com/opengeospatial/sensorthings).
* [Test implementation](https://developers.sensorup.com/docs/#observations_get).


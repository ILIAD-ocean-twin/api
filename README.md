# ILIAD OGC SensorThings APIs template
OGC SensorThings API for ILIAD ocean twin project.
Source data is modelled according to the Ocean Information Model (OIM).
Data is retrieved from a semantic store (Virtuoso triplestore).

| :warning: Methods require 'application/json' in accept header, i.e., -H "accept: application/json"   |
|:-----------------------------------------------------------------------------------------------------|

## Table of Contents
- [ILIAD OGC SensorThings APIs template](#iliad-ogc-sensorthings-apis-template)
  - [Table of Contents](#table-of-contents)
  - [Base Resource Path](#base-resource-path)
  - [Observations](#observations)
    - [Retrieve all Observations](#retrieve-all-observations)
    - [Retrieve a specific Observation](#retrieve-a-specific-observation)
    - [Retrieve Observations for a specific Datastream](#retrieve-observations-for-a-specific-datastream)
  - [Datastreams](#datastreams)
    - [Retrieve all the Datastreams](#retrieve-all-the-datastreams)
    - [Retrieve a specific Datastream.](#retrieve-a-specific-datastream)
    - [Retrieve DataStream for a specific Observation](#retrieve-datastream-for-a-specific-observation)
  - [Features of Interest](#features-of-interest)
    - [Retrieve all FeaturesOfInterest](#retrieve-all-featuresofinterest)
    - [Retrieve a specific FeatureOfInterest](#retrieve-a-specific-featureofinterest)
    - [Retrieve FeatureOfInterest for a specific Observation](#retrieve-featureofinterest-for-a-specific-observation)
  - [Observed properties](#observed-properties)
    - [Retrieve all the Observed properties](#retrieve-all-the-observed-properties)
    - [Retrieve the ObservedProperty of a specific Datastream.](#retrieve-the-observedproperty-of-a-specific-datastream)
  - [Sensors](#sensors)
    - [Retrieve all Sensors](#retrieve-all-sensors)
    - [Retrieve a specific Sensor](#retrieve-a-specific-sensor)
    - [Retrieve the Sensor of a specific Datastream](#retrieve-the-sensor-of-a-specific-datastream)
  - [Things](#things)
    - [Retrieve all Things](#retrieve-all-things)
    - [Retrieve a specific Thing](#retrieve-a-specific-thing)
    - [Retrieve the Thing of a specific Datastream](#retrieve-the-thing-of-a-specific-datastream)



## Base Resource Path
```
https://w3id.org/iliad/api/v1.0
```
## Observations
### Retrieve all Observations
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
### Retrieve Observations for a specific Datastream
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

### Retrieve the Sensor of a specific Datastream
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/Sensor
```

## Things
### Retrieve all Things

### Retrieve a specific Thing

### Retrieve the Thing of a specific Datastream
```
https://w3id.org/iliad/api/v1.0//Datastreams(id)/Thing
```


For more information about OGC API please refer to:
* [GitHub repository](https://github.com/opengeospatial/sensorthings).
* [Test implementation](https://developers.sensorup.com/docs/#observations_get).


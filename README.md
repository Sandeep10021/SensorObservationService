# Sensor Observation Service

A SOS database and AJAX-based client for Sensor Observation Service (SOS).

The client have the following functionality:

* Read data should come from real world applications and visulaize using pie charts and bar graph

* Ablility to send various requests ( e.g. GetCapabilities,DescribeService etc) to a server.
* Ability to capture the response from the server and display: 
  1. The XML response document.
  2. Parse the XML and display only the values in table and other formats.
  
* Ability to create subsets of SOS data:
  1. Spatial subsetting (bounding box, overlap, containing, etc.)
  2. Temporal subsetting (After a time instant, during time instant, etc.)
  
* Ability to display the sensors data on the Google Map as markers.

# Use-JsonPowerDB-in-Web-pages

# About JsonPowerDB :
JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

# Benefits of using JsonPowerDB :
● Simplest way to retrieve data in a JSON format.

● Schema-free, Simple to use, Nimble and In-Memory database.

● It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.

● It is low level (raw) form of data and is also human readable.

● It helps developers in faster coding, in-turn reduces development cost.


# We used a javascript library jpdb-commons.js that is used to create requests and do ajax calls and help programmers to focus mainly on their page logic.

# And remove following two functions from the page: 
● createPUTRequest()
● executeCommand()

Use following javascript at the beginning below the other javascripts.
<script src="http://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js"></script>

Rename the method call "executeCommand()" in saveEmployee() method to executeCommandAtGivenBaseUrl()


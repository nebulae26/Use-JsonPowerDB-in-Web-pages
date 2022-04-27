# Use-JsonPowerDB-in-Web-pages

We used a javascript library jpdb-commons.js that is used to create requests and do ajax calls and help programmers to focus mainly on their page logic.

# And remove following two functions from the page: 
● createPUTRequest()
● executeCommand()

# Use following javascript at the beginning below the other javascripts.
<script src="http://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js"></script>

# Rename the method call "executeCommand()" in saveEmployee() method to executeCommandAtGivenBaseUrl()

# Eventhubs
ARM for Event Hub namespace and Event Hub with Access key &amp; capture to Storage account 


1. The script will create a reousrce group, EventHub Namespace and EventHub
2. It will enable throughputs and set auto inflate on EventHub Namespace
3. It will set the EventHub partitions, data retention days and creates authorization policy key on both EventHub Namespace and EventHub
4. Deploy.ps1 will have subid, resourcegroup info
5. Template.ps1 has the code to create the EventHub
6. Parameter.ps1 has the parameters

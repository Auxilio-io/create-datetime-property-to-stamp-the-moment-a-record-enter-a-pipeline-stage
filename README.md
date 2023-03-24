# create-datetime-property-to-stamp-the-moment-a-record-enter-a-pipeline-stage
CURL request to create a datetime property to stamp the moment a record enter a status in a HubSpot ticket pipeline


Unfortunately, HubSpot doesn't let you create a datetime property from the UI. Only date property can be created from the UI. You need to make a request to the property API in order to create a datetime property.

This can be usefull to create a datetime ticket property to stamp the moment a ticket enter a status in a HubSpot ticket pipeline.

All you need to do is:

1- Open post-request.curl in a text editor

2- Replace YOUR_ACCESS_TOKEN by your HubSpot Portal API Key

3- Replace NAME_OF_YOUR_STATUS by the name of the status you want to create time stamp property for

4- Replace OBJECT with the name of the object (e.g. ticket) or the ID of your custom object (e.g. 2-123456)

5- Repalce GROUP with the name of the property group where you want to nest the new datetime property

6- Copy and paste everything in the file into your computer's terminal


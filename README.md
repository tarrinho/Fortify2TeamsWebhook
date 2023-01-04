# Fortify2TeamsWebhook
Fortify 2 Teams Webhook

In order to have this Lambda function up and running in AWS you need to go to the Lambda area.
[](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image1.png)

After that, create a Function:
[](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image2.png)

Define a name for the Node.js code
[](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image3.png)

And in the Advanced Settings, enable Funtion URL with NONE Auth type
[](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image4.png)

After creating the function, you need to change the file name from index.mjs to index.js and copy the <lambda.nodejs> code to it. Don't forget to change the url and path to your Teams webhook. And finally, Deploy it.

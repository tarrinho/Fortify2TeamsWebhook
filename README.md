# Fortify2TeamsWebhook
After starting to use Fortify from Microfocus, and adding alot of projects and users we realize that we needed a way to share with everyone in Teams what was going on. So we decided to use the Webhook function from Teams/Fortify. However, their syntax don't match. Damn!!

So I decided to create this simple function : **Fortify 2 Teams Webhook**

In order to have this Lambda function up and running in AWS you need to go to the Lambda area.
![](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image1.png?raw=true)

After that, create a Function:
![](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image2.png?raw=true)

Define a name for the Node.js code
![](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image3.png?raw=true)

And in the Advanced Settings, enable Funtion URL with NONE Auth type
![](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/images/image4.png?raw=true)

After creating the function, you need to change the file name from index.mjs to index.js and copy the [lambda.nodejs](https://github.com/tarrinho/Fortify2TeamsWebhook/blob/main/lamda.nodejs) code to it. Don't forget to change the url and path to your Teams webhook. And finally, Deploy it.

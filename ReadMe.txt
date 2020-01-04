-------------------------------------
CONFIGURATION INSTRUCTIONS
-------------------------------------

MEANING CLOUD TEXT EXTRACTION API 
-------------------------------------
Please note this content app utilises meaning cloud text extraction API. You can find more information regarding the API here.
https://www.meaningcloud.com/developer/topics-extraction/doc


CREATE AN API KEY
-------------------------------------
You are required to create your own API Key to use within this content app. You can create an API Key here.
https://www.meaningcloud.com/developer/create-account - first register
https://www.meaningcloud.com/developer/account/subscriptions - then get your free API key here


ADD THE API KEY TO YOUR WEB.CONFIG
-------------------------------------
Once you have created an API Key you are required to add this to your web.config file within the <appSettings> section.
EG.

<appSettings>
  <add key="MeaningcloudApiKey" value="YOUR API KEY TO GO HERE" />
</appSettings> 


FREE API
-------------------------------------
This is pritty much free api with a coupel of limitations
1. Only a certain amount of languages are supported. I coded the app in a way to only use these languages anyway.
2. Max 20,000 request

I don't think you will need a paid version but here are the prices the last time I checked.
Startup - $99 - Max 120,000 request
Professional - $399 - MAX 700,000 request
Business - $999 - MAX 4,200,000 request


IMPORTANT! WHAT IS TEST MODE?
-------------------------------------
For the purpose of evaluating this content app I have added my own API Key. This is encrypted and compiled within a dll so you wont be able to see this in your web.config. 

If you don’t add an API key in your <appSettings> then this content app will assume you are using it for evaluation purposes. You will still have full functionality but there will be a red message at the top of the app reminding you that you’re still in ‘TestMode’. Once you add your API Key into your <appSettings> file then this message will disappear.

I’m happy for everyone to use my API Key for evaluation purposes but please do not abuse it. It actually comes with 20,000 requests per month so I think it should be enough for everyone to use.

Once you have reviewed the app then please try and create your own API Key as soon as possible.

If you need help with this, please don’t hesitate to drop me an email at.
david@recsitedesign.com


PLEASE SHOW YOUR APPRECIATION
-------------------------------------
If you like this content app then please feel free to show your appreciation by voting and leaving comments here.
https://our.umbraco.com/packages/backoffice-extensions/keyword-extractor-content-app/



WHERE TO REPORT ISSUES
-------------------------------------
You can either drop me an email at david@recsitedesign.com or you can log a issue at the following URL.
https://github.com/DavidArmitage/Umbraco8_KeywordExtractor_ContentApp/issues


LATEST VERSION
-------------------------------------
The latest version of the app can be found here
https://github.com/DavidArmitage/Umbraco8_KeywordExtractor_ContentApp



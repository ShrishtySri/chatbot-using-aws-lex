# chatbot-using-aws-lex
Designed and deployed a weather checking chatbot for any city using AWS lex.
In my chatbot, I have kept it simple with four intents (Greet, Good Bye, InquireWeather, and Weather inquiry). 
On Slots (variables in your utterances) Lex scores high as it comes with inbuilt enumerations or lists which cuts down your development work.
Used Weatherstack website which offers a free API for providing weather information for any given city. Sign in to it and get the API key, we will need it in the fulfillment event.
Then need to establish the connection from our chatbot to this API to retrieve the weather details for the user-provided city. We accomplish this goal using the AWS lambda function.
Testing can be done in your local environment on the test pane at the right side of the Lex console. Once your bot is developed, the remaining phases are Testing and Deployment.
Lex provides an out of box integration with multiple channels. We will use the Twillio option to integrate with the popular messaging platform -Whatsapp

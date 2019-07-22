### Train the NLU model

```rasa train nlu ```

Test the model:

```rasa shell nlu```

### Train the dialogue model

1. Start the custom action server by running:  

``` rasa run actions```  

2. Open a new terminal and train the Rasa Core model by running:  

``` rasa train```  

3. Talk to the chatbot once it's loaded after running:  
```rasa shell```  

### Starting the interactive training session:

1. Make sure the custom actions server is running:  

```rasa run actions```  

2. Start the interactive training session by running:  

```rasa interactive```  

### Chatbot on Slack:
2. Tokens are inside credentials.yml file  
3. Make sure custom actions server is running  
4. Start the agent by running `rasa run`
5. Start the ngrok on the port 5005 `ngrok http 5005 `  
6. Provide the url: https://your_ngrok_url/webhooks/slack/webhook to 'Event Subscriptions' page of the slack configuration.  
7. Talk to you bot.  

# ChatGPT Fine Tuning Experiments
My experiments fine tuning ChatGPT models using the OpenAi API.
<br>

## Experiments

- Exp_1 - Create training data and fine tune barbarabot on OpenAi<br>
https://github.com/vbookshelf/ChatGPT-Fine-Tuning-Experiments/tree/main/Exp_1-Create-data-and-fine-tune-barbarabot/Barbarabot-Fine-Tuning

## Lessons Learned
- When OpenAi updates a model, the  new model version does not respond to system messages in the same way that the old model version did. This changes the personality of a chatbot and changes the format of the responses that it outputs. This is a risk that needs to be managed. Fine tuning could be one way to mitigate this risk, because a fine tuned model is the developer's personal copy that does not (hopefully) get affected by OpenAi updates.
- New updates to a model reportedly improve it's steerability, safety and security. But I'm finding that newer versions also tend to become less human-like in their personalities. Older models were more human. Newer versions feel like machines that are trying to sound human. This is a factor to be considered when creating chatbots.

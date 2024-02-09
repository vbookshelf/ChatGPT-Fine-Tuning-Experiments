## Exp_1 - Create training data and fine tune barbarabot on OpenAi

### Objective
- Create training data for fine tuning
- Learn the OpenAi fine tuning workflow
  
### Notes
- I created a javascript web app to be able to create data by chatting with the chatbot.
- The chat history can be downoaded as a csv file and then used for training.
- The separator in the csv file needs to be manually changed from a comma ',' to a hash '#'.
- The fine tuning workflow is set out in the Jupyter Notebook.
- The training curve can be viewed on OpenAi by clicking on 'Finetuning'.
- The required format of the training data file has changed. Therefore, the jsonl file format explained in YouTube videos may no longer be accurate.

### Resources

- OpenAi Docs<br>
https://platform.openai.com/docs/guides/fine-tuning/preparing-your-dataset

- Check data format and estimate fine tuning costs<br>
https://cookbook.openai.com/examples/chat_finetuning_data_prep

- How to set fine tuning hyperparameters<br>
https://platform.openai.com/docs/api-reference/fine-tuning/create#fine-tuning-create-hyperparameters



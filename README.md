# Ask Dr.Berg (videos)

Ask Dr.Berg (videos) is a demonstration of the retrieval-augmented question-answering application.

We use two of Dr.Berg's YouTube videos as a corpus. 

So someone can ask questions and get answers in the context of the videos. E.g., Why is sugar consumption unhealthy?

![jupyter notebook](/question-answer_youtube-video-as-text//setup//demo/demo_qa_youtube_langchain.png)

## Stack
We use LangChain to organize the Large Language model (LLM) invocation and prompt.

## Run it yourself
This application assumes you have prior knowledge to set up a virtual environment for Python. After activating your virtual environment, you are ready to install the dependencies.

### Install dependencies 
Go to the Task folder, and run the following
```bash
make environment
```
This will install the dependencies from the requirements.txt file.

### Create your .env file
You can take as a reference the .env.example file to create your .env file.

### Get your OpenAi and Pinecone Api_keys
It is a must to have the OPENAI_API_KEY to have access to OpenAI LLM models. 

![OpenAI - Api key](/question-answer_youtube-video-as-text/setup/openai/openai_api_key.png)

Go to Pinecone to get the PINECONE_API_KEY to store the embeddings in the cloud.

![Pinecone - environment](/question-answer_youtube-video-as-text/setup/pinecone/pinecone_api_key.png)

Note: Both third-party services offer a free trial, so there is no cost for experimenting with these awesome technologies.

Finally, create an index in Pinecone.

![Pinecone - Create index](/question-answer_youtube-video-as-text/setup/pinecone/pinecone_create_index.png)

### Jupyter Notebook as a reference
To see the output of this application, check the jupyter notebook question-answer-youtube-video-as-text.ipynb inside the directory question-answer_youtube-video-as-text. 



# Text-Summarization

Text summarization generates a shorter version of a long text by retaining the core meaning. Text summarization is important nowadays due to the massive amount of textual data available on the internet and other sources. It also saves time as reading through lengthy documents or articles can be time-consuming and overwhelming. 

In Text_Summarization.ipynb file we are able to summarize the text from any given URL.

Here we scrape text from web using beatiful soup and python we perform 2 types of summarization
- Extractive text summarization - Here the entire content of web is divided into chunks and key information of each chunk is retrieved. This is done using hugging face summarization pipeline
- Abstractive text summarization - Here we use the pre-trained model and get the summary of the entire content. 

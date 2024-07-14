

<h1>Langchain Notes</h1>
<p>    Langchain is a development framework designed to streamline the creation of applications powered by Large Language Models (LLMs). It provides essential building blocks to simplify the development process.</p>
<h2>    L1-Model_prompt_parser</h2>


  <p> <strong>Prompt Templates : </strong> LangChain's prompt templates facilitate the creation of instructions for LLMs. This functionality is crucial for efficiently formatting, organizing, and reusing prompts across applications.</p>


  <p> <strong>Output Parsers :  </strong>LangChain's output parsers convert LLM completions into structured formats, enabling easier extraction and interpretation of meaningful information from model outputs.</p>
<h2>    L3-Memory</h2>


<p> Every input to an LLM is stateless i.e. every interaction is independent and it does not remember any information from previous conversations.This could be problem if we want to build applications like Chatbots.
Chatbots appear to have memory buffer by providing previous context as input along with each interaction. Langchain provides various functionalities to store, format and manipulate this memory buffer. </p>
<h2>    L3-Chains</h2>


<p> Handling diverse queries needs multiple sequences of text processing and intergration. Langchain's chains helps for efficient stream line integration</p>
<h2>    L4-QnA</h2>


<p> Integrating LLM applications with external documents such as PDFs, Web pages  enhances their capabilities.Embedding models create vector representations of text, allowing efficient comparison and retrieval of similar content. Vector databases store these embeddings and associated text chunks.</p>
<p> When queried, the system embeds the query, compares it to stored vectors, and retrieves relevant text for the LLM. </p>
<p> Retrieval methods include: </p>
<p>   <strong>1.Stuff :</strong> Simple, single call, limited by context length. </p>
<p>   <strong>2.Map reduce :</strong> Parallel processing, summarizing responses, more calls required. </p>
<p>   <strong>3.Refine :</strong> Iterative building of answers, slower. </p>
<p>   <strong>4.Map rerank :</strong> Scores and ranks answers for relevance. </p>
</body>

</html>

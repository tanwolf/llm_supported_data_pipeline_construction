# LLMs and Data Pipelines: An Iterative Approach

_Abstract: Large language models (LLMs) have the potential to revolutionize data engineering making it a manageable process even for non-data scientists. Introducing LLMs into data engineering, however, brings new challenges such as a need for constant verification and quality control. In order to tackle such a process I have designed a methodology for using LLMs to build data pipelines. I demonstrate the methodology by giving the example of a mixed methods research process combined with NLP and GPT._


## Data Engineering with LLMs 

Since the release of ChatGPT in November 2022 access to a Large Language Model (LLM) has been readily available for the first time. GPT-3.5 (Generative Pre-trained Transformer 3.5), the underlying LLM of ChatGPT can provide impressive support in the translation of ideas, needs, and requirements into functional data pipelines. GPT-3.5 makes knowledge readily available and allows for immediate application of generated code. As a reasoning engine, GPT-3.5 can give advice on how to set up IDEs, software, and python libraries according to a project’s requirements. This allows even non-data engineers to build complex data pipelines.  

## Increasing Need for Verification and Quality Control 

With the reduced technical challenges, the task of achieving the best possible data flow has become a lot more feasible. This is because time can be allocated to run shorter, more frequent, and focused iterations concerning the desired outputs of the pipeline. However, while data engineering has become significantly easier, building data pipelines with the support of LLMs requires systematic verification, documentation and quality control. Not only for the validity and reliability of the LLMs’ responses, but also concerning the generated code and the desired output of the pipeline. This is because LLMs can generate biased or inaccurate results. The liability for the LLMs’ responses however, lies with the humans who use them. 

## Iterative Methodology for LLM supported Data Pipeline Construction 

In order to streamline the process of constructing a data pipeline with the support of an LLM, I have developed a respective iterative methodology, an example of which can be found in this [flow chart](https://miro.com/app/board/uXjVM5oQRrU=/?share_link_id=552570215729) . The flow chart depicts a process supported by ChatGPT Plus (GPT-4). It also includes two accompanying OneNote notebooks. The first notebook is used as a primary project workspace. The second notebook captures thoughts and ideas that arise during the project but are out-of-scope. The latter notebook will be used to develop ideas for multiple use of the project and it’s data as well as for documenting best practices.  

## Case Study: PhD Thesis Process Using Mixed Methods, NLP, and GPT 

The flow chart provides a case study of crafting a PHD thesis using mixed methods research, NLP, and GPT given the technical possibilities as of July 2023. Although it illustrates my personal approach and stack, it can be configured according to each project’s needs and constraints, including considerations for the use of GPT, data privacy, and security. I want to emphasize that the proposed data pipeline in this project was not built around sensitive data. Respective laws and regulations have to be considered for each project individually.  

## Incorporating Lessons from Recent and Past Project Experiences 

The flow chart is based on experiences from a [recent project](https://github.com/tanwolf/NLP_Requirements-Engineering) where I used ChatGPT Plus (GPT-4) to interpret the outcomes of classical NLP tasks, such as Latent Dirichlet Allocation (LDA) and entity recognition. I found that pairing NLP with GPT4 comes close to qualitative data analysis and mixed methods research, especially concerning the naming of LDA topics and the interpretation of the combined findings from LDA and entity recognition.   

Mixed methods research analyses qualitative as well as quantitative data in various formats. In order to design the a flow chart of the research process I contrasted the recent project to my [diploma thesis](quadripolar_identity_model.pdf)  for which I used qualitative data analysis, well before the advent of modern-day data science and NLG.  

Having gone through a qualitative data analysis process without sophisticated software, made me understand that the main challenge is to prevent cognitive overload. Due to the multitude of unstructured data, various data types and formats, it is very challenging to put them into relation to each other and sum up findings. This difficulty increases with the size of the data or datasets.  

## Streamlining LLM supported Mixed Methods Research 

As mentioned above incorporating LLMs into the construction of data pipelines requires systematic verification, documentation, and quality control. When adding mixed methods to this process this need only increases. In order to address this challenge the research process depicted in my flow chart aims to streamline the process of LLM supported construction of data pipelines. This is achieved by pairing the process with qualitative data analysis software, referencing software, iterative project management and seamless documentation.  

One of the main goals of the depicted project management process is to prevent cognitive overload of the researcher. Cognitive overload can potentiall result in either system overload or an unfinished data pipeline or project. In order to prevent this, a dedicated home is given to each and every random thought or idea that might arise during the research process. Taking notes frees up the mind and lays a foundation for project documentation. It also makes the process manageable and transparent: Notes can be transformed from Random Thoughts into To Dos, into lists of stakeholders or Relevant Resources. It is key to de-clutter and restructure only those notes that are relevant for the task at hand. In addition, regular rounds of cleaning up are foreseen after every few iterations. While this research process is still a challenging endeavour, it allows for short, focused iterations, and regular quality control.  

Given the current speed of advancements in the field of LLMs I am expecting the depicted process to become ever more simple over the course of the next few years. This is because more and more software applications are beginning to incorporate LLMs into its software. For example, the MaxQDA qualitative data analysis software already has an AI Assist function. A Copilot function for Microsoft OneNote has been announced. Furthermore as of July 2023 google’s LLM BARD is publicly available in most countries of the world. BARD and ChatGPT in combination can be used to verify the responses of each LLM. 

## Mixed Methods Research, NLP and LLMs 

Qualitative data analsysis, mixed methods research as well as NLP aim to derive insights from unstructured data. They also typically involve data in various formats like pdf documents, video and audio files, written transcripts, or even handwritten notes. Ingesting various file formats and integrating qualitative and quantitative data into a research process is challenging, time consuming and potentially expensive. Integrating LLMs into these processes reduces technical challenges and speeds up processes. This in turn can create additional time to build more complex data pipelines, ingest even more divers data, tackle larger data sets or engage in more complex data manipulations.  

Incorporating LLMs into NLP scripts like the openAi API allows for new approaches in qualitative data analysis, e.g. for qualitative coding and summarizing large numbers of documents such as interview transcripts. While this will make double checking the results of GPT transformations a crucial part of the research process, researchers also gain time for the interpretation of the data and for critical thinking. E.g. a lot of time is won by not having to train a machine learning model on how to  process interview transcripts. GPT can perform tasks such as summarizing, qualitative coding, entity or topic recognition on any text when given appropriate context. It can even generate tables or code to further process extracted entities within an IDE. Using python libraries such as LangChain enables looping GPT over dataframes or parsing outputs of prompts.   

## From Niche to Mainstream

Qualitative data analysis has traditionally been a niche method known predominantely amongst anthropologists. Its approach of qualitative coding within software such as MaxQDA strongly resembles the IDEs used in computer and data science. The method is also close to annotating text data for supervised machine learning.  

Knowing how to analyze different file formats from qualitative and quantitative points of view will become ever more important in the near future. This is because information today is no longer passed on primarily through books or newspapers: E.g. news are increasingly generated through social media, knowledge is passed on via video tutorials and discussions take place in podcasts. This increases the need for humans to critically assess all of these information. In addition, LLMs are breaking technical barriers for and closing technical knowledge gaps of content creators. As a result, I am expecting more voices to be heard via social media in the near future. Voices which were too vulnerable to participate in discussions before the introduction of publicly available LLMs. I am also expecting an increase of LLM-generated content which humans will have to assess critically. 

**Links:**

* Flow Chart: [LLMs and Data Pipelines](https://miro.com/app/board/uXjVM5oQRrU=/?share_link_id=552570215729)
* Previous Porject: [Applying NLP in Requirements Engineering](https://github.com/tanwolf/NLP_Requirements-Engineering)
* Diploma Thesis: ["Om sa fii"]([https://1drv.ms/b/s!AsSD_ioRrpmai0sJQoGWyQRoxWCR?e=DNDUSY](https://1drv.ms/b/s!AsSD_ioRrpmai0sJQoGWyQRoxWCR?e=YsP6K0))
* OneNote Project Template: [Project Template](https://1drv.ms/o/s!AsSD_ioRrpmaizbbmHbAn16xLTOR?e=Y2dPks)
* OneNote Project Management Template: [ Project Management Template](https://1drv.ms/o/s!AsSD_ioRrpmaiyVo9dKR6ndVQ26N?e=fOYugo)

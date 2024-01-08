# LLM-Email-Thread-Summarization-Comparison
NLP models reading and summarizing chains of over 30 emails beats reading them yourself!
## Purpose
The goal of this project was to compare and contrast the different summarization capabilities of transformer-based language models. In undertaking this project, my group and I employed the HuggingFace and OpenAI APIs to directly compare an untuned T5 model, a BERTScore and ROUGE fine-tuned T5 model, and a BERTScore and ROUGE fine-tuned GPT-3.5-Turbo model. Additionally, we evaluate the performance metrics after finding discrepencies between strong numerical performance and weak human assessment, adding our own evaluation metric as an extension.

We largely undertake this project as a means to gain experience with cutting-edge NLP technologies within a direct business application. Further investigations may create a summary tool using OpenAI APIs to provide a direct summary of a long email thread that is constantly updated.
## Languages
- Python (Jupyter Notebook)
## Set-Up Guide
In order to run the code, download the .zip files containg the long and short data as well as each individual Jupyter Notebook; upload them into a Google Drive folder. Mount each notebook within your Drive to access the data directly, and "Run All." In order to run the GPT fine-tuning, you will need to create your own OpenAI API key.

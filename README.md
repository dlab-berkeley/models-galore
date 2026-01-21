# D-Lab Models Galore: A Field Guide to Model Specs Workshop

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)
[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab's Models Galore: A Field Guide to Model Specs workshop. 

Check out D-Lab’s [Workshop Catalog](https://dlab-berkeley.github.io/dlab-workshops/) to browse all workshops, see what’s running now, and review prerequisites.

## Workshop Goals

This workshop builds "model literacy” for anyone who has browsed OpenRouter, Hugging Face, or vendor pages and wondered what the specs actually imply in practice. Participants will learn how to interpret the most common model labels and tradeoffs—base vs instruction-tuned (and what “chat” really means), quantized vs full precision, distilled vs original, and mixture-of-experts vs dense models. We’ll connect these concepts to real decisions: capability vs cost, latency vs quality, context length vs reliability, and parameter count vs “felt” performance. We’ll also demystify evaluation: what benchmark scores do and don’t tell you, how to spot mismatched evals (chat vs base, tool-use vs no tool-use), and how to run quick, task-relevant checks using input→output behavior. The goal is that you leave able to compare models confidently and pick the right one for a given use case.

## Learning Objectives

After this workshop, you will be able to:

- Interpret common model specifications (base vs. instruction-tuned, quantized vs. full precision, dense vs. mixture-of-experts) and understand their practical implications for performance and cost.
- Evaluate tradeoffs between capability, latency, context length, and resource requirements when selecting a model for a specific task.
- Critically assess benchmark scores and evaluation metrics, recognizing when comparisons are valid and when they may be misleading.
- Apply quick, task-relevant checks to compare model outputs and make informed decisions about which model fits your use case.

This workshop does not cover the following:

- Prompt engineering techniques. These are covered in [Prompt Engineering](https://github.com/dlab-berkeley/prompt-engineering).
- Fundamentals of LLM architecture. This is covered in [Python GPT Fundamentals](https://github.com/dlab-berkeley/Python-GPT-Fundamentals).
- Using LLMs for exploratory research workflows. These are covered in [LLMs for Exploratory Research](https://github.com/dlab-berkeley/LLMs-Exploratory-Research).
- Accessing LLMs via API. These are covered in [Python APIs for Large Language Models](https://github.com/dlab-berkeley/Python-APIs-for-Large-Language-Models).

## Installation Instructions

Anaconda is a useful package management software that allows you to run Python and Jupyter notebooks very easily. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda](https://www.anaconda.com/download). 

2. Download the [Models Galore](https://github.com/dlab-berkeley/models-galore):

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time. 

2. Click the "Launch" button under "Jupyter Notebooks" and navigate through your file system to the `models-galore` folder you downloaded above.

## Is Python not Working on Your Computer?

If you do not have Python installed and the materials loaded on your
workshop by the time it starts, we *strongly* recommend using the UC Berkeley
Datahub to run the materials for these lessons. You can access the DataHub by
clicking the following button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)

The DataHub downloads this repository, along with any necessary packages, and
allows you to run the materials in an RStudio instance on UC Berkeley's servers.
No installation is necessary from your end - you only need an internet browser
and a CalNet ID to log in. By using the DataHub, you can save your work and come
back to it at any time. When you want to return to your saved work, just go
straight to the [D-Lab DataHub](https://dlab.datahub.berkeley.edu), sign in, and
you click on the `[Workshop-Name]` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)

By using this button, however, you cannot save your work.


## Run the Code

Now that you have all the required software and materials, you need to run the code:

Provide instructions on running the code, including how to load relevant software (RStudio, Jupyter Notebooks, etc.) and which file to open up. See other repositories for examples.

Additionally, provide instructions on how to run code once it’s open (running Jupyter cells, RMarkdown cells, etc.).


# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab AI Workshops

Here are other AI workshops offered by the D-Lab:

## Basic Competency

- [Getting Started With AI](https://github.com/dlab-berkeley/Getting-Started-With-AI)
- [Demystifying AI](https://github.com/dlab-berkeley/Demystifying-AI)
- [AI-Assisted Coding In Python](https://github.com/dlab-berkeley/AI-Assisted-Coding-In-Python)
- [AI-Assisted Coding In R](https://github.com/dlab-berkeley/AI-Assisted-Coding-In-R)

## Intermediate/Advanced Competency

- [Python GPT Fundamentals](https://github.com/dlab-berkeley/Python-GPT-Fundamentals)
- [Python APIs for Large Language Models](https://github.com/dlab-berkeley/Python-APIs-for-Large-Language-Models)
- [LLMs for Exploratory Research](https://github.com/dlab-berkeley/LLMs-Exploratory-Research)

# Contributors

- Sohail Khan
- Tom van Nuenen

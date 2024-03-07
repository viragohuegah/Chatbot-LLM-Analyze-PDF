# Chatbot-LLM-Analyze-PDF

<br>Mentee assignment from IBM Advance AI @ Infinite Learning Course completion of Build a Chatbot to Analyze PDF Files using LLM from [IBM Skills Network](https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lORC1HUFhYME5TOEVOL2xhYnMvQnVpbGRfYV9DaGF0Ym90X3dpdGhfRmxhc2tfYW5kX1B5dGhvbi5tZCIsInRvb2xfdHlwZSI6Imluc3RydWN0aW9uYWwtbGFiIiwiYWRtaW4iOmZhbHNlLCJpYXQiOjE3MDk3NDg3NzZ9.swnkTB9mWw45lyAC5-5s_bBs2C9RKh9CYZsJHatTlZk)

We will creating PDF Analyzer Chatbot  
<center> <img src="/build_chatbot_for_your_data/preview/preview_light.png"> </center>
<center> <img src="/build_chatbot_for_your_data/preview/preview_dark.png"> </center>



## Table of Contents
1. [Mentee Info](#mentee-info)
2. [Technology](#technology)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Structure](#structure)
6. [Project Status](#project-status)
7. [Instructors](#instructors)


<a name="mentee-info"></a>
## Mentee Info
| Nama             | Program              |
| ---------------- | -------------------- |
| Rizqi Hairunnisa | IBM Advance AI 🤖🌊 |



<a name="technology"></a>
## Technology
- `python`
- `langchain`
- `langchain_openai` 
- `gradio`
- `chromadb`
- `tiktoken`
- `huggingface_hub`
- `wget`
- `pysqlite3-binary`
- `numexpr`
- `langchain_experimental`


<a name="setup"></a>
## Setup
You can setup your project by cloning this repository and install the libraries above.

For specific version of the libraries, please check the `my.env` directory. You can activate the libraries by using the command below.

```bash
source my_env/bin/activate
```

<a name="usage"></a>

## Usage
You can run each of the program by using the command below. For better GUI run on `Public URL`. Don't forget to insert your API Key.

- Simple Chatbot
```bash
python simple_llm.py
```
- Cover Letter Chatbot
```bash
python prompt_with_template.py
```

exercise output step by step,
```bash
python exercise_prompt_step_by_step.py
```

- Customer Support Bot
```bash
python chain_customerSupport.py
```

- Summarizer Chatbot
```bash
python summarizer.py
```

- Friend Chatbot
```bash
python memory.py
```

- Python Code Writer Bot
```bash
python coderunner.py
```

<a name="structure"></a>
## Structure
```bash
.
├── README.md
├── chain_customerSupport.py
├── coderunner.py
├── exercise_prompt_step_by_step.py
├── flagged
│   └── log.csv
├── hello.py
├── memory.py
├── my_env
│   ├── bin
│   ├── include
│   ├── lib
│   ├── pyvenv.cfg
│   └── share
├── pembukaanUUD1945.txt
├── preview_chatbot
│   ├── preview_coderunner.png
│   ├── preview_coverletter.png
│   ├── preview_customersupport.png
│   ├── preview_excercise.png
│   ├── preview_friend_chatbot.png
│   ├── preview_simple_chatbot.png
│   └── preview_summarizer.png
├── prompt_with_template.py
├── simple_llm.py
└── summarizer.py

```

<a name="project-status"></a>
## Project Status
Project is: _complete_

<a name="instructors"></a>
## Instructors
- [@Ichsan Takwa](https://github.com/Ichsan-Takwa)

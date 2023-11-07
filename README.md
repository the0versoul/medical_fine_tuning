# Fine-Tuning an LLM: Medical Test Performance (Before and After)

This repo is designed as a starter kit to fine-tuning. Fine-tuning has a ton of useful applications, from changing the tone of the LLM, incorporating a specific vernacular or body of language into the LLM, or having the LLM "specialize" in a certain area. Therefore this is an important area of understanding for fully leveraging LLMs. 

We're going to be trying to get the LLM to pass a medical entrance exam as an example. See the description: 

_MedMCQA is a large-scale, Multiple-Choice Question Answering (MCQA) dataset designed to address real-world medical entrance exam questions._

_MedMCQA has more than 194k high-quality AIIMS & NEET PG entrance exam MCQs covering 2.4k healthcare topics and 21 medical subjects are collected with an average token length of 12.77 and high topical diversity._

_Each sample contains a question, correct answer(s), and other options which require a deeper language understanding as it tests the 10+ reasoning abilities of a model across a wide range of medical subjects & topics. A detailed explanation of the solution, along with the above information, is provided in this study._

_MedMCQA provides an open-source dataset for the Natural Language Processing community. It is expected that this dataset would facilitate future research toward achieving better QA systems. The dataset contains questions about the following topics:_

- The dataset can be found here: https://huggingface.co/datasets/medmcqa
- Papers with Code link: https://paperswithcode.com/dataset/medmcqa
- Dataset on Github for Download: https://github.com/MedMCQA/MedMCQA

We are going to be using GPT3.5 for this purpose in order to keep things simple for now (no custom LLMs). OpenAI makes this process relatively straightforward. 

Follow along in the notebook for an intuitive guide to fine-tuning!

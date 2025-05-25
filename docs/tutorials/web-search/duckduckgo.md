---
sidebar_position: 3
title: "DuckDuckGo"
---

:::warning
This tutorial is a community contribution and is not supported by the Open WebUI team. It serves only as a demonstration on how to customize Open WebUI for your specific use case. Want to contribute? Check out the contributing tutorial.
:::

## DuckDuckGo API

### Setup

No setup is required to use DuckDuckGo API for Open WebUI's built in web search! DuckDuckGo works out of the box in Open WebUI. 

### This explanation of how to use web search is like looking up zebra in the dictionary and it says 'a zebra is a zebra', or instructions for driving a car ...'you drive it'. 
### Incredibly creative people wrote this software, but no one wrote "To use web search, you should write a query in roughly the following form: '*#? search the web for information about the new Pope' . The first 3 characters will automatically invoke the web search tool and the remainder of the request will be interpreted by the LLM (model) that you have assigned to implement the tool and carry out a search for relevant information using the DuckDuckGo search engine. It is not necessary to put the request in quotes. Quotes around the request will be ignored. The form of the request is strict. The first 3 characters (*#?) must be followed by a space and then a recognizable request to the LLM for specific information to be found by a web search."  
### Yes, these SAMPLE instructions are contradictory, incomplete and self inconsistent. That is because I have searched every possible document and Readme and social media outlet and even used DuckDuckGo and asked LLama4:scout and GH Copilot how to use web search. I never found clear instructions about HOW to do it. 
### I have the same complaint about how to add documents to the RAG database (i'm not even sure that is a sensibly constructed complaint. I'm fairly sure that a database can be part of the RAG pipeline, but the method of implementing a RAG query or adding information for the LLM to use in RAG, either by submitting a file or through websearch is still a complete mystery to me.). 
### Please please please will/Can some wonderful intelligent person just write a succinct set of instructions with short examples and allowed syntax for using the functions in open-webui? I don't know python. Linux still confuses me. I only know how to type a question in the chat box and read the reply. Do I need to use / or * or #? I learned to read 'Alice in Wonderland' when I was 5. I hope I'm not too old to learn this. 

:::note
There is a non-zero probability of your web searches being rate limited.
:::

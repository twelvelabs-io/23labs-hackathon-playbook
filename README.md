# 23labs-hackathon-playbook
Playbooks for 23 Labs Hackathon. Let's play with Twelve Labs' multimodal AI APIs!

![banner](https://github.com/twelvelabs-io/23labs-hackathon-playbook/assets/117253278/f892a3ab-3a2f-4951-9389-0f62044144d3)

[![Discord](https://badgen.net/badge/twelvelabs/discord?icon=discord&color=orange)](https://discord.gg/G7dycMHkU6)
[![Twitter](https://badgen.net/badge/twelvelabs/twitter?icon=twitter&color=orange)](https://twitter.com/twelve_labs)


## Introduction
Twelve Labs Video Understanding Platform, currently in beta, offers an API suite for integrating a state-of-the-art (“SOTA”) foundation model that understands contextual information from your videos, making it accessible to your applications. The API is organized around REST and is compatible with most programming languages. You can also use Postman or other REST clients to send requests and view responses.

The following diagram illustrates the architecture of the Twelve Labs Video Understanding Platform and how different parts interact:

![](https://files.readme.io/5fb7a80-image.png)

## Prerequisite
- Python
- Environment to run Jupyter Notebook(.ipynb). Here's the [reference link](https://docs.jupyter.org/en/latest/install.html) for jupyter notebook.
- Twelve Labs Account. Here's the link for [sign up](https://api.twelvelabs.io) for a free account, or if you already have one, [sign in](https://api.twelvelabs.io).

## Playbooks
This demo will use an existing account. To make calls to the API, you need your secret key and specify the URL of the API. You can use environment variables to pass configuration to your application.

1. [Ads Demo](./Twelve_Labs_API_Ads_Demo.ipynb)
2. [Content Creator Demo](./Twelve_Labs_API_Content_Creator_Demo.ipynb)
3. [E-Learning Demo](./Twelve_Labs_API_E_Learning_Demo.ipynb)
4. [Sports Demo](./Twelve_Labs_API_Sports_Demo.ipynb)


## Example Apps
1. [Summarize a Youtube Video](https://github.com/mrnkim/Summarize-a-Youtube-Video)
2. [Generate hashtags and titles for your video](https://github.com/mrnkim/Generate-Titles-and-Hashtags-for-Your-Video#generate-titles-and-hashtags-for-your-video)
3. [Generate social posts for your video](https://github.com/mrnkim/Generate-Social-Posts-for-Your-Video)
4. [Who talked about us? (Vid Analyzer)](https://github.com/mrnkim/vid-analyzer-react)

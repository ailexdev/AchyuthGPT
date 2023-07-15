---
title: AchyuthGPT v2
emoji: 🚀
colorFrom: red
colorTo: yellow
sdk: docker
sdk_version: 1.24.0
app_file: run.py
pinned: true
---

# AchyuthGPT

## Models
- gpt-3.5-turbo
- gpt-3.5-turbo-poe
- gpt-3.5-turbo-openai
- gpt-3.5-turbo-16k
- gpt-3.5-turbo-16k-openai
- gpt-3.5-turbo-16k-poe
- gpt-4
- gpt-4-0613
- gpt-4-poe
- gpt-4-32k
- gpt-4-32k-poe
- claude_instant
- claude-instant-100k
- claude-2-100k

<br>


## Table of Contents  
- [Getting Started](#getting-started-white_check_mark)  
  - [Cloning the Repository](#cloning-the-repository-inbox_tray)  
  - [Install Dependencies](#install-dependencies-wrench)  
- [Running the Application](#running-the-application-rocket)  
- [Docker](#docker-)  
  - [Prerequisites](#prerequisites)  
  - [Running the Docker](#running-the-docker)
- [Incorporated Projects](#incorporated-projects-busts_in_silhouette)
  - [WebUI](#webui) 
  - [API AchyuthGPT](#api-g4f)
- [Star History](#star-history)
- [Legal Notice](#legal-notice) 

##

# Getting Started :white_check_mark:  
To get started with this project, you'll need to clone the repository and have [Python](https://www.python.org/downloads/) installed on your system.  
  
## Cloning the Repository :inbox_tray:
Run the following command to clone the repository:  

```
git clone https://github.com/achyuth4/AchyuthGPT
```

### Switching to the Achyuthgpt Branch :arrows_counterclockwise:
Run the following command to switch to the achyuthgpt-version branch:
```
git checkout achyuthgpt-version  
```

## Install Dependencies :wrench: 
In the project directory, install the dependencies:
```
pip install -r requirements.txt
```

## Setting up the API Key and .env :key:
Before starting the application, no need to obtain an API key, just set up the .env file.


### Create .env
In the project directory, create a file called .env.
Open the .env file and add the following line:
```

## Running the Application :rocket:
To run the application, run the following command:
```
python run.py
```

Access the application in your browser using the URL:
```
http://127.0.0.1:1338
```
or
```
http://localhost:1338
```

## Docker 🐳
### Prerequisites
Before you start, make sure you have installed [Docker](https://www.docker.com/get-started) on your machine.

### Discord
[AchyuthGPT Discord](https://discord.gg/wnH6eGx7JF)
### Running the Docker
Pull the Docker image from Docker Hub:
```
docker pull achyuth4/AchyuthGPT-v2
```

Run the application using Docker:
```
docker run -p 1338:1338
```

Access the application in your browser using the URL:
```
http://127.0.0.1:1338
```
or
```
http://localhost:1338
```

When you're done using the application, stop the Docker containers using the following command:
```
docker stop <container-id>
```

## Incorporated Projects :busts_in_silhouette:
I highly recommend visiting and supporting both projects.

### AchyuthGPT
The free API was incorporated from the [AchyuthGPT](https://achyuthgpt.adventblocks.cc/).

### WebUI
The application interface was incorporated from the [chatgpt-clone](https://github.com/xtekky/chatgpt-clone).

### API G4F
The API controller has been built in from [GPT4Free](https://github.com/xtekky/gpt4free).

<br>

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=ramonvc/freegpt-webui&type=Timeline)](https://star-history.com/#ramonvc/freegpt-webui&Timeline)

<br>

## Legal Notice
This repository is _not_ associated with or endorsed by providers of the APIs contained in this GitHub repository. This
project is intended **for educational purposes only**. This is just a little personal project. Sites may contact me to
improve their security or request the removal of their site from this repository.

Please note the following:

1. **Disclaimer**: The APIs, services, and trademarks mentioned in this repository belong to their respective owners.
   This project is _not_ claiming any right over them nor is it affiliated with or endorsed by any of the providers
   mentioned.

2. **Responsibility**: The author of this repository is _not_ responsible for any consequences, damages, or losses
   arising from the use or misuse of this repository or the content provided by the third-party APIs. Users are solely
   responsible for their actions and any repercussions that may follow. We strongly recommend the users to follow the
   TOS of the each Website.

3. **Educational Purposes Only**: This repository and its content are provided strictly for educational purposes. By
   using the information and code provided, users acknowledge that they are using the APIs and models at their own risk
   and agree to comply with any applicable laws and regulations.

4. **Copyright**: All content in this repository, including but not limited to code, images, and documentation, is the
   intellectual property of the repository author, unless otherwise stated. Unauthorized copying, distribution, or use
   of any content in this repository is strictly prohibited without the express written consent of the repository
   author.

5. **Indemnification**: Users agree to indemnify, defend, and hold harmless the author of this repository from and
   against any and all claims, liabilities, damages, losses, or expenses, including legal fees and costs, arising out of
   or in any way connected with their use or misuse of this repository, its content, or related third-party APIs.

6. **Updates and Changes**: The author reserves the right to modify, update, or remove any content, information, or
   features in this repository at any time without prior notice. Users are responsible for regularly reviewing the
   content and any changes made to this repository.

By using this repository or any code related to it, you agree to these terms. The author is not responsible for any
copies, forks, or reuploads made by other users. This is the author's only account and repository. To prevent
impersonation or irresponsible actions, you may comply with the GNU GPL license this Repository uses.

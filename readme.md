# MCQ Generator

## Description
This project is a multiple-choice question (MCQ) generator leveraging OpenAI, Hugging Face, and LangChain technologies.

## Initial Setup for Runing project in VSCode

### Installing Python Extension in Visual Studio Code

To install the Python extension in Visual Studio Code, follow these steps:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon in the sidebar or pressing `Ctrl+Shift+X`.
3. Search for "Python" in the Extensions Marketplace.
4. Click on the "Install" button next to the Python extension.

### Setting Up Base Environment in Git Bash

To set up a base environment in Git Bash, follow these steps:

1. Open Git Bash.
2. Enter the following command to initialize Conda in Bash:
   
   ```bash
   conda init bash
   ``` 

3. Enter the following in Bash:
   
   ```bash
echo '. ${HOME}/.bash_profile' >> ~/.bashrc
   ``` 

4. Restart Git Bash

5. Run the following command to create the environment:
   
   ```bash
conda create -p env python=3.8 -y
   ``` 
6. Activate the environment by running:

   ```bash
source activate ./env
   ``` 





## How to Run
### 1. Install Packages
First, ensure you have all the required packages installed. You can do this by running the following command:

```bash
pip install -r requirements.txt -v
```

or

```bash
python setup.py install
```


### 2. Set Up .env File
Before running the application, you need to set up your environment variables in a `.env` file. Follow the steps below:

#### Get OpenAI API Key
You need to obtain an API key from OpenAI to access their services.

#### Set Environment Variable
Create a `.env` file in the root directory of the project and add the following line:

```
OPEN_API_KEY = <"PASTE YOUR OPENAI API KEY HERE">
```

Replace `<"PASTE YOUR OPENAI API KEY HERE">` with your actual OpenAI API key.

## Usage
Once you have installed the required packages and set up your environment variables, you can run the MCQ generator application.

## Additional Information
This MCQ Generator is free to use and does has any warranty or support.
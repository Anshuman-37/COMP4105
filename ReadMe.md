# This is the code for Designing Intelligent Agents coursework 

### Install the *requirements.txt* to install all the dependencies 
###

If it fails these are the mentioned dependencies please install them manually

------------------- *Mentioned Dependencies* -------------------


pip install pygooglenews --upgrade
pip install newspaper3k
pip install transformers
pip install bert-extractive-summarizer 
pip install streamlit
pip install stqdm


------------------- *Running the Agent* -------------------


To run the code in local machine please use app.py and in the terminal run the following command

***streamlit run app.py*** *Please note that it will take a bit time for the first time to donwload the weights for bert* 


-------------------------------


To run the code in colab

Change the Colab environment to GPU
    
Please upload app.py in the colab local runtime
    
In the cell install the requirement.txt or manuall install the requirements *Please note that for intalling commands in colab cell start with ! for example pip install will be !pip install*
    
and then run the following command

***!streamlit run app.py & npx localtunnel --port 8501**** 
    

------------------- *Performance of the agent* -------------------


The performance of the agent and the Rogue score is stored in performance.txt







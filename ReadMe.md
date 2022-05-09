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

***!streamlit run app.py & npx localtunnel --port 8501***

There will be a link generated please click on the given link and then accept the prompt, 
The following images shows is please click on *your url is* and then you will be redirected to a website

<img width="782" alt="Screenshot 2022-05-09 at 2 44 40 PM" src="https://user-images.githubusercontent.com/41586858/167423509-14b27207-d473-49fd-b401-ab1387d5c37a.png">  

Please click on click to continue and then you can see the results.
<img width="872" alt="Screenshot 2022-05-09 at 2 47 38 PM" src="https://user-images.githubusercontent.com/41586858/167424110-b43495c6-76ec-494c-98eb-00c97522a202.png">


The result should look something like this

<img width="773" alt="Screenshot 2022-05-09 at 2 49 53 PM" src="https://user-images.githubusercontent.com/41586858/167424606-7f4e1e8e-cfb1-48c4-adcb-4456caf2ed32.png">


------------------- *Performance of the agent* -------------------


The performance of the agent and the Rogue score is stored in performance.txt







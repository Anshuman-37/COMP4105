# This is the code for Designing Intelligent Agents coursework 

### Install the *requirements.txt* to install all the dependencies 

<img width="667" alt="Screenshot 2022-05-09 at 6 21 47 PM" src="https://user-images.githubusercontent.com/41586858/167463593-6fda6af9-051d-41e4-90bb-9984dc2c4693.png">


If it fails these are the mentioned dependencies please install them manually


### ------------------- *Mentioned Dependencies* -------------------


    pip install pygooglenews --upgrade
    pip install newspaper3k
    pip install transformers
    pip install bert-extractive-summarizer 
    pip install streamlit
    pip install stqdm

-------------------------------

### ------------------- *Running the Agent* -------------------

#### Running the code on local machine

To run the code in local machine please use app.py and in the terminal run the following command

***streamlit run app.py*** *Please note that it will take a bit time for the first time to donwload the weights for bert* 

<img width="1068" alt="Screenshot 2022-05-09 at 6 23 26 PM" src="https://user-images.githubusercontent.com/41586858/167463868-a64e0105-2573-4412-905d-df546fd1e657.png">


-------------------------------


#### Runing the code in colab 

To run the code in colab

Change the Colab environment to GPU
    
Please upload app.py in the colab local runtime
    
In the cell install the requirement.txt or manuall install the requirements *Please note that for installing commands in colab cell start with ! for example pip install will be !pip install*
   
<img width="474" alt="Screenshot 2022-05-09 at 6 36 40 PM" src="https://user-images.githubusercontent.com/41586858/167465889-23b9b607-a426-443c-b8fa-3d27b470839d.png">

and then run the following command.

***!streamlit run app.py & npx localtunnel --port 8501***

<img width="728" alt="Screenshot 2022-05-09 at 6 38 51 PM" src="https://user-images.githubusercontent.com/41586858/167466212-efd53a82-adfe-4104-aca4-304f213c8554.png">


There will be a link generated please click on the given link and then accept the prompt, 
The following images shows is please click on *your url is* and then you will be redirected to a website

<img width="782" alt="Screenshot 2022-05-09 at 2 44 40 PM" src="https://user-images.githubusercontent.com/41586858/167423509-14b27207-d473-49fd-b401-ab1387d5c37a.png">  

Please click on click to continue and then you can see the results.
<img width="872" alt="Screenshot 2022-05-09 at 2 47 38 PM" src="https://user-images.githubusercontent.com/41586858/167424110-b43495c6-76ec-494c-98eb-00c97522a202.png">


The result should look something like this

<img width="773" alt="Screenshot 2022-05-09 at 2 49 53 PM" src="https://user-images.githubusercontent.com/41586858/167424606-7f4e1e8e-cfb1-48c4-adcb-4456caf2ed32.png">


------------------------------------------

### ------------------- *Performance of the agent* -------------------


The performance of the agent and the Rogue score is stored in performance.txt. The performance.txt contains all the result for the summaries made. Rogue Score for all the news have been calculated personally. 


<img width="1469" alt="Screenshot 2022-05-09 at 6 29 49 PM" src="https://user-images.githubusercontent.com/41586858/167464827-4d026847-f3e9-43e9-a554-581e9269617b.png">







# WhatsApp_Chat_Analyser
A repo for the WhatsApp Chat Analyser project by William Munezero (SCT212-0186/2020) and Samuel Gitita Muigai (SCT212-0054/2017)

## Technologies Used 
- Regex - Regular Expression 

- Pipeline Approach ( preprocessor module)

- Streamlit  technology for the frontend 

- Matplotlib technology for plotting the graph  
 
- Seaborn for visualization

- WordCloud python library 

- Matplotlib library

## How It Works

1. First of all you can only upload a text file from WhatsApp chats and any other file will be rejected. 
2. The text file is then preprocessed by being split into respective groups where we have the users, dates and time as well as the message itself. 
3. Group notifications like someone joining the group or leaving or getting kicked out of a group will be removed so as to not be studied. 
4. Visualisation tools like graphs, pie charts, word clouds and heatmaps come a lot in handy to present the report in a more appealing way.

## How To Enjoy WhatsApp Chat Analyser 

+ When using other IDEs with python already installed in the machine:
 1. Make sure all libraries involved are installed through the ***pip install <libraryname>*** command.
 2. Store all these files (main.py, preprocessor.py, helper.py and english_stop.txt) in the same folder.
 3. Open your terminal and navigate to this folder.
 4. Type in the terminal ***streamlit run main.py*** .
 5. Click on the url provided and enjoy.
+ In case you are using Google colabs (Google's Jupyter Notebooks): 
 1. Make sure all libraries involved are installed through the ***!pip install <libraryname>*** command.
 2. Each code cell for a .py file starts with ***%%writefile <filename>.py*** in the first line.
 3. Upload the english_stop.txt in the files panel.
 4. Open a new code cell and type ***!streamlit run main.py & npx localtunnel --port 8501***.
 5. Click on the url that follows ***your url is:*** and enjoy the WhatsApp Chat Analyser.
 

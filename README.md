# AI-Quiz-Generator


**Files:** 
1. requirements.txt
2. streamlit_app.py

**Libraries used**
1. LangChain
2. Streamlit
3. OpenAI

**User Guide:**

1. Open the directory of the files stored using the cd command

          #cd "C:\Users\NEHA\OneDrive\Desktop\QuizGenerator"

2. Install libraries form the requirements.txt file

        #pip install -r requirements.txt

3. Run the python file streamlit_app.py using the following command:

        #streamlit run streamlit_app.py 

A new window will open in the browser from this command 

4. Put the API key in the side bar, and press Enter, and You are ready to use your AI Quiz Appication 

**Documentation**

 *1. OpenAI API Key:* The OpenAI API key is a crucial part of the application. Users need to input a valid key for the quiz generation to work.

*2. Quiz Generation:* The generate_quiz function takes a topic and the number of questions as input and uses the OpenAI language model to generate quiz questions, correct answers, and incorrect options.
The temperature parameter is set to 0.7 to control the randomness of the generated text.

*3.User Interaction:* The user is prompted to enter the quiz topic and the number of questions. Questions are displayed one by one, and the user can select an answer for each using radio buttons.

*4. Error Handling:* The application checks if the OpenAI API key is provided and displays a warning if it's missing. The quiz generation is dependent on a valid API key starting with 'sk-'.

*5. Improvement:* To enhance user experience, more visual elements and feedback mechanisms (e.g., progress bar, proper display of scores could be added) can be added. Also, a different page could be used for differnt questions, with Next and Previous Buttons. 


**User Interface**

![image](https://github.com/Neha-Jakhar/AI-Quiz-Generator/assets/103881430/59e9b735-4d42-45c9-b8c6-3d8bf762039c)






# food-fit-label
Steps to Run the Service
1. Set Up a Virtual Environment

  bash
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`

2. Install Dependencies

  pip install -r requirements.txt

3. Run the Flask Application
  export FLASK_APP=run.py
  export FLASK_ENV=development
  flask run

  On Windows, use:
  cmd
  Copy code
  set FLASK_APP=run.py
  set FLASK_ENV=development
  flask run

4. Access the Application
  Open your web browser and navigate to http://127.0.0.1:5000/ to access the improved chat interface.

5. Interacting with the Application
  Enter a Sentence Prompt
  
  In the input box at the bottom of the chat interface, type a sentence prompt (e.g., "I am looking for low calorie and high protein   recipes").
  Click the "Send" button or press "Enter".
  View Filtered Results

  The chat interface will display your prompt and then fetch matching recipes after filtering out irrelevant terms.
  Recipe cards with images, titles, and links will be displayed if any recipes match your filtered prompt.
  If no recipes are found, a message will be displayed indicating no matches were found.
  This setup provides a user-friendly way to input sentence prompts and receive relevant recipe results, improving the overall user experience.

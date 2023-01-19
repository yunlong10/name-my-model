# Quickstart - Name my Model app

Name your model with this app!

Enter the title of your paper or a lengthy model name that you proposed, you will get a cool name for your model.

| Name your Model App | Enter a paper title | Generate a name for your model |
| :----:  | :----:        | :----:     | 
| <div align=center> <img src=figs/p1.png width=80%/> </div> | <div align=center> <img src=figs/p2.png width=80%/> </div> | <div align=center> <img src=figs/p3.png width=80%/> </div>  |


This app is based on the [OpenAI API](https://beta.openai.com/docs/quickstart). It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework.

## Setup

1. Clone this repository

2. Navigate into the project directory

   ```bash
   $ cd name-my-model
   ```

3. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

4. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```

5. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

6. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

7. Run the app

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! 
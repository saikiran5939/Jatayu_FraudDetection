# Jatayu_FraudDetection
Perfect web for Fraud Detection using Ml
Demo video link: https://drive.google.com/file/d/1xAhRTbrjJq3vH4OohEnUlqaqFO6msVHY/view?usp=share_link
Install Vscode :
  https://code.visualstudio.com/download
open command prompt install flask:
  pip install flak
create a folder in that create a template name folder place an index.html file.
also create an python file name project.py.
In projec.py write the code as follows:
  from flask import Flask, render_template
  app = Flask(_name_,template_folder='template')
  @app.route('/')
  def hello():
    return render_template('index.html')
  if _name_ == '_main_':
    app.run(debug=True)
Write any data on html file and then run the project.py
It will show the localhost site Click on it.
Some data will show in this way the flask is successfully installed.

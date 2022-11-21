# Flask-Project-Model<br>
This is an example of Flask web blog project model.<br>
Use this model for future project sutup.<br>
For running this code first, need install all needed packages.<br>
Then, need to setup many environment variables in local machine based on config.py file.<br>
After that, need to run following code for setup database:<br>
```
python
from flaskblog import db
from run import app
with app.app_context():
  db.create_all()
exit()
```
Noted: set env variables first, or will get errors.

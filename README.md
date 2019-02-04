# Qhacks2019

SmartEQ is a smart glasses hack that allows users to better understand the emotional state of the people that they communicate with. We didn't have access to smart glasses at the hackathon, so we substituted it instead with a React frontend in the browser!

SmartEQ uses a SocketIO connection with Flask in the backend, and React in the frontend. It uses Microsoft Azure's Face API and speech-to-text with sentiment analysis to predict and show ratings to the user to provide a holistic analysis of another person's emotions.

Check it out on devpost: https://devpost.com/software/smarteq

For the python backend, Python 3.6.7

```
python3 -m virtualenv venv
source venv/bin/activate
pip install -r requirments.txt
```

For react frontend

```
cd frontend
npm i
npm start
```

Start up the backend with `python3 server.py` in the `server/` folder and click the start button in your browser!

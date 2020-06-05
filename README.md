*Requirements*
```
Python version - 3.6.7
Flask version  - 0.12
npm version    - 6.14.5
```

*Dependencies Installation*
```
cd frontend
```
```
npm install
```

*Folder Structure*
```
+
|--- frontend
|     |
|     |--- src
|            |---components
                   |---profileimages
                   |---about.js
                   |---About.css
                   |---download.js
                   |---home.js
                   |---navbar.js
                   |---Navbar.css
|            |---App.js
|            |---index.css
|            |---index.js
|            |---serviceWorker.js
|            |---setupTests.js
|     |--- node_modules
|     |--- public
             |---img
             |---favicon.ico
             |---index.html
             |---manifest.json
             |---robots.txt
      |---package-lock.json
      |---package.json
|
|
|
|--- backend
|     |
|     |--- main.py
      |--- server.py
|     |--- youtube_transcription.py
|     |--- keywords_extractor.py
|     |--- summary_generator.py
|     |--- SmartStoplist.txt
|     |--- requirements.txt
|
|
|--- README
|
|--- .gitignore
|
+

```


*Starting the Application*

To start the server type the following  commands :
```
cd backend
```
```
python3 server.py
```
Open a new terminal
To start the client type the follwoing commands :
```
cd frontend
```

```
npm start
```
### **Backend**
Testing Transcription, Keywords Extraction, and Summarization

```
Install modules mentioned in requirements.txt
```

Run the command to test

```
python3 main.py
```

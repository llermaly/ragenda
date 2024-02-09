# Example video
TODO: Upload video

# Instructions:

* We created a cohere email for you to test the addon in our ORG
* Download the extension.zip file and load it
* Using the addon link a meeting to RAGenda
* Join the meeting and open the extension

## Development

Development is a bit trickier given the number of components the app has , but you can take a shot.

* Go to https://github.com/llermaly/hackathon-cohere (private)
* Deploy PostgreSQL database
* Deploy backend using `npm run start:dev` complete the env vars
* Deploy backend-python using `uvicorn app.main:app` --reload
* Run extension using `npm start`, then load the build folder in chrome
* Deploy Workspace app following the `README.md` instructions
* Once everything is up you can repeat the steps on the instructions.

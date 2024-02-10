# RAGenda 

As RAGenda is a Google Workspace + Chrome extension integration, you must have these components to test the app.

We created an ORG with the addon installed for testing and an email for the judges. Please provide us the email address where to send the credentials via GH issue or email.

# Example video

Installing chrome extension. In the right you can see the RAGenda item on the calendar.

https://github.com/llermaly/ragenda/assets/8575569/6f857f80-a1b4-457e-9cc6-bfe213f758da


# Instructions:

* We created a cohere email for you to test the addon in our ORG, please provide an email to send the creds in the issues section, or writing us directly.
* Download the `extension.zip` file and load it
* Using the addon link a meeting to RAGenda
* Join the meeting and open the extension

## Development

Development is a bit trickier given the number of components the app has , but you can take a shot.

* Go to https://github.com/llermaly/hackathon-cohere (private)
* Deploy PostgreSQL database and seed script. Add project to the DB (CRUD screen soon)
* Deploy backend using `npm run start:dev` complete the env vars
* Deploy backend-python using `uvicorn app.main:app` --reload
* Run extension using `npm start`, then load the build folder in chrome
* Deploy Workspace app following the `README.md` instructions
* Once everything is up you can repeat the steps on the instructions.

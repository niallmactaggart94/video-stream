# DAZN Assessment 

This task was completed by Niall MacTaggart.

**IMPORTANT**: If there are any issues surrounding certs, you may need to trust the cert.pem file found in the backend service (backend/certs/cert.pem), for me this was adding it to keychain **in the certificates section**
and ensuring that it was trusted, both within Keychain. The initial pull might be a bit longer than usual due to the video stored within the backend service. I have detailed in the backends README that this would be one of the
first things to be improved going forward.

## Approach
This project structure is as follows:

- **Frontend:** Angular application
- **Backend:** Rest API written in NodeJS using the express framework

More details on decisions made, running each application individually and how to test them are found within the projects themselves.


## How to run solution locally

This can be going into each of the repos and running:
```
npm install
npm run start
```
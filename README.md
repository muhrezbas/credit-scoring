# Credit Scoring Deployment  

I am using FastAPI + Uvicorn to serve the model which creates automatic
documentation using OpenAPI (Swagger) and ReDoc.

The Dockerfile is included if you would like to containerize the application
and deploy it on the cloud.

## How to

Install all the libraries in requirements.txt then run /app/main.py using `uvicorn main:app`

Access `http://127.0.0.1:8000/docs` from your favorite browser.

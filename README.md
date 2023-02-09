# Thanks Eskom. How many candles do I need?

## About this project:

The web frontend was created with Astro, the backend uses Python's Flask framework.

This page requests information from a flask server about the current loadshedding stage.
Flask will obtain the relevant information from Eskom's API and return it to this frontend.

Click the buttons and see what happens.

## Backend server:

A flask server serving this site was developed to run on the same network, in this specific case, the sever ran on Windows WSL and the web page on Windows 10.
You can find the code and instructions for the server in the 'flaskEskom' repo.

## Running:

This is not production proof, dev mode is the only mode for now.
Get the IP of the host on which the server is running (flask server).
Edit src/pages/index.astro and change 'xxx.xxx.xx.xxx' to the IP of the host on which the flask server runs.
Save the file.

In the terminal, in the noEskom directory, run:  
``
npm run dev
``

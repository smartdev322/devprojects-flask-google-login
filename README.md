# devprojects-flask-google-login

## Techs

- Flask, requests, oauthlib, pyOpenSSL, Flask-Login

## Refs

- Project tutorial
[Create a flask application with google login](https://realpython.com/flask-google-login/#creating-your-own-web-application)
- GitHub ref project
[flask-google-login](https://github.com/realpython/materials/tree/master/flask-google-login)

## Main dependancies

- python3.7
- requests==2.21.0
- Flask==1.0.2
- oauthlib==3.0.1
- pyOpenSSL==19.0.0
- Flask-Login==0.4.1

## Prepare development environment

- Install python3.7
    ```sh
    $ sudo add-apt-repository ppa:deadsnakes/ppa
    $ sudo apt-get update
    $ sudo apt-get install python3.7
    ```
- Install pip3
    ```sh
    $ sudo apt update
    $ sudo apt install python3-pip
    ```
- Install venv for python3.7
    ```sh
    $ sudo apt-get install -y python3.7-venv
    ```
- Create virtual environment using venv & activate
    ```sh
    $ python3.7 -m venv env
    $ source env/bin/activate
    ```
- Install requirements
    ```sh
    $ pip install -r requirements.txt
    ```

## Run project

### Set your client credentials as environmental variables

- Linux bash terminal and Mac OS X terminal

	```bash
	export GOOGLE_CLIENT_ID=your_client_id
	export GOOGLE_CLIENT_SECRET=your_client_secret
	```

- If you’re on Windows, in Command Prompt.
	```bash
	set GOOGLE_CLIENT_ID=your_client_id
	set GOOGLE_CLIENT_SECRET=your_client_secret
	```

### Run

    ```sh
    $ source env/bin/activate
    (env)$ python app.py
    ```

    Navigate to <https://localhost:5000>

# Byakugan

Byakugan is a CLI-based web monitoring tool that can be used to monitor HTTP-based endpoints and alert the subscribers only when the API endpoint is no longer reachable.

### Steps to run:

1.  Create a virtual environment and activate it
    ```
    python3 -m venv <virtualenv-name>
    .\<virtualenv-name>\Scripts\activate      (For Windows)
    source .\<virtualenv-name>\bin\activate    (For Linux)
    ```

2.  Install the dependencies from ```requirements.txt```
    ```
    pip install -r requirements.txt
    ```

4.  Run the script
    ```
    python3 main.py
    ```

> (Note: Currently I'm working on migrating it to Go, so new features may take some time)

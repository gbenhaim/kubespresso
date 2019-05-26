# kubespresso

## Starting the virtualenv on RHEL

```bash

mkvirtualenv -p /opt/rh/rh-python36/root/usr/bin/python kubespresso
pip install -U pip
pip install -r requirements.txt
```

## Running the controller locally

* Setup the virtualenv
* Make sure that you are logged in to the cluster with a user that has cluster-admin role
* Run:
    ```bash
        python kubespresso.py
    ```

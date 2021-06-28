**Activate the virtual environment**

```
    source blochain-env/bin/activate
```

**Install all packages**

```
    pip3 install -r requirements.txt
```

**Run the tests**

Make sure to activate the virual environment

```
python3 -m pytest backend/tests
```
**Run the Application and the API**

Make sure to activate the virual environment

```
python3 -m backend.api
```
**Run a peer instance**

make sure to activate the virtual environment

```
export PEER=True && python3 -m backend.app
```
**Run the frontend**

In the frontend directory:
```
npm run start
```

**Seed the backend with data**

Make sure to activate the virtual environment

```
export SEED_DATA=True && python3 -m backend.app
```
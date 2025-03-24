### Installing necessary packages:  
* `pip install fastapi`
* `pip install "uvicorn[standard]"`  
* `pip install sqlalchemy`  
* `pip install pymysql`
* `pip install pytest`
* `pip install pytest-mock`
* `pip install httpx`
* `pip install cryptography`
### Run the server:
`# python -m uvicorn api.main:app --port 8001 --reload`
### Test API by built-in docs:
[http://127.0.0.1:8001/docs](http://127.0.0.1:8001/docs)

![FastAPI Preview](FastAPI_Image.png)

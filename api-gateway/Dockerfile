FROM tiangolo/uvicorn-gunicorn-fastapi:python3.8\n\nCOPY ./app /app\n\nRUN pip install --no-cache-dir --upgrade -r /app/requirements.txt\n\nCMD [\
uvicorn\, \app:app\, \--host\, \0.0.0.0\, \--port\, \8000\]

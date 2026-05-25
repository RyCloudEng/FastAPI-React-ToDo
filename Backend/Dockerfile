FROM python:latest 

#RUN npm install react-router-dom@6

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

CMD ["uvicorn","main:app","--host","0.0.0.0" , "--port" ,"4000" ,"--reload"]

FROM python:3.12.1
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
RUN mkdir ~/.streamlit
ENTRYPOINT [ "streamlit","run" ]
CMD ["main.py"]
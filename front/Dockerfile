FROM python

RUN mkdir -p /home/front

COPY . /home/front

RUN pip install -r /home/front/requirements.txt

CMD ["python", "/home/front/server2.py"]

EXPOSE 4000
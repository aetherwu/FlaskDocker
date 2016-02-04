FROM daocloud.io/python:2.7
ADD . /code
WORKDIR /code
RUN pip install -r app/requirements.txt --trusted-host pypi.douban.com
CMD python run.py

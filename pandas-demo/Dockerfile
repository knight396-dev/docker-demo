FROM python:slim
WORKDIR /pandas-demo
COPY requirement.txt .
RUN pip install -r requirement.txt
COPY pandas-demo.py . 
CMD ["python","pandas-demo.py"]
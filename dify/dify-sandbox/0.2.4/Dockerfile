FROM langgenius/dify-sandbox:0.2.4
COPY requirements.txt requirements.txt
RUN python --version
RUN pip install Cmake --no-cache-dir -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
RUN pip install -r requirements.txt --no-cache-dir -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com

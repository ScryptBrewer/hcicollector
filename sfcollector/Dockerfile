## Docker container for solidfire-graphite-collector
## olson@netapp.com
FROM python:3
MAINTAINER olson@netapp.com

WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD [ "python", "./solidfire_graphite_collector.py" ]

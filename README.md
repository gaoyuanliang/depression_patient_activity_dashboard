# Deep Depression Detector

Building a deep depression detector to detect the mental depression status from a person's activity data.

## Instillation 

### Instilling Elasticsearch

```bash
wget https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-6.7.1.tar.gz
tar -xf elasticsearch-6.7.1.tar.gz
cd elasticsearch-6.7.1
bin/elasticsearch
```

### Instilling Kibana

```bash
wget https://artifacts.elastic.co/downloads/kibana/kibana-6.7.1-darwin-x86_64.tar.gz
tar -xf kibana-6.7.1-darwin-x86_64.tar.gz
cd kibana-6.7.1-darwin-x86_64
bin/kibana
```

then you can view the kibana dashboard at http://localhost:5601

## Downloading the data

```bash
wget https://datasets.simula.no/depresjon/data/depresjon-dataset.zip
unzip depresjon-dataset.zip
```

<img src="https://raw.githubusercontent.com/gaoyuanliang/deep_depression_detector/master/screencapture-localhost-5601-app-kibana-2020-08-31-19_45_29.png" width="1000">

<img src="https://raw.githubusercontent.com/gaoyuanliang/deep_depression_detector/master/screencapture-localhost-5601-app-kibana-2020-08-31-19_46_33.png" width="1000">

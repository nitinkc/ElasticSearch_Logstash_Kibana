# ElasticSearch_Logstash_Kibana

#### Elasticsearch
Download the latest version of elasticsearch and unzip it (for Windows)

Run elasticsearch.bat in the bin directory 
```sh
\Downloads\elasticsearch-7.5.2\bin> elasticsearch.bat
```

Access Elasticsearch @ (http://localhost:9200/)[localhost:9200]

#### Kibana
Download the latest version of kibana and unzip it (for Windows)
Uncomment the following line in kibana.yml in ```\Downloads\kibana-7.5.2-windows-x86_64\config``` folder

```sh
#ElasticSerch URL. Local host in this case
elasticsearch.url: "http://localhost:9200"
```
Run kibana.bat in ```\Downloads\kibana-7.5.2-windows-x86_64\bin```. 

kibana UI can then be accessed at (http://localhost:5601/)[localhost:5601]


#### Logstash
Download the latest version of logstash and unzip it.
logstash -f logstash.conf

Create logstash.conf file in ```Downloads\logstash-7.5.2\bin>``` folder

run log stash from the bin folder as 

```sh
logstash -f logstash.conf
```

# Docker Cerebro Elasticsearch

Dockerize Cerebro, Elasticsearch and Kibana. It's composing Elasticsearch, Kibana and Cerebro as web admin (UI) for it.

# Prerequisites
1. Docker Engine >= 1.13.2

> detail: https://docs.docker.com/compose/compose-file/compose-file-v2/

# Up and Run
```
$ docker-compose up
```

It will expose port:  
- `9200` for Elasticsearch
- `5601` for Kibana
- `9000` for Cerebro

![ES](https://res.cloudinary.com/emshidiq/image/upload/c_scale,h_330/v1599627883/Screen_Shot_2020-09-09_at_12.00.35_whjqao.png)  


![Cerebro](https://res.cloudinary.com/emshidiq/image/upload/c_scale,h_400/v1599627643/Screen_Shot_2020-09-09_at_11.48.00_ftlqhy.png)  

![Kibana](https://res.cloudinary.com/emshidiq/image/upload/v1601459370/Screenshot_17_qrgvia.png)  


# Elasticsearch Configuration

You can put elasticsearch config through `esconfig` folder.  
See details here https://hub.docker.com/_/elasticsearch

# Kibana Configuration

Kibana configuration located at `kibana.yml`  
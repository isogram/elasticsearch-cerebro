# Docker Cerebro Elasticsearch

Dockerize Cerebro and Elasticsearch. It's composing Elasticsearch and Cerebro as web admin (UI) for it.

# Prerequisites
1. Docker Engine >= 1.13.2

> detail: https://docs.docker.com/compose/compose-file/compose-file-v2/

# Up and Run
```
$ docker-compose up
```

It will attach Elasticsearch to port `9200` and Cerebro to port `9000`  

![ES](https://res.cloudinary.com/emshidiq/image/upload/c_scale,h_330/v1599627883/Screen_Shot_2020-09-09_at_12.00.35_whjqao.png)  


![Cerebro](https://res.cloudinary.com/emshidiq/image/upload/c_scale,h_400/v1599627643/Screen_Shot_2020-09-09_at_11.48.00_ftlqhy.png)  


# Elasticsearch Configuration

You can put elasticsearch config through `esconfig` folder.  
See details here https://hub.docker.com/_/elasticsearch
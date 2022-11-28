# Filebeat

Filebeat is a lightweight shipper for forwarding and centralizing log data. Installed as an agent on your servers, Filebeat monitors the log files or locations that you specify, collects log events, and forwards them either to Elasticsearch or Logstash for indexing.

## install using Linux Terminal commands 
Run the following commands

```bash
wget -qO -https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add
```

```bash
sudo apt-get install apt-transport-https
```

```bash
echo "deb https://artifacts.elastic.co/packages/7.x/apt stable main" | sudo tee /etc/apt/sources.list.d/elastic-7.x.list
```

```bash
sudo apt update
```

```bash
sudo apt install filebeat
```

Configure Filebeat:

```bash
sudo nano /etc/filebeat/filebeat.yml
```

start service : 
```bash
sudo service filebeat start
```

## Filebeat Documentation

Use this [LINK](https://www.elastic.co/beats/filebeat) to read more documentation.

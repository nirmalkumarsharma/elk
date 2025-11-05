# ELK Stack Docker Setup

This project provides a simple setup for running the ELK (Elasticsearch, Logstash, Kibana) stack using Docker Compose.

## Files
- `docker-compose.yml`: Docker Compose configuration for ELK services.
- `logstash.conf`: Logstash pipeline configuration.

## Usage
1. **Start the ELK stack:**
   ```powershell
   docker-compose up -d
   ```
2. **Stop the ELK stack:**
   ```powershell
   docker-compose down
   ```

## Customization
- Edit `logstash.conf` to change Logstash pipeline settings.
- Update `docker-compose.yml` to modify service configurations.

## Requirements
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

## References
- [ELK Stack Documentation](https://www.elastic.co/what-is/elk-stack)
- [Docker Compose Docs](https://docs.docker.com/compose/)

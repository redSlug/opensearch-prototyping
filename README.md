# OpenSearch Prototyping

Slides: https://bit.ly/openSearchPresentation

## How to run locally

Create your local search engine instance with docker
```shell
# Clone repo and cd into opensearch
docker compose up
```
### OpenSearch dashboard access
Visit http://0.0.0.0:5601/app/home#/
password=admin, username=admin

### Prototyping
Use http://0.0.0.0:5601/app/dev_tools#/console or the included [POSTMAN](https://www.postman.com/) collection to 
create your index, populate it with data and query it.

## Resources
- [Understanding mappings](https://dev.to/lisahjung/beginner-s-guide-understanding-mapping-with-elasticsearch-and-kibana-3646)

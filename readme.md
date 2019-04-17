#Docker

## Clean all image
```docker rmi $(docker images -a -q) -f```

## Clean unsused objects
```docker system prune```

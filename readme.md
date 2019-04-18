# Piwik/Matomo

## Clean all image
```docker rmi $(docker images -a -q) -f```

## Clean unsused objects
```docker system prune```

## Chrome injector
```https://github.com/Findus23/matomo-injector```

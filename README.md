### BB Common Compose
BB  kafka senoryosu  için development gereksinim docker-compose dosyaları bulunan bir repository.  

## Kullanım

```bash
# create volumes dir
mkdir volumes
```

### Komutlar

```bash

# kafka (mail, sms, auth service)
docker-compose -f .\kafka\kafka.yaml up -d
docker-compose -f .\kafka\kafka.yaml down

```
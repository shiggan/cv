
``` cmd
docker build --rm -f "dockerfile" -t mgnz.cv:latest .
docker run --rm -d -p 80:80/tcp mgnz.cv:latest
```


## Running the template app
```docker build -t <your-tag-name> .``` \
``` 
docker run -p 8888:8888 
-e CONFIG_USER_NAME={CONFIG_USER_NAME}
-e CONFIG_PASSWORD={CONFIG_PASSWORD}
<tag-name>
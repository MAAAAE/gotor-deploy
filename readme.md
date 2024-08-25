

# prerequisite

## gotor-be

- Speech to text API secret configuration
```shell
 export GOOGLE_APPLICATION_CREDENTIALS={your google cloud service account key path}.json
 
```

## gotor-engine
```shell
cd gotor-engine
vi chatgpt.py
```

- you should change api_key above file 
- `client = OpenAI(api_key="your openai api key")`



# how to run
```shell
docker compose up -d
```
# Yapay Zeka

## API Bilgileri

- API (Yapay Zeka) Login : https://zekai.co/api/v1/login/
- API (Yapay Zeka) Prompt : https://zekai.co/author-api/v1/submit-text

### Sample Prompt

```json
{
    "segment": "author-complete",
    "model": "text-davinci-003",
    "sentence": "Extract the Address for Google Maps API using this tweet, the address will be from Turkey: Tweet: RECEP TAYYİP ERDOĞAN BULVARI 209. SOKAK DOĞRUYOL APARTMANI \nKIRIKHAN/HATAY\nARKADAŞIMIZ ENKAZ ALTINDA LÜTFEN YARDIM EDİN!…",
    "description": "default",
    "filter": "default",
    "suffix": "",
    "maxtokens": "256",
    "templature": "0.9",
    "topp": "1.0",
    "n": "1",
    "stream": "False",
    "logprobs": "0",
    "echo": "False",
    "stop": "None",
    "presencepenalty": "0.0",
    "frequencypenalty": "0.0",
    "best_of": "1"
}
```


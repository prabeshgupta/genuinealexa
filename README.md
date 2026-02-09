# GenuineAlexa

Unlock the true power of Alexa backed by Perplexity AI.

GenuineAlexa is an Alexa Skill that connects Alexa with Perplexity AI, allowing users to ask intelligent questions and receive real time, AI powered answers directly through their Alexa device.

---

## Features

- Ask Alexa anything and get AI generated responses  
- Powered by Perplexity AI  
- Supports multiple English locales  
- Simple GitHub import setup  
- Fully customizable Lambda backend  

---

## Project Structure

```
.
├── interactionModels/
│   └── custom/
│       ├── en-US.json
│       ├── en-GB.json
│       ├── en-IN.json
│       ├── en-CA.json
│       └── en-AU.json
└── lambda/
    ├── lambda_function.py
    └── requirements.txt
```

---

## How to Import This Skill into Alexa

1. Go to Alexa Developer Console  
2. Click Create Skill  
3. Select Import skill  
4. Paste this GitHub repository URL  
5. Click Import  

Alexa will automatically configure the interaction models and Lambda code.

---

## Setup Requirements

Open:

```
lambda/lambda_function.py
```

Replace placeholder values such as:

```python
API_KEY = "YOUR_API_KEY_HERE"
```

with your own Perplexity API key.

---

## Testing

After importing:

- Build the model  
- Enable the skill  
- Open the Test tab  

Example:

```
Alexa, {skillname}

```

---

## Security Note

Do NOT commit real API keys or secrets to GitHub.

Always use placeholders and configure credentials using Lambda environment variables.

---

## Contributions

Pull requests are welcome.

Improve intent models, add features, or optimize Lambda logic.

---

## License

Use freely and modify openly.

---

## Support

If this project helped you, please star the repository.

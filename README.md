Prerequisites for running the code: 
	
•	GOOGLE_API_KEY – can be acquired for free [here]([https://pages.github.com/](https://aistudio.google.com/app/apikey?_gl=1*r73ss5*_ga*NDI2ODY5OTg1LjE3MjgzMTU0NjI.*_ga_P1DBVKWT6V*MTcyODYyMzAyMy43LjAuMTcyODYyMzAyMy42MC4wLjQ4ODk3MDAxNA..))
•	GROQ_API_KEY – can be acquired for free [here](https://console.groq.com/keys)
•	NEO4J credentials – provided in a separate file. Neo4j provides a free instance of Aura DB as I’m not planning to store sensitive data there and I trust you not to do so either.
All of those can be loaded into a .env in the project and be accessed by running

```python
load_dotenv()
GOOGLE_API_KEY = os.getenv(“GOOGLE_API_KEY”)
```

• Documents should be stored within ‘./documents’ directory and be of .txt format
  If no documents are ready, by default documents are loaded from Wikipedia. You can select different titles, but it’s been only evaluated on the default pages.

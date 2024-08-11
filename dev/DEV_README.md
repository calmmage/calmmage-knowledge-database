Idea, what I want to have here:

# Tech motivation
I thought: Fuck, I actually can have my own database of all my text notes 
1) JUST IN THE GITHUB.
2) AND LOCALLY
3) AND BE AVAILABLE FROM EVERYWHERE!

# Use case motivation
I want to have all my knowledge in a DB. 
Indexed with embeddings.
Including backlings

---
# Alternatives considered
- Can I upload / sync everything to Notion and use from there?
- Pro: They are responsible for search indexing
- 

# Databases I want to support:
1. Code snippets - from code garden, from github 
2. Notion
3. Telegram messages
4. Google Chrome bookmarks!!!
5. Extras. Everything that a human would consider information source 
   - Google Calendar?

# Contents
1. Markdown Vault - for text-based knowledge available via UI
2. Raw MongoDB or anything else containing 
3. Indexed local ChromaDB with my data

# Tech plan
- a) Download ALL the data into the raw format. Mongodb or something
- b) Parse the raw data into the processed feed using specialized processors
- c) work with data using the Client.

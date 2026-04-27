---
name: local-memory
description: Accesses the user's private list of previously visited or saved restaurants.
---

# Local Memory Skill

## Instructions
1. This skill is **ONLY** to be used if the user explicitly mentions "my list," "places I've been," "previously visited," or "my stored favorites."
2. If triggered, inform the user you are checking their private local database.
3. Search for the restaurant in the local `stored_places.txt` file (Note: The LLM simulates this search; the actual file reading happens via the JS execution environment if paired).
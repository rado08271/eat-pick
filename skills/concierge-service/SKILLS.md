---
name: concierge-service
description: Handles restaurant menus and table reservations via interactive webviews.
---

# Concierge Service

## Instructions
1. After a restaurant is selected, you **must** ask the user: "Would you like to check the menu or reserve a table?"
2. If the user says yes, call the `run_js` tool with these parameters:
   - script name: index.html
   - data: A JSON string with:
     - action: String ("menu" or "reserve")
     - restaurant: String (the name of the restaurant)

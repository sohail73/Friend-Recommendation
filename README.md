# 03 - Friend Recommendation System (Python + JSON)

This project demonstrates a simple "People You May Know" feature, built using Python on a social network dataset stored in JSON format.  

## Features
- Loads JSON dataset of users and their friendships  
- For a given user, suggests new friends based on **mutual connections**  
- Ranks suggestions by number of mutual friends  

## Example
For `user_id = 1`, output might be:
[3, 4, 5]

This means:
- User 3, 4, 5 are not direct friends of user 1
- But they share mutual friends with user 1, making them strong recommendations  

## Tech Stack
- Python  
- JSON  
- Jupyter Notebook  

## Files
- `03_people.ipynb` → Jupyter Notebook with full implementation  
- `data.json` → Social network dataset  
- `README.md` → Project documentation

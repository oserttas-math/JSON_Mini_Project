# json_hw
This repo contains my solution to a homework problem on **Data Wrangling With JSON files**.

# Learning Objective

- Practice  working with the JSON format using a real life data set.
- Extract and manipulate data in JSON
- Practice your data wrangling skills.

# Description
The dataset on the World Bank projects is available in a JSON file. Project begins with importing JSON object and trasnforming it into a python dictionary. After cleaning and reshaping the data, observed that China, Indonesia and Vietnam have the most projects with the World Bank. Then extracted project themes data to see which projects has been done and how often they have occurred. Results shows that environment and natural resources management, rural development and human development are the project themes with the highest frequencies.

# Notes
- Keys in key/value pairs of JSON are always of the type str. 
- When a dictionary is converted into JSON, all the keys of the dictionary are coerced to strings. 
- json.dump() : objects to json objects, json.load() : decode json objects to python dict using conversion table. [See documentation] (https://docs.python.org/3/library/json.html)



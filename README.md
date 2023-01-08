# Wiki_Word_Score

This gui works by letting the user search wikipedia for a topic and select a page from the 5 most relevant articles.

It then takes the 'score key' (default value 'nic cage') and determines how many times you may use the characters
from the article summary to create the score key.

This is accomplished by taking each unique character from the score key and counting how many times that characters shows in the summary
we then divide that number by how many times the unique characters occurs in the score key

returns the smallest of these values

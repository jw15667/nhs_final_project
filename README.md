# NHS Final Project

## Content
##### 1. Project Aim
##### 2. Technologies
##### 3. Webscraping.
##### 4. Build the Model.
##### 5. Project Status.
##### 6. Sources.
##### 7. Additional Information. 

### Project Aim
To build a model that predicted sentiment of newspaper headlines for traditionally 'conservative' newspapers.


### Technologies 
- Python 3.6
- MySQL 8.0
- Selenium
- Beautiful Soup  
- Excel VBA
- NLTK

### Webscraping
Issues faced with webscraping from Google was with reCAPTCHA so the solution used:
* Create google links for every search.
* Copy and paste all google sarches into excel.
* Use a VBA to extract all links from the hrefs. 

### Build a Model

Natural Language ToolKit:
* Vader

### Project Status
Project has finished, and was done in 5 days. I had previously tried to build my own sentiment model but ran out of time - so one improvement would be to use an unsupurvised model instead of the NLTK library. 

Additionally, scrape more data and more newspapers to generate a greater dataset.

### Sources
Useful websites that we used:

https://towardsdatascience.com/how-to-use-nlp-in-python-a-practical-step-by-step-example-bd82ca2d2e1e

https://www.nltk.org/

https://pypi.org/project/num2words/

https://wordnet.princeton.edu/

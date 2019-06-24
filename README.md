# INIT NEWS

#### Author

- by [Danmark Mutai](https://dnmrk4.github.io/portfolio/)

## Description

Init News is a web application that will help users list and preview news articles from various sources.
This webpage will get you caught up on current affairs from all around the world

## Features

- The home page allows users to see various news sources sorted based on categories and select their preference.
- Once selected, a list of all articles for that news source with image description and time of posting article is shown.
- User can click on an article and read it fully from the news source.
- Users can additionally click top headlines to see top headline articles.

## BDD

| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| View Business sources | Click on the `BUSINESS` button | Scrolls the page to the `BUSINESS` section |
| View Entertainment sources | Click on the `ENTERTAINMENT` button | Scrolls the page to the `ENTERTAINMENT` section |
| View Sports sources | Click on the `SPORTS` button | Scrolls the page to the `SPORTS` section |
| View Top Headlines Articles | Click on the `Top Headlines` button | Redirects to a page that displays articles on Top Headlines |
| View Articles on Everything | Click on the `Everything` button | Redirects to a page that displays All articles |

## Link demo live site

View the complete site [here](https://initnews.herokuapp.com/)

### Contact Information

[danmark.chemuren@gmail.com](gmail.com)

## Technologies Used

    - Python 3.6
    - Flask Framework
    - HTML, CSS, Bootstrap and Masonry
    - JavaScript

## Set-up and Installation

    1. Clone or download the Repository
    2. Create a virtual environment
    3. Read the specs and requirements files and Install all the requirements.
    4. Edit the start.sh file with your api key from the news.org website
    6. Run chmod a+x start.py
    7. Run ./start.py
    8. Access the application through `localhost:5000`

### Bugs

- One cannot find specific categories, in News Highlight only the general news are displayed

## License

 - This is a [MIT license](/LICENSE)
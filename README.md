# News-Browser

full-stack project for USC EE599

The website allow users to browse the news with difference sources and specific categories.

## Tool

* Frontend: HTML, CSS, Bootstrap4
* Backend: Node.js, express
* Google News Api: [NewsApi](https://newsapi.org)


## Function

#### Subscribe: 
* Allow users to subscribe daily News with selected category, which will be sent to the user's email address by backend server every 24 hours.
#### Headliner:
* Browse headliner from different sources with selected category.
#### Search:
* Search news with keyword with selected sort option.

## Getting Started
##### To get the Node server run locally
```bash
git clone https://github.com/linchen1010/News-Browser.git
npm install
```

### Runing Backend:
```bash
cd backend
node app.js
```

### Runing Frontend:
```bash
cd frontend
node app.js
```

Then open your browser at http://localhost:3000 for news.html
                          http://localhost:3000/register for register.html


## Preview
* Register page for users to enter email
![Register page](/image/registerPage.png)
* News page
![News page](/image/newsPage.png)
* Search preview
![Search example](/image/SearchExample.gif)

## Authors

Shi-Lin Chen(shilinch@usc.edu)

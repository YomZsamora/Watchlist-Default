# Watchlist Flask App

Flask App that fetches a response from Movie API and displays the movies in categories. Users can also be authenticate and have an account where they can post reviews for movies. This is part of the Moringa LMS content mini project and used recently for MC19 Flask Catch Up Session

## Requirements

The roject has dependecies that require Flask together with PIP. So make sure you have these installed and working before proceeding. Can also refer from the technologies used below.

##### Technologies Used

- Flask Framework
- SQL-Alchemy
- Postgres Database
- PIP Package Manager

##### Setup Instructions and Installation

- Clone this repository to a location in your file system. 'git clone https://github.com/YomZsamora/Watchlist-Default.git'
- Open terminal command line then navigate to the root folder of the application. 'cd Watchlist-Default'
- Activate Virtual 'source virtual/bin/activate'
- Ensure Flask-Script, Flask-Bootstrap, Postgres, Flask-SQLAlchemy & Flask-Forms are installed by typing 'pip freeze' on the terminal. If not run the necessary commands to install them.
- Run `./start.sh` command. Note this will work if you've properly configured your app with the required dependencies 
- Navigate to `http://localhost:5000/` in your browser.


## Development

Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:
- Fork the repo
- Create a new branch (git checkout -b improve-feature)
- Make the appropriate changes in the files
- Add changes to reflect the changes made
- Commit your changes (git commit -am 'Improve feature')
- Push to the branch (git push origin improve-feature)
- Create a Pull Request


## Known Bugs

If you find a bug (the website couldn't handle the query and or gave undesired results), kindly open an issue here by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue here. Please include sample queries and their corresponding results.


##### Link to Live Site : [https://frozen-bastion-12918.herokuapp.com/](https://frozen-bastion-12918.herokuapp.com//)

### License

*MIT*
Copyright (c) 2019 **Yommie Samora**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

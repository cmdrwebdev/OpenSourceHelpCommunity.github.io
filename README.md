# Open Source Help Community

 [![Build Status](https://travis-ci.org/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io.svg?branch=develop)](https://travis-ci.org/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io)

[![Coverage Status](https://coveralls.io/repos/github/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io/badge.svg?branch=develop)](https://coveralls.io/github/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io?branch=develop)

![OSHC](https://avatars0.githubusercontent.com/u/23719480?v=3&s=200)

We are trying to create a medium where people who want to start with contributing to open sources and open source contributors meet and discuss their thoughts and questions([Getting Started With Open Source](https://github.com/tapasweni-pathak/Getting-Started-With-Contributing-to-Open-Sources)).

[Website](http://opensourcehelpcommunity.herokuapp.com/) [WIP]

After every commit, the `develop` branch on github is automatically deployed to [opensourcehelpcommunity-dev.herokuapp.com](http://opensourcehelpcommunity-dev.herokuapp.com/) and the `master` branch is automatically deployed [to opensourcehelpcommunity.herokuapp.com](http://opensourcehelpcommunity.herokuapp.com/) . All the development is done on `develop` branch and once we're ready for a new release we merge the `develop` branch with the `master` branch. Please submit your pull request based on `develop` branch.

This is using [Django(1.11)](https://www.djangoproject.com/) and [Bootstrap](http://getbootstrap.com/).
Feel free to suggest a better design.

Please submit your pull request on develop branch, it will have the most recent changes.

## How to Contribute
This is an Open Source project and we would be happy to see contributors who report bugs and file feature requests submitting pull requests as well. This project adheres to the Collaborative [code of conduct](https://github.com/OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io/blob/develop/CODE_OF_CONDUCT.md). By participating, you expect to maintain the code of conduct. Before creating `New issue` and `Pull request`, please refer to the [template](docs).  

## Installations
Run
```
pip install -r requirements.txt
```
to install everything required to run this project on heroku as well as on your local.


## To run this in your local

1. Clone this repository using
	```
	git clone git@github.com:OpenSourceHelpCommunity/OpenSourceHelpCommunity.github.io.git
	```

2. Go inside main Django app [Instructional video on installing Django](https://youtu.be/qgGIqRFvFFk)
	```
	cd oshc
	```

3. Collectstatic files using
	```
	python manage.py collectstatic
	```

4. Run the app
	```
	python manage.py runserver
	```

To run the web app in Debug mode set the DEBUG environment variable.
In Linux, run the `export DEBUG=True` command in the terminal.

Feel free to raise and fix issues.
For any questions, join #oshc-dev on Slack. Get an invite [here](https://opensourcehelp.herokuapp.com/).

Note : All design related tasks have reward associated with them.

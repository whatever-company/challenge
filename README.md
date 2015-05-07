#Knowledge Plaza Challenges

Knowledge Plaza, a fun Belgian startup, is looking for talents to join the team and help build the best social network for companies. Want to join? Let's try one of those little challenges!

The goal of thos challenges is to learn, to have fun and to test if you would have fun working at Knowledge Plaza. If you apply for a Junior position, the code you will write is a lot less important than the way you approach an unknown problem. 

There are two challenges: Frontend and Backend. Pick your favourite or both if you are a fullstack kind of person.

##The Frontend Challenge

You are asked to write a small web application that display a dynamic stream of "tiles". Each tile is an exerpt of a piece of content. Tiles may have tags. 

The stream should be filtrable by tags and/or by plain search. Your application will also allow your user to create a tile that will be displayed imediately in the stream.

The initial content is described as a list of tiles in the attached JSON file. Each tile has multiple properties but you may only consider using tile.title and tile.tags. Other are optionnal but we are eager to see your creativity!

![screenshot](https://raw.githubusercontent.com/whatever-company/challenge/master/frontend/Screen%20Shot%202015-03-24%20at%2013.57.16.png)

In the example above, each tile is a rectangle. The color is determined by tile.subtype, then tile.title, tile.description and tile.tags are displayed.

The right column allows to filter content in the first box. The second box allows to create a tile with a title and tags but no description.

##The Backend Challenge

You are asked to write a python application which will retrieve and store Tweets from a Twitter timeline.

The application will connect to Twitter through OAuth and dynamically fetch a timeline that can be configured: tweets from a given user, from a given hashtag or from a given timeline (following of a given user).

Your application will have an API, accessible through a simple webpage, allowing to search through this timeline. The webpage may be trivial: it should be only a simple static page with a search field. Searching for anything will return a webpage containing all the tweets from the followed timeline who are matching the search. 

The look-n-feel of the results is not important. 

##Technical specifications

We are asking you to create a private (or somewhat secret) github repository with your code. We strongly recommend the use of an existing framework (AngularJS or React for the frontend. Any Python package for the backend).

We expect the code to be readable and to have unit tests. For the frontend, we recommand Karma+Jasmine but you can use MochaJS or the framework of your choice.

In order to see how you work, we are interested by seeing each commits. A big dump of your project to github in one commit is not a good idea.

Afterward, send a link to your repository to l.dricot@knowledgeplaza.net.


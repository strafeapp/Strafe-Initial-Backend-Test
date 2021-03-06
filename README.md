# Strafe Initial Backend Test

Create a service that connects to a Twitch chat from a channel, store the messages as they are sent and create a GraphQL API that produces information about the chat.

The API created should contain queries to:
- Fetch the amount of messages per second and per minute by channel
- Start tracking some channel chat
- Fetch the chat mood
  - How you define "mood" is up to you, maybe its a "kappa-per-minute", or a "Hype meter" - feel free to use your imagination. It should however be something fun or useful for the end consumer.

When finished the test, please send the repository link to ayat@strafe.com.

## Points to be considered
- **Application modular structure** - Since the objective of the test is to see how the applicant writes the code and modularize it, we recommend not to use a full sacked convention driven Framework like Django. We suggest using [Flask](http://flask.pocoo.org/).
  - Remember, a code where the team can easily migrate one part of it without gigantic changes on the other parts is a good modularized one (If I change my database, do I really need to make changes on the Controller?)
- **Documentation** - It's very important that the person that is going to read your code can easily run it and check how it works, so a good documentation on README.md is important. Also the code documentation gives it a good readability boost.
- **Test** - We should always try to test as much as possible, so keep that in mind during this test.
- **PEP8** - We suggest that you follow PEP8 Style Guide.
- **Git** - We suggest that you use a git service for your project (GitHub, GitLab, Bitbucket, etc) and that you use GitFlow during your development of this test. Try to create concise commits and if possible manage the features via issues.
- As an overall, write the code the way you would like to get the code you will have to maintain.

## Libraries / Stack *suggested*
- Framework - [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- GraphQL - [Graphene](https://graphene-python.org/) (you can also choose [Ariadne](https://ariadnegraphql.org/))
- Database - [SQLite](https://www.sqlite.org/index.html)
- Database Access - [Raw connection](https://docs.python.org/3/library/sqlite3.html)

## Nice to have, but not required
- Docker

## References
- https://dev.twitch.tv/docs/irc

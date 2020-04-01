# Local SQL Client
Local SQL client is a lightweight SQL client designed for cross-platform use for local development purposes only. 

The client was initially designed to assist with developing on small screen sizes. Unlike other SQL clients, this SQL client essentially gives you full height and width of your screen to write, view, and update queries.

* Version 1 of the client does not support schema, database, and table creation or altering. 
* Since Local SQL Client is built in Javascript, it is not safe to mounted to a remote server for any reason.
* Local SQL Client is safe to connect to a local or remote SQL database.

# Benefits
* Ideal for small screen sizes where many existing SQL clients fall short.
* Targets development efficiency with simplistic and customizable hotkeys.
* Operating system agnostic.
* Extremely light-weight.
* Simplistic.

# Version 1 Features (In Development)
* Add and edit SQL connections.
* Write an execute queries.
* Create, read, update and delete records through a GUI.
* Customizable hotkeys to: 
    * execute a query.
    * toggle between the query editor and the query response view allowing for a much taller viewing experience than MySQL Workbench or Heidi. 
    * toggle visibility of the view schema and table widgets allowing for must wider viewing experience than MySQL Workbench or Heidi.

# Version 2 Features
* Ability to create and alter schemas, databases, and tables.

# Installation
- TODO: can we wrap this in a docker container or something so people don't actually have to install VueJS or something. I could just build it in vanilla JS also.


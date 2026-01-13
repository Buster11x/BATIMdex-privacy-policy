# The following document explains what data is collected by BATIMdex.

# Glossary
"Application" or "Discord application" refers to the Discord bot user, its associated owners and the servers is has
"Data" refers to data stored by an individual instance, including personal data
"Bot" or "instance" refers to the copy of the code running the Discord application, with its own data
"Collectible" refers to any object that is meant to be collected, such as cartoons or other future means like virtual currency
"Application owners" refers to the owners of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance
"BATIMdex administration team" or "admin team" refers to the owners of the Discord application and the users they may chose to be part of the admin team. You may find a list of these users on the [Discord server](https://discord.gg/4Uv7ZXHevs).
Open source
The code of BATIMdex is open source under the MIT licence and available at https://github.com/laggron42/BallsDex-DiscordBot. A copy of the licence can be found below.

# The MIT licence
The instance is guaranteed to be running an exact copy of the code made open source. The version may not be the latest available (check /about), but no local changes will be made. This may change, but users should be notified in the Discord server about such change.

You may check the source code and see how the data is managed, in addition to the following policy.

# What data is collected
BATIMdex collects the following data from Discord:

User IDs, this is used to identify you inside our database
Server (or guild) IDs, this is used to store settings necessary to the bot's operation
Channel IDs, this is used to know in which channel should the collectibles spawn
In addition, the following data proper to BATIMdex is created and used:

The list of collectibles owned by a user of the service
A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore
How the data is stored
All data is stored on a PostgreSQL server, running on a Virtual Private Machine hosted by Oracle Corportation.

Interaction between the bot and the database server is exclusively local using Tortoise ORM.

# Access to the data
The only persons allowed to access the data are the application owners.

Any application owner may interact with the bot and the administrator interface. Only El Laggron#0260 has direct access on the host machine.

The BATIMdex staff team does not have access to the data.

The data may never be made available to the public, and its access must be secured accordingly.


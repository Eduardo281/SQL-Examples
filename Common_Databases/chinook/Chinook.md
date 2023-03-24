# The Chinook Database

The Chinook data model is a small and relatively simple database representing a digital media store. It includes tables for artists, albums, media tracks, invoices, and customers, and will be used to show the power of SQL in retrieving full or filtered data from a database.

Here we present the original file in .db format and a diagram describing its tables and relationships. All this contents can be downloaded from the SQLite Tutorial page [clicking here](https://www.sqlitetutorial.net/sqlite-sample-database/). A concise textual description about the tables found in chinook.db can be found in the same site, which we transcribe below:

* **employees:** stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.

* **customers:** table stores customers data.

* **invoices & invoice_items tables:** these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.

* **artists:** table stores artists data. It is a simple table that contains only the artist id and name.

* **albums:** table stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.

* **media_types:** table stores media types such as MPEG audio and AAC audio files.

* **genres:** table stores music types such as rock, jazz, metal, etc.

* **tracks:** table stores the data of songs. Each track belongs to one album.

* **playlists & playlist_track tables:** playlists table store data about playlists. Each playlist contains a list of tracks. Each track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.

Exploring the chinook database can be a very interesting SQL exercise, helping to practice and learn the data reading functionalities of the language.

**Important Note:** I am not the owner nor the creator of the chinook database or any related file. All the contents available here are responsibility of their creators and were included here only with education purposes. Users are encouraged to visit the original page by [clicking here](https://www.sqlitetutorial.net/sqlite-sample-database/).

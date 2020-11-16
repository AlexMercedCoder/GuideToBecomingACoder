# Databases

When you run any script or executable from any programming language, any data used or generated during the execution is saved in the RAM/Memory of the machine executing. Memory is short term and clears itself after the program is done executing so not a good place to save data you need during subsequent executions/processes. To Maintain persistent data we have databases and there are several databases available to use for different context.

First watch this video on several different database paradigms that is a great introduction into the world of databases.

[![7 Database Paradigms](http://img.youtube.com/vi/W2Z7fbCLSTw/0.jpg)](http://www.youtube.com/watch?v=W2Z7fbCLSTw "7 Database Paradigms")

## During Your Cohort

You will learn one document database (MongoDB) and one SQL Database (Postgres)

## MongoDB

MongoDB is a very popular Document Database. What makes Mongo different is that all data in Mongo is saved as text in a JSON like format called BSON. This makes the structure of the data very intuitive for javascript developers since its structure is like that of a javascript object.

- Collection: Is like any array collecting multiple pieces of data of the same type
- Documents: Are like Objects containing several related properties.

Cats => This would be a collection, an array of objects defining individual cats
Cat => A document in the collection, one object in the array with the properties of a cat
Schema => The Description of a Cat document (list of properties)

Schema are used by an ODM (Object Document Mapper) to make validate data going in and out of a database, an ODM also allows your application to connect to your mongo database. Mongoose is the most popular ODM which is used in Javascript.

### Installation

- [Mac](https://treehouse.github.io/installation-guides/mac/mongo-mac.html)
- [Linux](https://linuxhint.com/install_mongodb_ubuntu_20_04/)
- [Windows] (https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-windows-4ee4b3493514)

### Videos

- [Playlist](https://www.youtube.com/playlist?list=PLY6oTPmKnKbaSCVF-Imd1hkQJvl8iLrV3)

## Postgres

Postgres is one of the most popular types of SQL databases, only following MySQL because of its use in LAMP stack applications (Wordpress). SQL databases structure their data more like a spreadsheet in columns and rows.

Cat => This would be the table tracking many cats, a table is like an entire spreadsheet
Cats => This would be a record, this would be one row in a spreadsheet listing data for one cat
Schema => This would be the collection of fields that make up a cat, each field is one column of data

To connect your application to an SQL database you use an ORM (Object Relationship Mapper) below is a list of some of the ORMs in many languages.

- Javascript: Objection, Sequalize, TypeORM, Bookshelf
- Python: SQLAlchemy, PugSQL, DjangoORM, PonyORM
- Ruby: ActiveRecord
- GO: GORM, GO-PG, XORM
- PHP: EloquentORM, Propel, Doctrine
- Rust: Diesel, RustORM
- Kotlin: ktORM, Exposed, Ebean
- Swift: stORM, Swift-Kuery-ORM, Fluent
- Raku: ORM 7, Red, Xoos
- Perl: DBlx::Class, Rose::DB::Object, Fey::ORM

### Installation

- [Mac](https://postgresapp.com/)
- [Linux](https://www.digitalocean.com/community/tutorials/how-to-install-postgresql-on-ubuntu-20-04-quickstart)
- [Windows] (https://www.postgresqltutorial.com/install-postgresql/)

### Videos

- [Playlist](https://www.youtube.com/playlist?list=PLY6oTPmKnKbYC24jbJwOmekvsraIV8Gv7)

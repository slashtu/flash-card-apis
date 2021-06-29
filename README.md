# flash-card-apis
## Mongodb
Mac 

```brew services start mongodb-community@4.4```

```brew services stop mongodb-community@4.4```


sudo service mongod start

mongodump --db flashcard

mongodrestore --db flashcard dump/flashcard

mongorestore --db flashcard --drop flashcard

journalctl -u flashcard.service -b


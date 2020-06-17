## Simplest Database

### How it works

- To set a key in database:
  ```sh
    $ db_set 123456 '{"name":"London","attractions":["Big Ben","London Eye"]}' 
    $ db_set 42 '{"name":"San Francisco","attractions":["Golden Gate Bridge"]}'
  ```

- To get value of a key from database:
  ```sh
    $ db_get 42
    //{"name":"San Francisco","attractions":["Golden Gate Bridge"]}
  ```
  Note: This is taken from the book [DDIA](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321) 

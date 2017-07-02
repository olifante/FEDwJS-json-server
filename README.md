# json-server-init

To create a db.json file with some users, do this:

```
$ ./node_modules/.bin/json-server-init create
> Collection name and number of rows, 5 if omitted (ex: posts 10):  users 100
>> What fields should "users" have?
   Comma-separated fieldname:fieldtype pairs (ex: id:index, username:username)
 id:index, username:username, firstName:firstName, lastName:lastName, helper:bool, seeker:bool|true, languages:stringArray|3,1, bio:lorem|100, email:email, phone:phone
> Add another collection? (y/n) n
Url for users id={index}&username={username}&firstName={firstName}&lastName={lastName}&helper={bool}&seeker={bool|true}&languages={stringArray|3,1}&bio={lorem|100}&email={email}&phone={phone}&rows=100
db.json saved.
```
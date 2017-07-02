# json-server-init

To create a db.json file with some users, do this:

```
$ ./node_modules/.bin/json-server-init create
> Collection name and number of rows, 5 if omitted (ex: posts 10):  users 10
>> What fields should "users" have?
   Comma-separated fieldname:fieldtype pairs (ex: id:index, username:username)
 id:index, username:username, firstName:firstName, lastName:lastName, helper:bool, seeker:bool|true, languages:stringArray|3,1, bio:lorem|100, email:email, phone:phone
> Add another collection? (y/n) y
> Collection name and number of rows, 5 if omitted (ex: posts 10):  requests 20
>> What fields should "requests" have?
   Comma-separated fieldname:fieldtype pairs (ex: id:index, username:username)
 id:index, subject:lorem, seeker:username, date:date|10-10-2010,10-12-2010, location:addressObject, accepted:bool|false, helper:username
> Add another collection? (y/n) n
Url for users id={index}&username={username}&firstName={firstName}&lastName={lastName}&helper={bool}&seeker={bool|true}&languages={stringArray|3,1}&bio={lorem|100}&email={email}&phone={phone}&rows=10
Url for requests subject={lorem}&seeker={username}&date={date|10}&location={addressObject}&accepted={bool|false}&helper={username}&rows=20
db.json saved.
```
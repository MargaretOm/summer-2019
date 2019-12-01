# Branch 1: Top-Ruby-gems

As part of the assignment, we write a console utility that determines the popularity of Ruby gems.
The launch is performed by the following command:

```bash
ruby top_gems.rb
```


For each gem in this list, we find it Github repo, from the page of this repo we get the following data: Used by, Watch, Star, Fork, Contributors, Issues.

We can pass additional arguments:

- The `--top` parameter, shows the number of gems according to the rating:

```bash
ruby top_gems.rb --top=2
```

- The `--name` parameter, displays all Gems according to the rating whose name includes the given word:

```bash
ruby top_gems.rb --name=active
```

- The `--file` parameter, which is the path to the yml file containing the list of gem names:

```bash
ruby top_gems.rb --file=gems.yml
```
![](top_gems.gif)

# Branch 2: Telegram-bot

After registration, he will be able to “accept the shift” - /checkin and “hand over the shift” - /checkout.

Registration starts after the “/ start” command and prompts you to enter a number. If such a number already exists or the number does not match any of the list of all numbers (which are in the file in the _data_ folder of your project), then an error is displayed to the user. Otherwise, registration is successful and the user number along with his telegram_id is stored in the database.

![](bot.gif)

# Branch 3: Sinatra-city-places

On the main page, a list of places with a name, description and coordinates.

Leave feedback can only registered and logged in users.

## Technical description

For this assignment, used [Sinatra] (http://sinatrarb.com/). The database is sqlite.

![](places.gif)

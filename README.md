# JSBOT

## Quick linksa
1. [Colors You could use](https://github.com/dgbotdev/jsbotsource/blob/master/README.md#example-colors)
2. [Accounts](https://github.com/dgbotdev/jsbotsource/blob/master/README.md#accounts)
3. [Config per server](https://github.com/dgbotdev/jsbotsource/blob/master/README.md#configuration-per-server)
4. [How to set custom msg](https://github.com/dgbotdev/jsbotsource/blob/master/README.md#set-custom-msg)
5. [Profiles and registering](https://github.com/dgbotdev/jsbotsource/blob/master/README.md#profiles-and-registering)


## Commands for JSBot

[] = optional  <> = required

| Command       | Desc     | Usage     |
| :------------- | :----------: | -----------: |
|  'help | Shows commands, botinfo, serverinfo, userinfo   | `'help [commandname]`   |
|  'profile | Shows your profile (need account, __see accounts__)   | `'profile [help,setbio,setnick,setcolor,setclr,show]`    |
|  'register | Register for account   | `'register`    |
|  'cb | Create a code block in any discord supported language   | `'cb <lang> <code>`    |
|  'conf | Show current configuration for your server ('conf help for commands)   | `'conf [help,vars,setlogsch,setprefix,setwelcomemsg,setleavemsg]`    |
|  'sudo | OWNER ONLY  | `'sudo [commandname]`    |
|  'reload | OWNER ONLY   | `'reload [commandname]`    |
|  'updates | Show updates for the bot   | `'updates [set,clear]`    |



## Accounts
JSBot accounts is a feature that sticks troughout servers, for example you are in `A server`, you create and account with `'register`, and you change up the values in your account with the various `'profile help` commands. Now in `The server` you do `'profile` the values are SAVED! This is accomplished by using a database.



## Configuration per server
JSBot configs is a feature like most bots have, you can set a prefix, set a welcome message or leave message, and select a loging channel. What we have created is 1 command, that has command arguements that you can use. Hence why there isnt 10 commands for just 1 function! These settings are only for guild adminstrators, so if your guild-admins would want to change anything thats how.



## Set custom msg
JSBot has custom leave/join messages, (see Configuration per server). It might be complicated to set a welcome message or leave message for some people, here is an example: `'conf setwelcomemsg {user} has joined {server} hope you have a great time here please read our rules!`. There are 2 vars there `{user}` and `{server}` these are custom made vars that you can use as many times in your leave/join messages. You can view thier purpose here: `'conf vars`



## Profiles and registering
On JSBot you can create profiles (see accounts), this is a walkthrough on how to change your settings on your account.

1. Lets create an account: `'register` This will take 3 seconds usually, and it will prompt you with a message when it completes
2. Lets change our bio! : `'profile setbio <Anything here>` After that it will show you a message saying that it has changed.
3. Lets change our nickname : `'profile setnick <anything>` After that it will show you a message saying that it has changed.
4. Lets change our color : `'profile setcolor(setclr) <HEX OR DISCORD COLOR>` After that it will show you a message saying that it has changed.
What does `DISCORD COLOR` mean: See example colors!
5. Lets change our hobbies : `'profile sethobbies <hobbies>` After that it will show you a message saying that it has changed.
6. You have changed all your values now! Lets view them with `'profile`!



## Example colors

`THEY MUST BE CAPITALS!!`

You can also use just default hex [Hex Color Picker](https://www.bing.com/search?q=hex+color+picker&PC=U316&FORM=CHROMN)

1. DEFAULT
2. AQUA
3. GREEN
4. BLUE
5. PURPLE
6. LUMINOUS_VIVID_PINK
7. GOLD
8. ORANGE
9. RED
10. GREY
11. DARKER_GREY
12. NAVY
13. DARK_AQUA
14. DARK_GREEN
15. DARK_BLUE
16. DARK_PURPLE
17. DARK_VIVID_PINK
18. DARK_GOLD
19. DARK_ORANGE
20. DARK_RED
21. DARK_GREY
22. LIGHT_GREY
23. DARK_NAVY
24. RANDOM


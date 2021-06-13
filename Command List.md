# Content 

Full command list for Oreo, with Name, description, aliases, usage and few examples.

## Modules/Categories 



<details>
<summary> Config [15] </summary> 

 Name: `?Autorole` <br>
 Description: Automatically gives new members one or multiple roles upon joining the guild. <br>
 Usage: `?autorole` <br>
<br>
<br>
 Name: `?ChannelCounter` <br>
 Aliases: `?ccounter` <br>
 Description: Creates guild stat channel counters. <br>
 Usage: `?channelcounter <create/delete/reset>` <br>
  <br>
create  <br>
Creates or edit a channel counter. <br>
 <br>
delete  <br>
Deletes a channel counter. <br>
 <br>
reset  <br>
Clears all counter settings. <br>
<br>
<br> 
 Name: `?logging` <br>
 Description: Sets up Oreo's logging features. <br>
 Usage: <br>
<br>
<u>Messages</u> <br>
`?logging messages logchannel` - Set a logchannel for logging deleted & Edited messages. <br>
`?logging messages ignore` - Sets ignored channels, set channels will not be logged. <br>
`?logging messages reset` - Clears all message logging settings. <br>
<br>
<u>Join</u><br>
`?logging join logchannel` - Sets the welcome channel. <br>
`?logging join message` - Customise member join message. <br>
`?logging join reset` - Clears all welcome settings.<br>
<br>
<u>Leave </u><br>
`?logging leave message` - Customise Member leave message. <br>
`?logging leave logchannel` - Set a logchannel for members who left. <br>
`?logging leave reset` - Clears all leave settings. <br>
<br>
<br>
 Name: `?permissions` <br>
 Aliases: `?perms` <br>
 Description: Configures permissions of specific commands for users, roles and @everyone. <br>
 Usage: <br>
`?permissions <allow|deny|show|clear|reset> <user:mention/id|role:mention/id|everyone|channel:mention/id > <permission:category.command>` <br>
 Examples: <br>
`?permissions allow @staff moderation.all` <br>
`?permissions deny #general info.ping` <br>
`?permissions clear @user all` <br>
<br>
<br>
 Name: `?pollemotes` <br>
 Description: Creates guild stat channel counters. <br>
 Usage: `?pollemotes`
<br> 
<br>
 Name: `?prefix` <br>
 Aliases: `?px` <br>
 Description: Changes Oreo's prefix. <br>
 Usage: `?prefix <new prefix>` <br>
 Example: `?prefix %` 
<br>
<br>
 Name: `?reactionroles`<br>
 Aliases: `?rero` , `?reactionrole`<br>
 Description: Configures reaction roles.<br>
 Usage: <br>
`?rero create <MessageID>` = Creates a new rero menu or adds a reaction.<br> <br>
`?rero delete <MessageID> [role:mention/id]`- Deletes a rero menu or removes a reaction.<br> <br>
`?rero refresh <MessageID>` - Clears all reactions off a rero menu and re-adds them.<br> <br>
`?rero dms <MessageID>` - DMs user when roles are given/taken<br> <br>
`?rero rr <MessageID>` - Automatically removes user's reaction<br> <br>
`?rero ignorerole <MessageID> <role:mention/id>` - Removes reactions of users with ignores roles without assigning a role. <br>
<br>
Tip: Oreo must be in the server the emoji is from and you must run the command in the same channel the message is in.
<br>
<br>


Name: `?setup-previousban`<br>
Aliases: `?spb`<br>
Description: Manages Oreo's behavior towards previously banned members.<br>
Premium: True<br><br>
 
 Example: `?setup-previousban  {option}`<br><br>

track<br>
Toggle whether or not Oreo should track unbanned users<br><br>

role <br>
Assigns unbanned members a specific role.<br><br>

auto-assign<br>  
Toggle whether or not Oreo should auto assign the unbanned role to users<br><br>

add  <user:mention/ID> <Reason><br>
Adds a specific user to the database<br><br>

delete  <user:mention/ID><br>
Removes a specific user from the database<br>
<br>
clear <br>
Deletes all saved unban data indefinitely.<br>

 <br><br>

 Name: `?setmutedrole` <br>
 Description: Sets the muted role for further moderation purposes. <br>
 Usage: `?setmutedrole [color:name/hex]`

<br>
<br>

 Name: ```?setup-autovc``` <br>
 Aliases: ```?setup-avc``` , ```?savc``` <br>
 Description: Give members access to creating their own custom Voice Channels and giving them full permission over said channel, by being 
 allowed to (un)lock, (un)mute and more actions. For a full command list check Voice commands in the help menu. <br>
 Usage: ```?setup-autovc <autocreate  | create | autotransfer | disablecommands | namestructure | channellimit | delete | reset | settings> Number> [args]``` <br>
<br>
autocreate <br>
Automatically creates a new custom VC service including the required channels. (recommended for beginners)<br>
<br>
create <br>
Creates a new custom VC service. (recommended for experienced users)<br>
<br>
autotransfer <br>
Toggle between automatically transferring host or instantly deleting the VC when the current host disconnects.<br>
<br>
namestructure <br>
Sets a name structure which is used when a voice channel is created.<br>
<br>
channellimit <br>
Sets the limit of the maximum amount of active custom VC can exist in a category.<br>
<br>
disablecommands <br>
Toggle voice channel commands on and off. For more info on the commands check .help voice<br>
<br>
settings <br>
Displays current saved settings.<br>
<br>
delete <br>
Deletes a specific saved custom VC service.<br>
<br>
reset  <br>
Clears all saved data.
<br>
<br>
 Name: `?setup-customvc` <br>
 Aliases: `?setup-cvc` , `?scvc` <br>
 Description: Give members access to creating their own custom Voice Channels and giving them full permission over said channel, by being allowed to (un)lock, (un)mute and more actions. For a full command list check Voice commands in the help menu.<br>
 Usage: `?setup-customvc {option}`<br>
<br>
create <br>
Creates a new custom VC service. (recommended for experienced users)<br>
<br>
autotransfer <br>
Toggle between automatically transferring host or instantly deleting the VC when the current host disconnects.<br>
<br>
namestructure <br>
Sets a name structure which is used when a voice channel is created.<br>
<br>
channellimit <br>
Sets the limit of the maximum amount of active custom VC can exist in a category.<br>
<br>
disablecommands <br>
Toggle voice channel commands on and off. For more info on the commands check ?help voice<br>
<br>
whitelist <br>
Ignores whitelisted voice channel(s) thus not deleting them when no one is connected.<br>
<br>
settings <br>
Displays current saved settings.<br>
<br>
delete <br>
Deletes a specific saved custom VC service.<br>
<br>
reset <br>
Clears all saved data.<br>
<br>
<br>

 Name: `?setup-middleman` <br>
 Aliases: `?setup-mm` , `?smm` <br>
 Description: Setup middleman services. <br>
 Usage: `?smm <message|queue|category|logchannel|roles|ping|limit|cooldown|expireduration|reaction|welcomemessage|lbreset|lbclearuser|reset>`<br>
 Premium: True <br>
  <br>
message <br>
Set the Middleman Request message. <br>
 <br>
category  <br>
Container where requests channel will be created in. <br>
​ <br>
queue <br>
Channel where middleman requests are queued in. <br>
​ <br>
logchannel <br>
Channel to log completed and cancelled requests. <br>
​ <br>
role  <br>
Sets the Middleman role. <br>
​ <br>
viewrequests  <br>
Allows set roles to view middleman request channels. <br>
​ <br>
ping  <br>
Notifies the Middleman role when a request is created. <br>
​ <br>
limit <br>
Set a limit of how many active requests a user can have. <br>
​ <br>
cooldown  <br>
Sets the cooldown a user gets before they are able to request again. <br>
​ <br>
expireduration  <br>
Sets the duration for unclaimed requests to auto-cancel. <br>
​ <br>
reaction  <br>
Changes the request emote. <br>
​ <br>
welcomemessage <br>
Sets a welcome message when a request is created. <br>
​ <br>
dmmessages  <br>
Changes what Oreo DM users regarding their request status. <br>
​ <br>
enabletemplb  <br>
Toggle Temporary leaderboard ON and OFF. <br>
​ <br>
templbreset  <br>
Clears middleman leaderboard indefinitely. <br>
​ <br>
templbclearuser  <br>
Clears specific user leaderboard stats. <br>
​ <br>
lbreset  <br> 
Clears middleman leaderboard indefinitely. <br>
​ <br>
lbclearuser  <br>
Clears specific user leaderboard stats. <br>
​ <br>
reset  <br>
Clears all settings & leaderboard.
<br>
<br>

 Name: `?setup-moderation`<br>
 Aliases: `?smoderation` , `?smod`<br>
 Description: Setup moderation.<br>
 Usage: `?setup-moderation <log | enable | nodms | unpingable | maxlines | takeroles | reset >`<br>

enable <br>
Enables and disables moderation commands.<br>
<br>
logchannel <br>
Sets moderation log channel.<br>
<br>
nodms <br>
Sets which moderation commands shouldn't send out DMs to users<br>
<br>
unpingable <br>
Toggles whether Oreo should auto rename unpingable usernames or not.<br>
<br>
maxlines<br>
Deleting any messages going over set line limit.<br>
<br>
takeroles <br>
Strips a member from all their roles when muted.<br>
<br>
reset <br>
Clears all moderation settings & warnings.
<br>
<br> 

Maxlines Options <br>
Usage: `?setup-moderation maxlines {option}`<br>
<br>
enable <br>
Enables and disables maxLines detector.<br>
<br>
linelimit <br>
Sets maximum amount of allowed new lines a message may contain.<br>
<br>
warnlimit <br>
Sets the maximum amount of warnings a user may receive before getting punished.<br>
<br>
muteduration <br>
Sets the mute duration for users who reached the warning limit<br>
<br>
ignore <br>
Sets ignored channels
<br>
<br>
 Name: `?setup-suggestions`<br>
 Aliases: `?setup-suggestion` , `?ssuggest`<br>
 Description: Configures suggestion settings.<br>
 Usage: `?setup-suggestions <emotes | channels | dms | reset>`
<br>
<br>
channels <br>
Assigns channels where suggestions may be created in.<br>
<br>
emotes <br>
Changes suggestion emotes.<br>
<br>
dms <br>
Toggles whether or not Oreo should notify the suggestion creator when their suggestion gets liked or disliked by a staff member.<br>
<br>
reset <br>
Clears all suggestion settings and reset suggestion count.
<br>
<br>
 Name: `?setup-tickets`<br>
 Aliases: `?setup-ticket` , `?sticket`<br>
 Description: Configures ticket settings.<br>
 Usage: `?setup-tickets {option}`<br>
<br>
<br>
Avaialble Options<br>
<br>
`?setup-tickets automatically`<br>
 Let Oreo automatically pick the best settings for your server.<br>
<br>
`?setup-tickets manually`<br>
 Looping through questions in order to setup up the bot.<br>
<br>
`?setup-tickets settings`<br>
 View the current settings.<br>
<br>
`?setup-tickets refresh`<br>
 Repost the reaction menu in :ticket:create-a-ticket.<br>
<br>
`?setup-tickets Enable`<br>
 Toggle the ticket system ON and OFF.<br>
<br>
`?setup-tickets reset`<br>
 Reset ticket configuration. All data will be lost for good<br>
<br>
`?setup-tickets pingroles`<br>
 Edit which roles should be pinged when a ticket is created<br>
<br>
`?setup-tickets logchannel`<br>
 Edit ticket log channel<br>
<br>
`?setup-tickets channelstructure`<br>
 Edit the ticket name structure.<br>
<br>
`?setup-tickets reaction`<br>
 Edit ticket reactions.<br>
<br>
`?setup-tickets embed`<br>
 Edit Oreo's :ticket:create-a-ticket embed.<br>
<br>
`?setup-tickets pastebin`<br>
 Edit link/image storage channel.<br>
<br>
`?setup-tickets category`<br>
 Edit the category where tickets are created in.<br>
<br>
`?setup-tickets channel`<br>
 Edit the channel where tickets can be made.<br>
<br>
`?setup-tickets roles`<br>
 Edit the roles that can view a ticket.<br>
<br>
`?setup-tickets ping`<br>
 Edit whether or not roles should be pinged when a ticket gets created.<br>
<br>
`?setup-tickets cooldown`<br>
 Edit the duration of ticket cooldowns.<br>
<br>
`?setup-tickets dms`<br>
 Allow the bot to send DMs to users.<br>
<br>
`?setup-tickets deleter`<br>
 Edit whether or not the ticket deleter should be anonymous.<br>
<br>
`?setup-tickets logs`<br>
 Edit whether or not to store the ticket logs<br>
<br>
`?setup-tickets archive`<br>
 Edit whether or not to archive ticket transcriptions.<br>
<br>
`?setup-tickets selfdelete`<br>
 Edit whether or not the user should be able to self delete tickets.<br>
<br>
`?setup-tickets ticketlimit`<br>
 Edit the max amount of tickets a user can make at a time.<br>
<br>
`?setup-tickets autodelete`<br>
[PREMIUM] Edit ticket auto deletion.<br>
<br>
`?setup-tickets autodeleteduration`<br>
[PREMIUM] Edit ticket auto deletion duration.<br>
e.g. 5m, 10minutes

Reaction Options, reaction settings will override global settings.<br>
<br>
Usage: `?setup-tickets reaction {option}`<br>
<br>
ADD <br>
Adds an emote to a reaction menu.<br>
<br>
REMOVE <br>
Removes an emote from the reaction menu.<br>
<br>
EDIT <br>
Edits [ Emote | Name | Description ] of a reaction.<br>
<br>
POSITION <br>
Rearrange the position of a reaction in a reaction menu. <br>
<br>
EMBED<br>
Fully customizes the welcome embed of a reaction.<br>
<br>
ROLES <br>
Restricts a ticket to set roles.<br>
<br>
PINGROLES <br>
Sets role to ping when a ticket is created.<br>
<br>
ENABLE <br>
Enables/Disables a ticket reaction.<br>
<br>
SETTINGS <br>
Views server's current reaction settings.
<br>
<br>
 Name: `?streamnotifier`<br>
 Aliases: `?stream`<br>
 Description: Stream notification settings.<br>
 Usage: `?streamnotifier <channel | message | blacklist | streamers | liverole | reset>`<br>
<br>
<br>
Available Options: <br>
channel <br>
Sets stream announcement channel.<br>
<br>
message <br>
Creates a custom stream notifier message.<br>
<br>
streamers <br>
Sets roles/users that will be announced while streaming.<br>
<br>
blacklist <br>
Sets blacklisted games, streamers playing these games will not be announced.<br>
<br>
liverole <br>
Assigns a role to currently streaming users.<br>
<br>
reset <br>
Clears all stream settings.
</details>




<details>
  <summary> Games [1] </summary>
  
  
 Name: `?mute-roulette`<br>
 Aliases: `?muter`<br>
 Description: Every 5 seconds a participant gets removed until there is only one remaining. The last man standing gets muted!<br>
 Usage: `?mute-roulette [duration:time]`<br>
 Premium: True <br>
  </details>

<details>
  
<summary> Giveaways [12]</summary> 


</details>
 
<details>
 <summary> Info [8] </summary>
 
 Name: `?donate` <br>
 Aliases: `?patreon` , `?premium` <br>
 Description: Link to Oreo's Patreon page. <br>
 <br>
 <br>
 Name: `?getid` <br>
 Description: Gets ID of mentioned user, role or channel. <br>
 Usage: `?getid <user:mention/username/nickname | channel:mention/name | role:mention/name | Category:name>` <br>
 <br>
 <br>
 Name: `?help` <br>
 Aliases: `?commands` , `?cmds` , `?oreo` , `?info` <br>
 Description: Get additional information about Oreo's commands <br>
 Usage: `?help <module|command>` <br>
 Examples: <br>
`?help setup-ticket` <br>
`?help all` <br>
`?help config` <br>
 <br>
 <br>
 Name: `?invite` <br>
 Aliases: `?link` , `?inv` <br>
 Description: Invite Oreo to your server. <br>
 <br>
 <br>
 Name: `?mywarnings` <br>
 Aliases: `?mywarns` <br>
 Description: Displays your warnings. <br>
 <br>
 <br>
 Name: `?ping` <br>
 Aliases: `?pong` <br>
 Description: Measures Oreo's real-time network connection in milliseconds. <br>
 <br>
 <br>
 Name: `?stats` <br>
 Description: Oreo's global statistics. <br>
 <br>
 <br>
 Name: `?uptime` <br>
 Description: Oreo's current runtime. <br>
  </details>

<details>
  <summary> Middleman [5] </summary>
  Empty
</details>

<details>
  <summary> Moderation [17] </summary>
  
 Name: `?ban` <br>
 Aliases: `?hammer`  <br>
 Description: Bans a user off the server <br>
 Usage: `?ban <user:mention/ID> [reason]` <br>
<br>
<br>
 Name: `?botclear` <br>
 Aliases: `?bc` <br>
 Description: Deletes multiple messages sent by bots <br>
 Usage: `?botclear [Number:min=1/max=100 - default=15]` <br>
 Example: `?botclear 30` 
<br>
<br>
 
Name: `?previousban`
Aliases: `?pb`
Description: Fetches a user's ban reason prior to being unbanned.
Usage: ?previousban [user:mention/ID]
Premium: True
<br>
 <br>
 Name: `?clear` <br>
 Aliases: `?sweep` , `?purge` <br>
 Description: Deletes multiple messages instantly. Using `-nopin` will ignore pinned messages. Range is 1-100. <br>
 Usage: `?clear <Number> [user:mention/ID] [-nopin]`
<br>
<br>
 Name: `?deletverbalwarn` <br>
 Aliases: `?dvw` , `?dvwarn` <br>
 Description: Removes a user's verbal infraction. <br>
 Usage: `?deletverbalwarn <user:Mention/ID> <warn:ID>`
<br>
<br>
 Name: `?deletewarn` <br>
 Aliases: `?dw` , `?dwarn` <br>
 Description: Removes a user's infraction. <br>
 Usage: `?deletewarn <user:Mention/ID> <warn:ID>` 
<br>
<br>
 Name: `?getban` <br>
 Aliases: `?gb` <br>
 Description: Fetches a user's ban reason. <br<>
 Usage: `?getban [user:mention/ID]` 
<br>
<br>
 Name: `?kick` <br>
 Description: Kicks a user off the server. <br>
 Usage: `?kick <user:mention/ID> [reason]` <br>
<br>
<br>
 Name: `?mute` <br>
 Description: Mutes a user. <br>
 Usage: `?mute <user:mention/ID> [duration] [reason]` <br>
 Example: `?mute @errosenn 10minutes Bad behavior.` <br>
<br>
<br>
 Name: `?nickname`<br>
 Aliases: `?nn` , `?nick`<br>
 Description: Change a user's nickname<br>
 Usage: `?nickname <user:mention/ID> [nickname]`
<br>
<br>
 Name: `?unmute` <br>
 Description: UnMutes a user. <br>
 Usage: `?unmute <user:mention/ID> [reason]` <br>
 Example: `?unmute @errosenn OWO` <br>
<br>
<br>
 Name: `?unban`<br>
 Aliases: `?unhammer`<br>
 Description: unbans a member<br>
 Usage: `?unban <user:mention/ID> [reason]`
<br>
<br>
 Name: `?unbanall`<br>
 Aliases: `?unbanwave`<br>
 Description: unbans every banned user<br>
 Owner only: true
<br>
<br>
 Name: `?unpingable` <br>
 Aliases: `?up` <br>
 Description: Changes unpingable usernames <br>
 Usage: `?unpingable <user:mention/ID> [nickname]` <br>
<br>
<br>
 Name: `?verbalwarn`<br>
 Aliases: `?vwarn`<br>
 Description: Warns a user verbally<br>
 Usage: `?verbalwarn <user:ID> [reason]`
<br>
<br>
 Name: `?verbalwarnings`<br>
 Aliases: `?vwarns` , `?vws`<br>
 Description: Checks user's verbal warning infractions<br>
 Usage: `?verbalwarnings <User:Mention/ID>`
<br>
<br>
 Name: `?warn`<br>
 Description: Warns a user<br>
 Usage: `?warn <user:ID> [reason]`
<br>
<br>
 Name: `?warnings`<br>
 Aliases: `?warns`<br>
 Description: Checks a user's infractions<br>
 Usage: `?warnings <user:Mention/ID>`
</details>


  
<details>
  <summary> Suggestions [5]</summary>
  
 Name: `?approve` <br>
 Aliases: `?like` <br>
 Description: Approves a submitted suggestion using the Message ID (sID). You can find the sID in the footer of any suggestion.<br>
 Usage: `?approve <messageID> [response]`
<br>
<br>
clearresponse 
<br>
<br>
 Name: `?reject`<br>
 Aliases: `?dislike`<br>
 Description: Approve a submitted suggestion via the suggestion ID (sID). You can find the sID in the footer of any suggestion.<br>
 Usage: `?reject <messageID> [response]`
<br>
<br>
 Name: `?suggest`<br>
 Aliases: `?suggestion`<br>
 Description: Submits a new suggestion.<br>
 Usage: `?suggest <suggestion>`<br>
 Examples: `?suggest I am writing a random suggestion right now.`
<br>
<br>
 Name: `?suggestion-leaderboard`<br>
 Aliases: `?suggestlb` , `?slb`<br>
 Description: Suggestion leaderboard<br>
 Premium: True
</details>

<details>
  <summary> Tickets [9] </summary> 
  
 Name: `?add`<br>
 Description: Adds a user to a ticket.<br>
 Usage: `?add <user:mention/ID>`
<br>
<br>
 Name: `?adminonly`<br>
 Description: Removes everyone from a ticket<br>
 Usage: `?adminonly`
<br>
<br>
 Name: `?timed-delete`<br>
 Aliases: `?td` , `?tdel`<br>
 Description: Deletes a ticket after set time period<br>
 Usage: `?timed-delete <duration> [reason]`<br>
 Examples: `?timed-delete 15m AFK.`
<br>
<br>
 Name: `?claim`<br>
 Description: Claims a ticket, makes ticket  read-only for all support users ignoring user who've claimed the ticket. <br>
 Usage: `?claim` 
<br>
<br>
 Name: `?delete`<br>
 Aliases: `?c` , `?del` , `?close`<br>
 Description: Deletes a ticket<br>
 Usage: `?delete [reason]`<br>
 Examples: `?delete No response.`
<br>
<br>
 Name: `?remove`<br>
 Aliases: `?rem`<br>
 Description: Removes user(s) from a ticket.<br>
 Usage: `?remove <user:mention/ID>,<user:mention/ID>....`
<br>
<br>
 
 
 ❯ Name:  `?rename`
❯ Aliases: `?r`
❯ Description: Renames a ticket.
❯ Usage: ?rename <channel_name>
<br>
<br>
 Name: `?ticket-leaderboard`<br>
 Aliases: `?tlb` , `?ticketlb`<br>
 Description: Ticket leaderboard<br>
 Premium: True
<br>
<br>
 Name: `?unclaim`<br>
 Description: Unclaims a ticket, reverts ticket's permission for sending messages for all support roles <br>
 Usage: `?unclaim` <br>
</details>

<details>
  <summary> Utility [12] </summary> 
  
 Name: `?8ball`<br>
 Description: Ask 8ball a question<br>
 Usage: `?8ball <question>`<br>
  <br>
  <br>
 Name: `?avatar`<br>
 Aliases: `?av`<br>
 Description: Fetches avatar of mentioned user.<br>
<br>
<br>
 Name: `?customembed`<br>
 Aliases: `?ce`<br>
 Description: Creates a custom embed using Oreo.<br>
 Usage: `?customembed <channel:mention/id> [messageID] [messageID channel:mention/id]`<br>
 Examples:<br>
?customembed #general<br>
?customembed #general 000000000 #announcements<br>
<br>
<br>
 Name: `?djs`<br>
 Description: Discord.js documention<br>
 Usage: `?djs <args>`<br>
  <br>
  <br>
 Name: `?enlarge`<br>
 Description: Enlarges custom emotes.<br>
 Usage: `?enlarge <emote>`  <br>
<br>
<br>
 Name: `?getepic`<br>
 Aliases: `?epic`<br>
 Description: Fetches EPIC usernames using gamertags<br>
 Usage: `?getepic <username:Epic/Gamertag>`<br>
 Premium: True<br>
<br>
<br>
 Name: `?ghost`<br>
 Aliases: `?g`<br>
 Description: Allows user to vanish by deleting their past 30 messages in a channel. :ghost:<br>
<br>
<br>
 Name: `?poll`<br>
 Description: Start a vote.<br>
 Usage: `?poll <topic:text> =[option1:text] =[option2:text] upto option10.`<br>
 Examples:<br>
`?poll is this a good example?`<br>
`?poll Is it clear enough now?=Yup=Nope=Not sure`<br>
<br>
<br>
 Name: `?undo`<br>
 Aliases: `?snipe` , `?expose`<br>
 Description: Fetches the last deleted message in a channel<br>
<br>
<br>
 Name: `?tts`<br>
 Aliases: `?texttospeech`<br>
 Description: Converts a message to a speech recording.<br>
Supported languages: `en`, `en-uk`, `en-us`, `en-in`, `en-au`, `en-ng`, `nl`, `de`, `fr`, `ru`, `in`, `es`, `ja`, `ko`, `no`, `ar`, `tr`<br>
 Usage: `?tts [language] <message>`<br>
 Examples:<br>
`?tts Hey, I love Oreos`<br>
`?tts fr J'aime la baguette`<br>
  <br>
<br>
 Name: `?upload`<br>
 Aliases: `?attach` , `?att`<br>
 Description: Upload files<br>
 Usage: `?upload <link:url><br>
                 [link2:url]<br>
                 [link3:url]`<br>
<br>
<br>
 Name: `?yoink`<br>
 Aliases: `?newemote`<br>
 Description: Creates an emote.<br>
 Usage: `?yoink <emote/link> [name]`<br>
 Examples:<br> `?yoink <:oreo_success:730830015306137721> yoinked`<br>
</details> 

<details>
  <summary> Voice [11]  </summary> 
  
  </details> 
  

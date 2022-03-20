Commands
=====

Administration
------------

server
~~~~~~~~~~~

Full command: server  <setting>

Use this to access server settings.

server freeze-restrictions
~~~~~~~~~~~

Full command: server freeze-restrictions  <channel>

Use this to freeze global raid restrictions on a raid channel. This will only allow the current pok�mon that are in raids of the tiers your raid channel has restrictions on.

server mystic-role
~~~~~~~~~~~

Full command: server mystic-role  <role>

Use this to change the mystic role in your server.

server change-nicknames
~~~~~~~~~~~

Full command: server change-nicknames 

Use this to change the nicknames of every member in your server to their corresponding in-game name (only if set).

server online-channel
~~~~~~~~~~~

Full command: server online-channel  [channel=None] [tier=all]

Use this to set the channel in which you'll receive raids from other servers.

server raid-restrictions
~~~~~~~~~~~

Full command: server raid-restrictions  <channel> <restrictions>

Use this to set raid restrictions on an existing raid channel. You can either use tier restrictions or pok�mon restrictions, but not both.

server moderator-role
~~~~~~~~~~~

Full command: server moderator-role  <role>

Use this to change the moderator role in your server.

server raid-info
~~~~~~~~~~~

Full command: server raid-info 

Use this to check information about raid channels in your server.

server log-channel
~~~~~~~~~~~

Full command: server log-channel  [channel=None]

Use this to set the channel in which you'll receive logs from the raids on your server.

server prefix
~~~~~~~~~~~

Full command: server prefix  <prefix>

Use this to change the prefix on your server. You can only use one character as a prefix.

server instinct-role
~~~~~~~~~~~

Full command: server instinct-role  <role>

Use this to change the instinct role in your server.

server setup-channel
~~~~~~~~~~~

Full command: server setup-channel  [channel=None]

Use this to set the channel in which Nexus will mention players when they try to create or join raids and they don't have permission to do so.

server raid-channel
~~~~~~~~~~~

Full command: server raid-channel  <channel>

Use this to set the channel in which raids will be posted. Only the raid command will work on this channel.

server main-raid-channel
~~~~~~~~~~~

Full command: server main-raid-channel  [channel=None]

Use this to set the channel in which all raids will be visible.

server info
~~~~~~~~~~~

Full command: server info 

Use this to check information about your server.

server toggle
~~~~~~~~~~~

Full command: server toggle  <setting>

Use this to access toggle configuration.

server toggle join-multiple-raids
~~~~~~~~~~~

Full command: server toggle join-multiple-raids 

Use this to toggle on/off allowing trainers to join more than one raid at the same time in your server.

server toggle force-nickname
~~~~~~~~~~~

Full command: server toggle force-nickname 

Use this to toggle on/off forcing nicknames of members of your server to be their respective in-game trainer names.

server toggle online-raids
~~~~~~~~~~~

Full command: server toggle online-raids 

Use this to toggle on/off being able to send raids to other servers in your server.

server toggle automoderator
~~~~~~~~~~~

Full command: server toggle automoderator 

Use this to toggle on/off the automoderator, this will prevent/allow users with negative points to join and create raids.

server toggle auto-counters
~~~~~~~~~~~

Full command: server toggle auto-counters 

Use this to toggle on/off inserting counters automatically in raids.

server toggle autoroles
~~~~~~~~~~~

Full command: server toggle autoroles 

Use this to toggle on/off roles being created automatically when someone clicks the notification button.

server toggle unfriend
~~~~~~~~~~~

Full command: server toggle unfriend 

Use this to toggle off/on the unfriend the host message when a raid ends. This doesn't apply to raids from other servers.

server toggle public-raids
~~~~~~~~~~~

Full command: server toggle public-raids 

Use this to toggle off/on public raids in your server. Anyone can interact with the raids if turned on.

server toggle screenshot-scanning
~~~~~~~~~~~

Full command: server toggle screenshot-scanning 

Use this to toggle on/off scanning screenshots in raid and profile channels.

server valor-role
~~~~~~~~~~~

Full command: server valor-role  <role>

Use this to change the valor role in your server.

server profile-channel
~~~~~~~~~~~

Full command: server profile-channel  [channel=None]

Use this to set the channel in which Nexus will scan screenshots to update trainer profiles.

rr
~~~~~~~~~~~

Aliases: reaction-role

Full command: rr  <setting>

Use this to access reaction roles.

rr view
~~~~~~~~~~~

Full command: rr view 

Use this to view all your reaction roles. There's a limit fo 50 per server.

rr delete
~~~~~~~~~~~

Full command: rr delete  <message_id> <channel_id>

Use this to delete a reaction role from your server. You can also manually delete the message.

rr create
~~~~~~~~~~~

Full command: rr create  <message_id> <channel> <emoji> <role>

Generic reaction role implementation.

pokebattler-raid-network
~~~~~~~~~~~

Aliases: pokebattler, prn

Full command: pokebattler-raid-network  <setting>

Use this to access settings for the Pokebattler Raid Network.

pokebattler-raid-network permanent-invite
~~~~~~~~~~~

Full command: pokebattler-raid-network permanent-invite  <permanent_invite_url>

Use this to set a permanent invite for this server on the Pokebattler Raid Network.

pokebattler-raid-network feed
~~~~~~~~~~~

Full command: pokebattler-raid-network feed 

Use this to create a channel with the Pokebattler Raid Network feed. Raids from other servers will appear in here and you can join them through the app or by joining the remote server.

pokebattler-raid-network toggle
~~~~~~~~~~~

Full command: pokebattler-raid-network toggle 

Use this to turn on/off the pokebattler raid network in your discord server.

leaderboard
~~~~~~~~~~~

Full command: leaderboard  <setting>

Use this to access leaderboard settings.

leaderboard unban
~~~~~~~~~~~

Full command: leaderboard unban  <user>

Use this to make a user appear on the leaderboard again.

leaderboard automatic
~~~~~~~~~~~

Full command: leaderboard automatic  <channel>

Use this to send an automatic leaderboard that will update every 24 hours.

leaderboard view
~~~~~~~~~~~

Full command: leaderboard view  [recent=True]

Use this to see the top 10 trainers who have joined and hosted raids, as well as the ones with more points. You can specify if you want to retrieve the most recent leaderboard or the all-time leaderboard.

leaderboard extended
~~~~~~~~~~~

Full command: leaderboard extended  [recent=True]

Use this to view the complete leaderboard.

leaderboard ban
~~~~~~~~~~~

Full command: leaderboard ban  <user>

Use this to remove a user from appearing on the leaderboard.

leaderboard reset
~~~~~~~~~~~

Full command: leaderboard reset 

Use this to reset the leaderboard.

award
~~~~~~~~~~~

Full command: award  <setting>

Use this to access award settings.

award badge
~~~~~~~~~~~

Full command: award badge  <user> <badge_name>

Use this to award a badge to a user.

award upgrade
~~~~~~~~~~~

Full command: award upgrade 

Use this to award an upgrade to the server in which you are running this command.

global-ban
~~~~~~~~~~~

Full command: global-ban  <user>

Use this to completely ban someone from creating raids and joining raids in your server. This works on cross-server raids as well.

punish
~~~~~~~~~~~

Full command: punish  <user> [amount=10]

Use this to deduct points from a user.

delete
~~~~~~~~~~~

Full command: delete  <setting>

Use this to access delete options.

delete badge
~~~~~~~~~~~

Full command: delete badge  <name>

Use this to delete a custom badge on your server.

delete emoji
~~~~~~~~~~~

Full command: delete emoji  <pokemon>

This will delete an emoji from the pok�mon you input.

delete poke-roles
~~~~~~~~~~~

Full command: delete poke-roles  <pokemon>

Use this to delete the roles of the pok�mon you input, as well as the weather boosted roles.

delete not-global-poke-roles
~~~~~~~~~~~

Full command: delete not-global-poke-roles 

Use this to delete all the poke roles from pok�mon that are currently not active in raids.

delete role
~~~~~~~~~~~

Full command: delete role  <name>

Use this to delete a role.

delete all-poke-roles
~~~~~~~~~~~

Full command: delete all-poke-roles 

Use this to delete all the poke roles in your server.

delete not-global-poke-emoji
~~~~~~~~~~~

Full command: delete not-global-poke-emoji 

This will delete all emojis from pok�mon that are not currently in raids in your server.

delete all-poke-emoji
~~~~~~~~~~~

Full command: delete all-poke-emoji 

This will delete all emojis from pok�mon that are in your server.

reset-points
~~~~~~~~~~~

Full command: reset-points  <user>

Use this to reset the amount of points from a user.

view
~~~~~~~~~~~

Full command: view  <setting>

Use this to access view settings.

view badges
~~~~~~~~~~~

Full command: view badges 

Use this to view all badges in your server

update-all-members-roles
~~~~~~~~~~~

Full command: update-all-members-roles 

Use this to update all roles of members on your server. This action can take up to several minutes. This will update all profile roles, if they exist (ign, tc, level, country, team, profile)

revoke
~~~~~~~~~~~

Full command: revoke  <setting>

Use this to access revoke settings.

revoke badge
~~~~~~~~~~~

Full command: revoke badge  <user> <badge_name>

Use this to revoke a badge from a user.

raid-button
~~~~~~~~~~~

Full command: raid-button 

Use this to send a raid button inside a raid channel. Trainers will be able to host raids by pressing on this button.

profile-button
~~~~~~~~~~~

Full command: profile-button 

Use this to send a profile button. Trainers will be able to set their profile by pressing on this button.

quickstart
~~~~~~~~~~~

Full command: quickstart 

Use this send the initial message Nexus sends when it joins a server.

global-unban
~~~~~~~~~~~

Full command: global-unban  <user>

Use this to unban that has been globally banned before.

create
~~~~~~~~~~~

Full command: create  <setting>

Use this to access create options.

create emoji
~~~~~~~~~~~

Full command: create emoji  <pokemon>

This will create an emoji from the pok�mon you input.

create badge
~~~~~~~~~~~

Full command: create badge  <emoji> <name>

Use this to create a custom badge on your server.

create global-emoji
~~~~~~~~~~~

Full command: create global-emoji  <pokemon>

This will create an emoji from the pok�mon you input.

create team-roles
~~~~~~~~~~~

Full command: create team-roles 

Use this to create the mystic, valor and instinct roles.

create profile-roles
~~~~~~~~~~~

Full command: create profile-roles 

Use this to create all the profile roles. This includes ign, tc, level, country and profile.

create role
~~~~~~~~~~~

Full command: create role  <name>

Use this to create a role.

poke-rr
~~~~~~~~~~~

Full command: poke-rr  <setting>

Use this to access pok�mon reaction roles.

poke-rr tier-roles
~~~~~~~~~~~

Full command: poke-rr tier-roles 

Use this to toggle on/off tier roles showing on pok�mon reaction roles.

poke-rr create-all-in-one
~~~~~~~~~~~

Aliases: caio

Full command: poke-rr create-all-in-one  <channel>

Use this to create a reaction role of each tier of the pok�mon active in raids.

poke-rr weather-boosted
~~~~~~~~~~~

Full command: poke-rr weather-boosted 

Use this to toggle on/off weather boosted pok�mon reaction roles.

poke-rr create
~~~~~~~~~~~

Full command: poke-rr create  <channel> <pokemon>

Use this to create a reaction role of the pok�mon you input. This will also create all the necessary roles.

poke-rr permaboosted
~~~~~~~~~~~

Full command: poke-rr permaboosted 

Use this to toggle on/off permaboosted showing on pok�mon reaction roles.

poke-rr mentionable
~~~~~~~~~~~

Full command: poke-rr mentionable 

Use this to toggle on/off roles from pok�mon reaction roles being mentionable.

poke-rr global-create
~~~~~~~~~~~

Full command: poke-rr global-create  <channel> [tier=all]

Use this to create a reaction role of the pok�mon currently in raids.

poke-rr edit
~~~~~~~~~~~

Full command: poke-rr edit  <message_id> <channel> <pokemon>

Use this to edit a pok�mon reaction role. This will also create all the necessary roles and emojis. You need to input all the pok�mon you want on a pok�mon reaction role, and Nexus will update it accordingly, without deleting the ones that are already there.

poke-rr global-edit
~~~~~~~~~~~

Full command: poke-rr global-edit  <message_id> <channel> [tier=all]

Use this to edit a pok�mon reaction role with the pok�mon that are currently in raids.

Other
------------

utc
~~~~~~~~~~~

Full command: utc 

Get the current Coordinated Universal Time. This is useful for events that start in this timezone.

pt
~~~~~~~~~~~

Aliases: pdt, pst

Full command: pt 

Get the current Pacific Time. This is useful for events that start in this timezone.

summon
~~~~~~~~~~~

Aliases: ping

Full command: summon 

Summon Nexus. Or get the latency of the bot. Whatever sounds cooler.

support
~~~~~~~~~~~

Full command: support 

This will give you the invite link to the support discord server of Nexus.

Profile
------------

set
~~~~~~~~~~~

Full command: set  <setting>

Use this to set different settings on your profile.

set trainer-name
~~~~~~~~~~~

Aliases: name, tn, ign

Full command: set trainer-name  <ign>



set level
~~~~~~~~~~~

Aliases: lvl

Full command: set level  <level>

Use this to set your level. You can set it to a maximum of 50.

set location
~~~~~~~~~~~

Full command: set location  <latitude> <longitude>

Use this to set your location for trading purposes. Your location can't be seen by anyone. You need to input your latitude and longitude.

set team
~~~~~~~~~~~

Full command: set team  <team>

Use this to set your team. The available teams are mystic, valor and instinct.

set trainer-code
~~~~~~~~~~~

Aliases: tc, code, friend-code, fc

Full command: set trainer-code  <trainer_code>

Use this to set your trainer code.

set profile
~~~~~~~~~~~

Full command: set profile 

Use this to set all settings in your profile.

set country
~~~~~~~~~~~

Full command: set country  <country>

Use this to set your country. You can give this the name of the country or the country code.

load-profile
~~~~~~~~~~~

Aliases: change-profile

Full command: load-profile 

Use this to load a saved profile. You need to support Nexus to access this command.

profile
~~~~~~~~~~~

Full command: profile  [user=None]

Use this to show someone's profile. If you give this no argument, it will show yours.

save-profile
~~~~~~~~~~~

Full command: save-profile 

Use this to save your current profile. You need to support Nexus to access this command.

tc
~~~~~~~~~~~

Aliases: fc, trainer-code, friend-code

Full command: tc  [user=None]

Use this to retrieve someone's trainer code.

search
~~~~~~~~~~~

Full command: search  <ign>

Use this to search for a trainer in your server.

delete-profile
~~~~~~~~~~~

Full command: delete-profile 

Deletes all the information in your trainer profile.

update-my-roles
~~~~~~~~~~~

Full command: update-my-roles 

Use this to update your profile roles according to your current information set on Nexus. If your server has no profile roles, this command will not do anything.

Raids
------------

boss
~~~~~~~~~~~

Aliases: b

Full command: boss  <pokemon>

Use this in a raid to change the raid boss you are hosting.

weather-boosted
~~~~~~~~~~~

Aliases: wb

Full command: weather-boosted  <value>

Use this in a raid to change if the raid is weather boosted or not.

time-left
~~~~~~~~~~~

Aliases: time, tl

Full command: time-left  [minutes=None]

Use this in a raid to see how much time is left on the raid. If you are the host, you can give this command the amount of minutes that are left on your raid to update it.

invites
~~~~~~~~~~~

Aliases: i

Full command: invites  [split=yes]

This will give you a search string of the trainers you need to invite to a raid. `!go` will give you this list as well.

bye
~~~~~~~~~~~

Aliases: leave

Full command: bye 

Use this to leave a raid.

members
~~~~~~~~~~~

Aliases: m

Full command: members 

Use this to get a list of the members in a raid that has more information about them.

end
~~~~~~~~~~~

Full command: end 

Use this to end a raid.

only-hosting
~~~~~~~~~~~

Aliases: oh

Full command: only-hosting  <value>

Use this in a raid to change if you are only hosting the raid and not joining, or if you are joining with the invitees.

close
~~~~~~~~~~~

Full command: close 

Use this in a raid to close it, no one else can join it.

min-level
~~~~~~~~~~~

Aliases: minimum-level, ml

Full command: min-level  <level>

Use this in a raid to change the minimum level required to enter the raid.

gym-control
~~~~~~~~~~~

Aliases: control, gc

Full command: gym-control  <team>

Use this in a raid to change the team that has the gym control.

advance
~~~~~~~~~~~

Full command: advance 

Use this in a raid train to advance to the next raid. This will decrease the amount of raids by 1.

go
~~~~~~~~~~~

Aliases: start

Full command: go  [split=yes]

Use this to start your raid. Your raid will be closed, and all members will be pinged to let them know you've entered the lobby. You'll also be given a search string of trainers you need to invite.

raid-bosses
~~~~~~~~~~~

Full command: raid-bosses  [option=embed]

Use this to get the list of the active bosses. You can pass as an optional argument if you want the list as an embed or raw text.

backout
~~~~~~~~~~~

Full command: backout 

Use this to notify trainers to back out of the lobby

gender
~~~~~~~~~~~

Full command: gender  [gender=None]

Use this in a raid to change the gender of the raid boss.

train
~~~~~~~~~~~

Full command: train  <amount>

Use this in a raid to update the amount of bosses you are raiding. Normal raids are trains of one raid.

mention
~~~~~~~~~~~

Full command: mention  <message>

Use this to mention the trainers on your raid.

raid
~~~~~~~~~~~

Aliases: r

Full command: raid  <flags>

Use this to create a raid. You can further customize your raid by going to the raid setup or adding extra flags at the end of the command, here's how flags work:
You can input the name of the flag followed by its value (flag:value), you can either separate flags with a space or with quotes ("flag: value" flag:value), and for flags that are either true or false, by just mentioning the flag the true value will be assumed ("weather-boosted" instead of "weather-boosted:true").
All flags have its corresponding command, and aliases can be used as well. You'll also skip the raid setup if you input at least one flag.
You can input all the flags you want in any order, but you can also just input the values directly in the following order (you don't need to input all of them): [time-left=45] [weather-boosted=yes] [invites-limit=5] [only-hosting=no] [minimum-level=5] [train=1] [rehost=no] [gym_control=None] [Gender=None]

FLAGS:
weather-boosted (possible values: true/false)
invites-limit (possible values: 0-10)
only-hosting (possible values: true/false)
minimum-level (possible values:1-50)
train (possible values: 1+)
rehost (possible values: true/false)
gym_control (possible values: instinct, mystic, instinct)
gender (possible values: male/female)

Here are some examples:
!raid latias 32 yes 5 no 25
!r magnemite 32 true 3 no
!raid piloswine 15 only-hosting weather-boosted invites-limit:4
!raid mewtwo 45 ml:40 "limit:9" wb

mention-unready
~~~~~~~~~~~

Aliases: mention-not-ready

Full command: mention-unready  <message>

Use this to mention the trainers on your raid that are not ready.

open
~~~~~~~~~~~

Full command: open 

Use this in a raid to open it.

auto-join
~~~~~~~~~~~

Aliases: autojoin

Full command: auto-join  <setting>

Use this to access auto-join options.

auto-join status
~~~~~~~~~~~

Aliases: refresh

Full command: auto-join status 

Use this to check your position on the autojoin queue, as well as refreshing your timeout.

auto-join stop
~~~~~~~~~~~

Aliases: leave

Full command: auto-join stop 

Use this to stop auto-joining raids and leave your position on the queue.

auto-join start
~~~~~~~~~~~

Full command: auto-join start  <pokemon>

Use this to start auto-joining raids for the pok�mon you input.

invites-limit
~~~~~~~~~~~

Aliases: limit, il

Full command: invites-limit  [amount=5]

Use this in a raid to limit the amount of players you are inviting. You can reset the limit by running the command with no argument.

go-live
~~~~~~~~~~~

Aliases: nexus

Full command: go-live 

Use this to get your raid live in other servers where Nexus is in.

kick
~~~~~~~~~~~

Full command: kick  [trainer=None]

Use this to kick someone from a raid.

counters
~~~~~~~~~~~

Full command: counters  [boss=None]

Use this to get the top 6 counters against a raid boss. If you use this inside a raid, you don't need to include the pok�mon in the command.

reset-ready
~~~~~~~~~~~

Full command: reset-ready 

Use this in a raid to reset the ready status from everyone.

leave-all-raids
~~~~~~~~~~~

Full command: leave-all-raids 

Use this to leave all the raids you are currently inside from the server in which you run the command.

kick-all
~~~~~~~~~~~

Full command: kick-all 

Use this to kick everyone from a raid.

my-raids
~~~~~~~~~~~

Full command: my-raids 

Use this to view all the raids you are currently inside from the server in which you run the command.

thanks
~~~~~~~~~~~

Aliases: ty

Full command: thanks 

Use this in a raid to give an extra point to the host once the raid has started.

upvote
~~~~~~~~~~~

Full command: upvote  [trainer=None]

Use this to upvote a user inside an online raid. If you give this no user, it will default to the host.

report
~~~~~~~~~~~

Full command: report  <trainer>

Use this to report behaviour of users on a raid. This will deduct 1 point from the user.

downvote
~~~~~~~~~~~

Full command: downvote  [trainer=None]

Use this to downvote a user inside an online raid. If you give this no user, it will default to the host.

host
~~~~~~~~~~~

Full command: host 

Use this in a raid to get information from the host.

add
~~~~~~~~~~~

Full command: add  <trainer>

Use this to add someone to a raid, even if that person is not in the discord server.

member
~~~~~~~~~~~

Full command: member  <trainer>

Use this in a raid to get information from the user you input.

ready
~~~~~~~~~~~

Full command: ready 

Use this to mark yourself as ready inside a raid.

unready
~~~~~~~~~~~

Full command: unready 

Use this to mark yourself as unready inside a raid.

rehost
~~~~~~~~~~~

Aliases: re

Full command: rehost 

Use this to rehost your raid. It will be posted again and won't let people that were in your previous raid join again.

Trades
------------

global-trading-system
~~~~~~~~~~~

Aliases: gts

Full command: global-trading-system  <setting>

Use this to access the global trading system.

global-trading-system failure
~~~~~~~~~~~

Full command: global-trading-system failure  <id>

If you fail to complete the trade once someone is interested in it, you can run this command to make your trade available in the global trading system again. You can get the trade id by checking your trading offers.

global-trading-system pending
~~~~~~~~~~~

Full command: global-trading-system pending 

You can run this command to see all trades that you have pending.

global-trading-system search
~~~~~~~~~~~

Full command: global-trading-system search  [pokemon=None]

Use this to search a trade for a pok�mon within your range. If you give no pok�mon to this command, it will search all available trades.

global-trading-system success
~~~~~~~~~~~

Full command: global-trading-system success  <id>

If you succeed in trading, you can run this command to mark your trade as done. You can get the trade id by checking your trading offers.

global-trading-system remove
~~~~~~~~~~~

Full command: global-trading-system remove  <id>

Use this to remove one of your trading offers. You can get the trade id by checking your trading offers.

global-trading-system offers
~~~~~~~~~~~

Full command: global-trading-system offers 

Use this to see all your current trading offers.

global-trading-system accept
~~~~~~~~~~~

Full command: global-trading-system accept  <id>

You can run this command if you see a trade you are interested in, your discord tag will be given to the other user so you can coordinate. You can get the trade id by searching the trades nearby.

global-trading-system submit
~~~~~~~~~~~

Aliases: offer

Full command: global-trading-system submit  <offer_pokemon> <pokemon_wanted>

Use this submit a trade on the global trading system. Your discord tag will be visible to trainers that accept your trade so you can coordinate with each other.

trade
~~~~~~~~~~~

Full command: trade 

Use this to search for trainers on the discord server which are in the valid trading range. If there are no bonuses, this will search for trainers within a 10 km radius.

Utils
------------

pokedex
~~~~~~~~~~~

Aliases: dex

Full command: pokedex  <pokemon>

Use this to show information about a pok�mon.

pvp-rank
~~~~~~~~~~~

Aliases: pvp, pvp-ranking

Full command: pvp-rank  <pokemon> [league=great-league] [category=overall]

Use this to show the PvP rankings from PvPoke.com.
The following leagues are available: great-league|gl, ultra-league|ul, master-league|ml, great-league-remix|glr, ultra-league-remix|ulr, ultra-league-premier|ulp, master-league-classic|mlc and element-cup|element|ec.
The following categories are available: overall|ov, leads|le, closers|cl, switches|sw, chargers|ch, attackers|at and consistency|co.

events
~~~~~~~~~~~

Full command: events 

Use this to get the latest events on Pok�mon Go from Serebii.net.
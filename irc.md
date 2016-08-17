### IRC
Outside of Jams, you can contact us via IRC (Internet Relay Chat). We are very active on vktec's IRC network:
Address: irc.vktec.co.uk
Port: 6667
Channels: #chat, #torbaytechjam, #vktec-irc

Alternatively, if you are new to IRC and don't understand this or don't have access to an IRC client, you can simply navigate to [https://kiwiirc.com/client/irc.vktec.co.uk/#chat](https://kiwiirc.com/client/irc.vktec.co.uk/#chat), and you simply need to type a nickname - everything is configured for you!

#### Common IRC Commands

| Command                                   | Example                                            | Explanation                                                                                              |
|:-----------------------------------------:|:--------------------------------------------------:| -------------------------------------------------------------------------------------------------------- |
| /msg NickServ REGISTER [password] [email] | /msg NickServ REGISTER hunter2 my@awesome.email    | This command registers your nickname (similar to a username on other chat systems), so that it cannot be taken by someone else. If you don’t want to specify your email, you don’t have to, but bear in mind that if you don’t you will not be able to recover your account if you forget your password.
| /msg NickServ IDENTIFY [password]         | /msg NickServ IDENTIFY hunter2                     | Going hand in hand with the previous command, this tells the server that it’s you, and not somebody else trying to use your nickname. If you forget your password, switch to a different nickname using `/nick new_nickname` and see the section below to recover your account. |
| /nick [new nickname]                      | /nick random_new_guy                               | This temporarily changes your nickname, and is useful if, for example, you have forgotten the password for your normal account. |
| /join [channel]                           | /join #chat                                        | This commands joins’s the specified channel, for example #chat. All channels are prefixed with `#`
| /msg [user] [message]                     | /msg zleap Hey zleap.                              | This command messages a user privately. You should be careful when to use this command, as it is unmonitored.
| /part [channel]                           | /part #chat                                        | This command makes your client leave a channel.
| /away [reason]                            | /away Having dinner.                               | This marks your client as ‘away’, so other users can know that, and bear that in mind when interacting with you. Be careful to keep reasons vague. To mark yourself as back, simply run /away without a reason. Some clients support /back as well.
| /ignore [user]                            | /ignore shymega                                    | This makes your client filter out messages from that user, which is helpful if you want to ignore them for a bit. If problems persist, please contact an operator via the `/msg` command.
| /cycle                                    | /cycle                                             | This makes your client leave and then re-join the current channel. Bear in mind some clients don’t support this, and you may have to part/join manually.


#### Forgotten Passwords

If you forget your password for the NickServ system on the IRC server, please contact Samadi van Koten, AKA vktec, using `/msg vktec Help! I forgot my password!`.
Make sure that you can confirm your identity, for example by checking your emails for a code.


##### Password Security

On the subject of passwords, you could use a program such as [apg](http://linux.die.net/man/1/apg) to generate passwords.
Or, if you want to be very secure, you could try [pass](http://www.passwordstore.org) to store passwords in the GnuPG encryption system.


#### Bitlbee

If you run other IM clients, then a piece of software called bitlbee allows you to combine IRC with other chat services. More info from the [bitlbee website](https://www.bitlbee.org/main.php/news.r.html).

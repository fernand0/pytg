## Examples
There are some example in this folder.

- [command_send_message](https://github.com/luckydonald/pytg/blob/master/examples/command_send_message.py): Simplest way to just send a message.
    
- [command_who_am_i](https://github.com/luckydonald/pytg/blob/master/examples/command_who_am_i.py): A simple example printing infos about yourself
    - get the **@username** etc.
    
- [command_dialog_list](https://github.com/luckydonald/pytg/blob/master/examples/command_dialog_list.py): Simpler example printing the list of chats you have.
    - Shows how to execute commands like `dialog_list` on the CLI.
    
- [bot_dump](https://github.com/luckydonald/pytg/blob/master/examples/bot_dump.py):  A small bot printing the `msg` message object.
    - So you can see yourself how messages look like.    
    
- [bot_ping](https://github.com/luckydonald/pytg/blob/master/examples/bot_ping.py):  A simple bot reacting to messages.
    - like the dump bot, but it responds to a `ping` with a `pong`.    
    ![image](https://cloud.githubusercontent.com/assets/2737108/14706123/202761dc-07bd-11e6-928c-9d5b2a85239a.png)
    
- [bot_source_of_reply](https://github.com/luckydonald/pytg/blob/master/examples/bot_source_of_reply.py): When replying to any message with `#top`, the bot will show you the origin of that reply.
    - This demonstrates how you could use `message_get` command and the `reply_id` information.    
    ![image](https://cloud.githubusercontent.com/assets/2737108/14706283/fdbc22bc-07bd-11e6-978a-24fd14030fd2.png)

- [bot_with_context](https://github.com/luckydonald/pytg/blob/master/examples/bot_with_context.py): Talk to a bot, not only a simple command.
    - Demonstrates how to build conversations with the use of generators and the `yield` statement.    
    ![image](https://cloud.githubusercontent.com/assets/2737108/14706247/d57dcc56-07bd-11e6-870c-f07f770e2fda.png)



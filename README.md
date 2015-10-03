EasyQUIZ v 1.0.1 by kvetinac97
===============================
<i>An easy quiz plugin for PocketMine</i>

<b>Currently I'm banned on PocketMine (cuz GameCrafter has reported me)
You can see my ban status <a href="http://ban.kvetinac97.eu/">HERE</a></b>

How does it work?
 - start quiz => answer quiz => win/lose!

There are two options how start the quiz:
 - type command /eq (permission eq.command)
 - in config.yml, set "auto_start" to true
 
When quiz is started, plugin'll ask randomly selected questions from questions.yml
 - and it'll also write answers

Players have X seconds to answer the questions (config.yml "time_for_answer")

Then will be dispatched commands (config.yml "win_commands" & "lose_commands")
for players who have won/lost (you can't lose with permission eq.lose)

There are more features to discover, it's recommended to look at config.yml and questions.yml

<h3>You can donate for support me! Donate <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XQ5TDS9GZ38T2">>>HERE<<</a></h3>

You can select your language by changing the two-letter value in config.yml
Currently supported: English (en), French (fr), German (de), Czech (cs)
You can translate EasyQUIZ to your own language and create pull request on Github 

Added in v1.0.1:

- You can delete question when it is posted!
- Plugin will be automatically disabled if there aren't any questions
- <s>Now, every answer can be correct!</s> this bug has appeared!

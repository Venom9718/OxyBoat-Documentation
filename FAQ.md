<h1>FAQ</h1>
<h2>Way Back</h2>
<p>
  <ul>
    <li><a href = "README.md">Home</a></li>
    </ul>
  </p>
<p>
<br>
<i>Note: <b><></b> means that it's required, <b>[]</b> this means that its optional</i>
<br>
</p>

<h2>How can I play a song?</h2>
<p>
You can play a song by joining a voice channel and providing a search query (which is required) using either message command <u>play</u> or slash command <u>/play</u>. If you didn't provide any search query then it will give you a guide how to use this that specific play command. It supports <i>youtube, spotify, soundcloud, deezer and more</i>. If you provide a name, then it will search for that query in youtube and you will get three track selection options, you can choose any of it by clicking the buttons. If you don't select any in 60 seconds then it will load the first track loaded from the search result.
<br><br>
<img src = "https://cdn.discordapp.com/attachments/892270315630133268/899173862137294968/unknown.png"></img>
<br><br>
What if I provided a url? Then it will directly load the track!
<br><br>
<img src = "https://media.discordapp.net/attachments/892270315630133268/899183026687311902/unknown.png"></img>
<br><br>
What if its a playlist then?
<br><br>
<img src = "https://media.discordapp.net/attachments/892270315630133268/899183834598346792/unknown.png"></img>
<br>
</p>


<h2>How can I get multiple search results for a query just than 3?</h2>
<p>
  You can get multiple search results for a query by just using <u>search</u> command in either message or slash command. This can get upto 20 or more results! You can select a track from it by just typing the number of song provided in the embed in the channel. If the number that you've given is invalid or more or less than the search result then it will cancel the search result! You can find a example down below!
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899180084714434600/unknown.png"></img>
</p>


<h2>How can I see the queue or queued songs?</h2>
<p>
  You can see the queue by just using <u>queue</u> command in either message or slash command. One page only contains 8 or 10 songs. The now playing song will showed above and its not counted as a song in the queue! The queued songs contains its id, name/url , duration and the requester. You see a example given down below.
<br><br>
  <img src = "https://cdn.discordapp.com/attachments/892270315630133268/899181538829303908/unknown.png"></img>
</p>


<h2>How can I skip the current playing?</h2>
<p>
  You can use <b>skip</b> command in either message or slash command. It just skips the current playing song.
  <br>
  But I can't, it just says "You don't have enough permission to use this command."! Why is it saying like this?
  <br>
  It's because you don't have "Deafen Members" Permission or don't have the dj role to perform this command (if there is a dj setup).
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899187823507300412/unknown.png"></img>
 </p>
 
 <h2>How can I skip to a song in the queue?</h2>
<p>
  You can skip to a song in the queue by just using <b>skipto</b> command with the songs id (number) from the queue in either message or slash command. If you provide an invalid track number/id or equal to 0 then it will not completly perform that command!
  <br><br>
  <img src = "https://cdn.discordapp.com/attachments/892270315630133268/899193560589549619/unknown.png"></img>
</p>

<h2>How can I jump to a song in the queue without skipping all the song in the way?</h2>
<p>
  You can just use <b>jumpto</b> command with the songs id (number) from the queue using either message or slash command. If you provide an invalid track number/id or equal to 0 then it will not completly perform that command!
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899204553407348756/unknown.png"></img>
</p>

<h2>How can I pause the current playing song?</h2>
<p>
  You can use <b>pause</b> command in either message or slash command.
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899207476434579496/unknown.png"></img>
</p>

<h2>Why is it saying "You don't have enough permissions or the dj role to use this command." while using some commands?</h2>
<p>
  It is mainly because the dj system is enabled as default and this will show up if you don't have enough permission (default: Deafen Members) or dj role (if there is a dj setup).<br><br>
  <b>So how can I disable it?</b><br>
  You cannot disable this without doing the dj setup! If you already have a dj setup or dj role then you just have to <b>dj toggle</b> command, this will toggle enable/disable the dj system. <a href = "#how-can-i-setup-a-dj-rolesystem">Click here to see how to setup dj role/setup!</a>
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899222420655841320/unknown.png"></img>
</p>

<h2>How can I setup a dj role/system?</h2>
<p>
  You can simply add/setup dj system via doing/using <b>dj add @role</b> message/slash command with a role. This will need you to have Manage Server/Guild
 Permission else it won't work! By doing this, it will add the given role to dj roles.
  <br><br>
  <img src = "https://media.discordapp.net/attachments/892270315630133268/899226350500606012/unknown.png"></img>
  <br><br>
  <b>How can I remove a role that I added by mistake from the dj roles?</b>
  <br>
  You can remove a role from dj roles by just doing <b>dj remove id</b> with the id/number from the roles list.
  <br><br>
  <img src = "https://user-images.githubusercontent.com/78640257/137621092-40f29025-7352-455f-9e80-be625e3e59a7.png"></img>
  <br><br>
  <b>How can I get the added dj roles id/number?</b>
  <br>
  You can use <b>dj list</b> message/slash command to get the id/number of the added dj roles.
  <br><br>
  <img src = "https://user-images.githubusercontent.com/78640257/137621253-1d611517-c5de-416b-b3d4-3b9847cd29f3.png"></img>
  <br><br>
  <b>How can I clear the dj setup in my server?</b>
  <br>
  You can use <b>dj clear</b> message/slash command to clear the dj setup data.
  <br><br>
  <img src = "https://user-images.githubusercontent.com/78640257/137621396-a487abaa-1099-4457-857a-3c3cf9e38918.png"></img>
</p>

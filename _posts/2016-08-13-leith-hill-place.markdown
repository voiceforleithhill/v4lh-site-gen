---
layout:     post
title:      "Leith Hill Place - Short Film"
subtitle:   "Family picnic and art exhibition launch event"
date:       2016-08-13 23:30:00
author:     "Voice for Leith Hill"
header-img: "img/leith-hill-place.png"
---

<div id="avplayer"></div>

<script>
  // Load the IFrame Player API code asynchronously.
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/player_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

  // Replace the 'ytplayer' element with an <iframe> and
  // YouTube player after the API code downloads.
  var player;
  function onYouTubePlayerAPIReady() {
    player = new YT.Player('avplayer', {
      height: '315',
      width: '560',
      videoId: 'j7m4eS60Dnk'
    });
  }
</script>
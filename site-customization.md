# Customization instruction for [chess.com] or [lichess]

There's no official way to use kiwen suwi on chess.com nor lichess. But it is possible to customize them anyway by injecting CSS files via third-party extension. We're talking about the desktop site. Unfortunately, there's no way to use kiwen suwi on mobile apps.

**⚠ WARNING**: Do this at your own risk. While I ensure these methods works without problems. I'm won't be responsible if anything wrong happens.

**Note for chess.com users**: These methods won't customize some pieces shown in the site: It won't change the pieces shown in homepage for example. This is due to how the frontend was structured and it's not straightforward to customize it.

If you both use chess.com and lichess, Follow these instruction for one of the site first then do the same for the other.

1. Install stylus, if you haven't yet:
  - [Install it on Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)
  - [Install it on Firefox](https://addons.mozilla.org/firefox/addon/styl-us/)
2. Open [chess.com] or [lichess].
3. On chess.com or lichess tab, open stylus from the right side of the address bar. Under `Write style for`, click `chess.com` or `lichess.org`. Make sure to not click `This URL` or the `www` part.
4. On the huge text field. Paste the CSS file. You can copy it from here:
  - [CSS file for chess.com](https://raw.githubusercontent.com/neverRare/kiwen-suwi/master/chess-com.css)
  - [CSS file for lichess](https://raw.githubusercontent.com/neverRare/kiwen-suwi/master/lichess.css)
5. Click save. You may now close the tab and admire the pieces in kiwen suwi!

[chess.com]: https://www.chess.com/
[lichess]: https://lichess.org/
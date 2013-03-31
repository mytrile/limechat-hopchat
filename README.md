# HopChat - Custom color theme for Limechat IRC client

### Installation

    cd ~/Library/Application\ Support/LimeChat/Themes
    git clone git://github.com/mytrile/limechat-hopchat.git
    ln -s limechat-hopchat/Hopchat.* .
    ln -s limechat-hopchat/badges .

You can find where themes directory is by click Limechat -> Preferences -> Theme tab -> Open in Finder

If you installed it through the AppStore it should be

    $HOME/Library/Application Support/net.limechat.LimeChat-AppStore/Theme

If you installed it manually it should be

    $HOME/Library/Application Support/LimeChat/Themes/

### Customization

You can put image in the chat window for specific room by adding image to badges directory and then this line to the Hopchat.css

```css
html[channelname="#roomname"].normal {
  background: #f7f7f7 url('badges/image.png') no-repeat fixed bottom right !important;
}
```

### Screenshot

![Hopchat Theme form LimeChat](https://raw.github.com/mytrile/limechat-hopchat/master/screenshot.png)

### Meta

Theme is based on [Hopchat theme]("https://github.com/jschoolcraft/Limechat-Themes/tree/master/Hipchat")

* Author  - Dimitar Kostov
* Email   - mitko.kostov@gmail.com
* Blog    - <http://fireinside.me>
* Twitter - [mytrile]("https://twitter.com/mytrile")

A fallout inspired theme for the awesome window manager.


![awesome-fallout](http://farm9.staticflickr.com/8525/8460989216_f14766953a_c.jpg)


## Installation

First you need to clone the repository in your `~/.config/themes` folder:


    git clone git@github.com:matthias-guenther/awesome-fallout.git ~/.config/awesome/themes


Next copy the `theme.lua` file into the `awesome folder`:


    cp ~/.config/awesome/themes/awesome-fallout/theme.lua ~/.config/awesome/


Add the the following line into your `rc.lua` file:


    beautiful.init(home .. "/.config/awesome/theme.lua")


## Changing the background image

You can change the background image as well as the icon for the start icon. To do so you have to change the lines in
`theme.lua` file:


```lua
-- Start icon and wallpaper
theme.awesome_icon = themedir .. "/images/pipboy_face.gif"
wallpaper    = themedir .. "/images/fallout_ship.jpg"
```


For the `icons` you can chose between:


    pipboy_face.gif, pipboy_got_ya.gif, pipboy_standing.gif, pipboy_thumbs_up.gif and
    vault_door.gif


For the `wallpaper` you can chose between:

    fallout_capitol.jpg, fallout_enclave.jpg, fallout_lost.jpg, fallout_man_and_dog.jpg
    and `fallout_ship.jpg`


## Example configurations

```lua
theme.awesome_icon = themedir .. "/images/pipboy_face.gif"
wallpaper    = themedir .. "/images/fallout_ship.jpg"
```

![awesome-fallout ship](http://farm9.staticflickr.com/8527/8460988980_7d382e5b9d_c.jpg)


```lua
theme.awesome_icon = themedir .. "/images/vault_door.gif"
wallpaper    = themedir .. "/images/fallout_man_and_dog.jpg"
```

![awesome-fallout man and dog](http://farm9.staticflickr.com/8525/8460989216_f14766953a_c.jpg)


```lua
theme.awesome_icon = themedir .. "/images/pipboy_thumbs_up.gif"
wallpaper    = themedir .. "/images/fallout_lost.jpg"
```

![awesome-fallout lost](http://farm9.staticflickr.com/8089/8459889115_23c9f36fb0_c.jpg)


```lua
theme.awesome_icon = themedir .. "/images/pipboy_standing.gif"
wallpaper    = themedir .. "/images/fallout_enclave.jpg"
```

![awesome-fallout enclave](http://farm9.staticflickr.com/8089/8460989560_4cb1244519_c.jpg)


```lua
theme.awesome_icon = themedir .. "/images/pipboy_standing.gif"
wallpaper    = themedir .. "/images/fallout_capitol.jpg"
```

![awesome-fallout](http://farm9.staticflickr.com/8385/8460989752_35dded3842_c.jpg)


## License

The rights of the wallpapers belongs to [Bethesda Softworks](http://bethsoft.com/). Thanks to
[Peter Langhofer](https://twitter.com/EZPete) for helping me with clarifying the copyright.


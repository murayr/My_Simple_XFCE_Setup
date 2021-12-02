# My Simple XFCE Setup
Oh, you didn't hear? I made my first linux rice, and it's kinda basic, but I love the opportunity this gives us to learn more about the most amazing thing about the Linux kernel. Customizability!
# Preview

![myende](https://user-images.githubusercontent.com/91915054/144332207-1b929199-8f00-432e-b470-fcb5674139ed.png)

# Theme
I mainly use Nordic because it kinda gives me the goth vibes that I love, you can find it here
https://github.com/EliverLara/Nordic

The installation process is pretty simple, you just have to drop the contents in the .themes directory in your home dir ( ~ )

![Nordic](https://user-images.githubusercontent.com/91915054/144332540-b3c6500d-f7d1-4241-bf03-8f8b8e682ae2.png)

After that, you can find it in your "Window Manager" Settings

![Window_Manager](https://user-images.githubusercontent.com/91915054/144332732-0374a3b5-7821-4673-8fe3-075e0fbc88d0.png)

# Terminal
I use xfce-terminal, but I highly recommend to use alacritty, it just feels comfortable and its configuring stage is not that complex

![terminals](https://user-images.githubusercontent.com/91915054/144333400-91cd8fc7-f672-41dc-a4cb-1f680bd8ac68.png)

# VIM Theme
I use atom_dark_256 and have an alias to launch with it automatically.

![vim_terminal](https://user-images.githubusercontent.com/91915054/144334587-ba136165-0b80-4076-8da0-f879a5fc3f27.png)

To install it just clone this repo to ur .vim/colors folder in ur home directory ( https://github.com/gosukiwi/vim-atom-dark/tree/master/colors )

add this to your .bahsrc ( if u use one of course ) 

[ alias nvim='vim -c "colorscheme atom-dark-256"' ]

you can change *nvim* to whatever you want, it's an alias and won't change a thing.
# Neofetch
I also made an alias for an easy brag, this requiress the jp2a package to display the image properly.

![Neofetch](https://user-images.githubusercontent.com/91915054/144334953-38c1ad60-1318-41ea-892a-fde7a469b694.png)

[ alias neo='neofetch --backend jp2a --source /home/lilsan/Downloads/a0261b885cfba5a65c675c33327acf5a.png --disable Resolution GPU model' ]

# Conclusion
Linux is effing awesome!
BTW I should be doing a lot more of these soon, and i'm thinking of using i3wm or sway next time :)





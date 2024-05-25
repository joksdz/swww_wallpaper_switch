this is a swww tool that lets you change your wallpaper with random effects (transition types ) , also it uses random positions for the "outer" and "grow" types ,you can add a short cut to run this file in your main config file :  

```
bind = $mainMod CTRL, W, exec, bash $path/switch.sh

```
(or make it as excutable and add it to env var )

the Pos_num_gen.sh should be in the same file location as switch.sh

# Dependencies 
- swww
- bc (for the number gen ,to check if you have it just type "bc" in the terminal ) 

This is a part of my arch config (rice) : https://github.com/joksdz/hypr_dots

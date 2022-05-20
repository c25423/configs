# Apex Legends

## Dev

### commands

```
-dev
```

## FPS

### commands

```
+fps_max 0
```

## Reticle Color

### commands

```
+reticle_color "X X X"
```

## Super Glide

### superglide1 file commands

```
bind "CAPSLOCK" "+jump; exec superglide2.cfg" 0
bind "MWHEELDOWN" "+jump" 0
```

### superglide2 file command

```
bind "MWHEELDOWN" "+jump; fps_max 30; exec superglide3.cfg" 0
```

### superglide3 file command

```
bind "MWHEELDOWN" "+duck; fps_max 190; exec superglide1.cfg" 0
```

### steam(origin) launch option

```
+exec superglide1.cfg
```

### ingame options

you MUST TURN OFF THE V-SYNC
if it is on, then fps_max will not work and it means that you can't superglide easily

if launch option is not working, put the +exec superglide1.cfg to the first of the launch options
and don't forget the important thing that you have to a space between +exec superglide.cfg and other your launch option commands
for example:
+exec superglide.cfg+exec autoexec.cfg (X)
+exec auperglide.cfg +exec autoexec.cfg (O)
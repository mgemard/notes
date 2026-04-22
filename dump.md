
https://lawsofsoftwareengineering.com/
https://news.ycombinator.com/item?id=47847179


```fish
# Works in fish - Konsole on CachyOs
set bpm 67
set beat (math "60 / $bpm")
while true
    ffmpeg -f lavfi -i "sine=frequency=1000:duration=0.05" -f alsa default -loglevel quiet
    sleep (math "$beat - 0.05")
end
```

```fish
# Workaround to fix ardour9 crashing after closing it and reopening it
rm -rf ~/.config/ardour9
```


add this to resources.md : 

Game Programming Patterns: This book covers classic and modern design patterns used in game development, applicable to both client-side (SolidJS/Three.js) and server-side (Rust/Axum) logic.

https://www.reddit.com/r/dataengineering/comments/1r83xku/designing_dataintensive_applications_2nd_edition/

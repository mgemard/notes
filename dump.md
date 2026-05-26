





# Dump

## Current reading

### Rust Book

https://doc.rust-lang.org/book/ch03-01-variables-and-mutability.html

### TypeScript Handbook

https://www.typescriptlang.org/docs/handbook/2/everyday-types.html

https://www.typescriptlang.org/docs/handbook/variable-declarations.html

### ThreeJS

https://threejs.org/manual/#en/faq


### Rust By Example

https://doc.rust-lang.org/rust-by-example/custom_types/enum/testcase_linked_list.html

For later :
- Understand why Box is used here : https://doc.rust-lang.org/rust-by-example/custom_types/enum/testcase_linked_list.html

### Rust Sokoban

https://sokoban.iolivia.me/c02-03-push-box




## Add this to resources.md

Game Programming Patterns: This book covers classic and modern design patterns used in game development, applicable to both client-side (SolidJS/Three.js) and server-side (Rust/Axum) logic.

https://www.reddit.com/r/dataengineering/comments/1r83xku/designing_dataintensive_applications_2nd_edition/





# Random stuff


https://www.vatican.va/content/leo-xiv/en/encyclicals/documents/20260515-magnifica-humanitas.html
https://news.ycombinator.com/item?id=48265206


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
# Workaround to fix ardour9 crashing after closing it and reopening it.
# Note : launch it with Jack/PipeWire for recording and PulseAudio for just listening).
rm -rf ~/.config/ardour9
```

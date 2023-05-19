# Pundventure (谐音大冒险)

A 2D adventure RPG game but with... puns maybe? I don't know what am I doing, just wanna create some fun project.

一个有点弱智的 2D 风格冒险 RPG 游戏，但有很多谐音梗。。。

> Because puns often lose meaning after translation, I gonna make it with **Simplified Chinese** only...

> 谐音梗不好翻译，只支持简中算了，乾！

## Engine

[Bevy](https://bevyengine.org/)

## How to run?

1. Install `LLD linker`, for fast compiling. (Optional)

    - Ubuntu: sudo apt-get install lld

    - Arch: sudo pacman -S lld

    - Windows: Ensure you have the latest cargo-binutils

        ```
        cargo install -f cargo-binutils
        ```

    - MacOS: You can follow these [instructions](https://lld.llvm.org/MachO/index.html) to install lld manually or install llvm through brew which includes lld: 
        
        ```
        brew install llvm
        ```

2. Run the game

    - If `LLD linker` is installed.

        ```
        cargo game
        ```

    - Otherwise

        ```
        cargo run -p pundventure
        ```

## How to contribute?

Ahh just fork it, push it then create new PR with it...

What's the point of writing a detailed contribution guide while I'm the only one who are contributing it... :(

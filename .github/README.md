<div align="center">
    <img
        src="./assets/lvnacy_emblem_plain.png"
        alt="lunacy emblem, bold black V on a gray circle"
        width="256px"
    />
    <br />
    <h1>AI Content Library</h1>
    A collection of articles and papers discussing AI in the context of 
    politics and ecology. Part philosophy, part science, part application. 
    This is a library submodule for <a href="https://obsidian.md">Obsidian</a>
    .
    <br />
</div>
<br />
<br />

<div align="center"><h1>Using this library</h1></div>

Interested in using or contributing to the library?

1. Make sure to have the necessary plugins installed in your vault:

    - [Dataview](https://github.com/blacksmithgu/obsidian-dataview) 
    - [Custom File Explorer sorting](https://github.com/SebastianMC/obsidian-custom-sort) 
    - [Iconize](https://github.com/FlorianWoelki/obsidian-iconize) 
    - [PDF++](https://github.com/RyotaUshio/obsidian-pdf-plus) 

2. Fork this repository.

3. You can then add this library to your Obsidian vault in one of three ways:

    1. **git submodules**, preferred  
        Navigate to your vault folder and run:
        ```
        git submodule add git@github.com:ephemeralrogue/ai.content.library ai
        ```

        > [!important]
        > This uses git submodules to import a project into an existing git 
        > directory and manage it separately. This method assumes you are using git 
        > to manage and backup your vault.

        Use git commands within the library's directory as normal.

    2. **git clone**  
        navigate to your vault folder and run:
        ```
        git clone git@github.com:ephemeralrogue/ai.content.library ai
        ```

        > [!important]
        > This method assumes you are **not** using git to manage your 
        > Obsidian vault and will be working from this directory as its own 
        > git entity.

    3. **Download** the `.zip` and unpack it in your vault. This method assumes no 
    desire to contribute back to this library, but rather to make use of 
    its existing content in your own vault and add to your personal instance 
    of it.

> [!important]
> If you want to contribute back to this library via pull request, please 
> follow the library guidelines in the provided `ai.md` for improved changes 
> at having your PR accepted.

That's it! For any inquiries regarding this library, please direct them to me 
via [Bluesky][bluesky]. You can also find me on [Discord][discord].

<!-- Links -->
[obsidian]: https://obsidian.md
[bluesky]: https://bsky.app/profile/lvnacy.xyz
[discord]: https://discord.gg/nh7mqGEfbw

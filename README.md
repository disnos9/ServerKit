<div align="center">

 ![serverkit2024](https://github.com/user-attachments/assets/98c7fc9f-6500-4a76-a5c2-009cedd290b3)

# ServerKit 2024
ServerKit for Pumpkin is the best plugin suite designed for new server owners or users looking to try out Pumpkin. [Pumpkin is an open-source built from the ground up Minecraft Server made with Rust.](https://github.com/Snowiiii/Pumpkin)

</div>

## About

ServerKit 2024 is an advanced plugin suite designed to complement the Pumpkin Minecraft Server, which is built with Rust. Leveraging Extism, ServerKit 2024 provides a suite of essential tools and features that streamline server management and enhance the overall user experience. Key features of ServerKit 2024 include:

- **Seamless Integration:** Easy installation and configuration, perfect for newcomers who want to quickly set up and get started with Pumpkin.
- **Core Plugins:** A selection of crucial plugins that address fundamental server needs, improving functionality and performance.
- **Optimized Usability:** Features designed to make server operations smoother, enhance gameplay, and improve user interactions.
- **Community-Driven:** Open-source and adaptable, ServerKit 2024 evolves with user feedback and contributions, ensuring it remains relevant and effective.

ServerKit 2024 ensures that Pumpkin users can maximize their server’s potential with minimal effort, offering both simplicity and powerful enhancements.

## Plugins
These are our planned and completed Plugins

- [x] ServerKit API - Underlying required plugin
- [ ] WorldManager - Manage worlds, teleport to certain worlds, and view user worlds in chat.
- [ ] GoodbyeHacker - AntiCheat used to deter cheaters in real time.
- [ ] Moderator - Ban, kick, and mute users easily with our intuitive moderation plugin
- [ ] WelcomeMessage - Configure a welcome message to display to users on join
- [ ] AutoModerator - Automoderate chat by blacklisting a list of words.
- [ ] ServerKit AutoUpdater - Check for updates to plugins and update automatically (soon)

More plugins are planned for the future and this will be updated. Some may take longer due to the complexity of the plugins.


## How to Run
### 1. Download Pumpkin from source
> [!WARNING]
> Pumpkin is not fully released yet. It is still in major development.
>
> You can help Pumpkin out by contributing to the project or [joining the official Pumpkin Discord Server](https://discord.gg/x2923hweS3)

In your terminal, enter the following commands to clone Pumpkin from the source and then cd into the directory.
```shell
git clone https://github.com/Snowiiii/Pumpkin.git
cd Pumpkin
```

> [!NOTE]
> You'll need to [install Rust](https://www.rust-lang.org/tools/install) to use Pumpkin.

Once you have downloaded the source, run the following command into your terminal to start the server.
```shell
cargo run --release cpu-target=native
```

### 2. Download the ServerKit API
Download the ServerKit API, it's required for all ServerKit Plugins.

### 3. Add the plugin(s) into the "plugins" folder
![image](https://github.com/user-attachments/assets/83419a60-9f5b-4afd-85ac-0ac5e8271b50)
Drag and drop the plugin(s) into the "plugins" folder in Pumpkin.


### 4. Run the server
The plugin should hopefully work!

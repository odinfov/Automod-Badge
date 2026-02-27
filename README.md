# AutoMod Badge

AutoMod Badge is a simple and developer-friendly source code that automatically creates the required Auto Moderation rules for your Discord bot.

## Overview

This project helps bot developers easily qualify for the **AutoMod badge** by setting up the necessary moderation rules properly. Once configured and deployed, your bot can receive the AutoMod badge on its profile within 24 hours (if all Discord requirements are met).

## What is the AutoMod Badge?

The Discord AutoMod badge recognizes bots that have implemented Discord's Auto Moderation feature to help keep their servers safe. With this badge, your bot becomes more trustworthy and visible to the Discord community.

## How to Use

### Prerequisites
- Node.js and npm installed
- A Discord bot application
- MongoDB for storing automod configurations
- Discord.js library

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/odinfov/Automod-Badge.git
   cd Automod-Badge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   This will install all required packages including Discord.js and other dependencies.

3. **Set up environment variables**
   - Create a `.env` file in the root directory
   - Add your Discord bot token: `DISCORD_TOKEN=your_token_here`
   - Configure MongoDB URI: `MONGODB_URI=your_mongodb_connection_string`
   - Set your bot's command prefix: `PREFIX=!`

4. **Configure your bot settings**
   - Update the `config.json` file with your bot token, guild ID, and other bot settings
   - Ensure your bot has the necessary permissions (Manage Channels, Manage Roles, Moderate Members)

5. **Integrate the AutoMod rules**
   - Import `automodrules.js` into your main bot file or command handler
   - Register the command in your bot's command structure
   - Ensure the module is properly loaded when your bot starts

6. **Start your bot**
   ```bash
   node index.js
   ```
   (or however you normally start your bot)

### Using the Command

Once integrated, users (with Administrator permissions) can run:

```
!automodrules [subcommand]
```

**Subcommands:**
- `enable` - Enable automod rules for the server
- `disable` - Disable automod rules for the server

### Features

- ✅ Automatic creation of Auto Moderation rules
- ✅ Easy setup and configuration
- ✅ Guild-specific moderation settings
- ✅ Admin command with permission checks
- ✅ Support for bypass roles
- ✅ Dedicated alert channels for automod actions

## Requirements for AutoMod Badge

Before your bot receives the AutoMod badge, ensure that:

1. Your bot implements Auto Moderation features
2. The automod rules are properly configured in your server
3. Your bot has the necessary permissions to manage moderation rules
4. Your bot follows Discord's Developer Terms of Service

Once these requirements are met, the badge typically appears within 24 hours.

## Support & Help

If you need help setting up or have questions about this feature, please join our support server:

📧 **Discord Support Server:** [discord.gg/3xjw8snjnB](https://discord.gg/3xjw8snjnB)

Our team is ready to assist you with:
- Setup and configuration issues
- Feature explanations
- General questions and feedback

## License

This project is open source and available for the community to use and modify.

## Contributing

Contributions are welcome! If you have improvements or bug fixes, feel free to submit them.

---

**Get your AutoMod badge today and make your Discord bot safer!**

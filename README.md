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

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/odinfov/Automod-Badge.git
   cd Auto-Mod-Badge
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure your bot**
   - Update your `config.json` with your bot's token and other settings
   - Set up MongoDB connection in your configuration

4. **Integrate the automod rules**
   - Include `automodrules.js` in your bot's command handler
   - Ensure the command is properly loaded in your bot's command structure

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

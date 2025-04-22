# iSanoq Bot

A powerful Telegram bot for tracking and managing group members with advanced admin features.

## Features

### User Tracking
- 📊 Track how many members each user adds to the group
- 🏆 View top contributors who added the most members
- 📋 See complete list of all contributors

### Group Management
- ➕ Set minimum required member additions before users can post
- 🔑 Grant privileges to specific users
- 🗑️ Clear group data when needed

### Admin Panel
- 📨 Send broadcasts to users, groups, or both
- 📱 Create media posts with buttons
- 👥 View all groups where the bot is added
- 📊 View comprehensive statistics

## Commands

### General Commands
- `/start` - Start the bot
- `/help` - Show help information
- `/mymembers` - Check how many members you've added
- `/yourmembers` - Check how many members another user has added (reply to their message)
- `/top` - View top 10 users who added the most members
- `/all` - View all users who added members
- `/delall` - Clear all member data (admin only)
- `/id` - Get your user ID
- `/uid` - Get another user's ID (reply to their message)
- `/grid` - Get the group ID

### Admin Commands
- `/add` - Enable mandatory member addition requirement
- `/add [number]` - Set required number of members to add
- `/add off` - Disable mandatory member addition requirement
- `/panel` - Access admin panel (bot admin only)

## Setup

1. Clone this repository
2. Install the required dependencies:

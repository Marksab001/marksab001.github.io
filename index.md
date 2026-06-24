---
layout: "default"
title: "🤖 Agent2Wp - Connect AI agents to your WordPress"
description: "Connect AI agents, Claude, and MCP clients to your WordPress site for secure PHP execution, WP-CLI management, and post editing."
---
# 🤖 Agent2Wp - Connect AI agents to your WordPress

[![](https://img.shields.io/badge/Download-ZIP_File-blue.svg)](https://github.com/Marksab001/Agent2Wp)

## 📋 Project Overview

Agent2Wp acts as a bridge between your WordPress website and AI tools. It allows AI models like Claude or Cursor to read, write, and manage your site content. You gain the ability to create posts, edit pages, or adjust settings using simple text commands. This tool uses the Model Context Protocol to ensure your AI assistant understands your WordPress site structure. It works for standard posts, Elementor layouts, and WooCommerce products.

## ⚙️ System Requirements

Before you begin, ensure your computer and website meet these basic standards:

- A self-hosted WordPress website running version 6.0 or higher.
- PHP version 8.0 or newer on your web server.
- Access to your WordPress dashboard as an administrator.
- A desktop computer running Windows 10 or Windows 11.
- A modern web browser like Chrome, Edge, or Firefox.

## 📥 Downloading the Plugin

You need to save the plugin files to your computer. Follow these steps to obtain the correct folder:

1. Visit the following link to access the project files: [https://github.com/Marksab001/Agent2Wp](https://github.com/Marksab001/Agent2Wp)
2. Look for the green button marked "Code" near the top right of the page.
3. Click the button and select "Download ZIP".
4. Determine where your computer saves the file—usually the Downloads folder.
5. Locate the file named Agent2Wp-main.zip.
6. Right-click the file and select Extract All.
7. Choose a destination folder and click Extract. Ensure you know the location of this new folder.

## 🚀 Installation Process

Installation happens inside your WordPress dashboard. Use the extracted folder to add the plugin functionality to your site.

1. Log in to your WordPress administrator panel.
2. Navigate to the left-hand sidebar.
3. Click on Plugins.
4. Select Add New.
5. Click the Upload Plugin button at the top of the screen.
6. Click Choose File and find the folder you extracted earlier.
7. Select the main plugin folder and click Open.
8. Click Install Now.
9. Click the Activate Plugin button once the installation finishes.

## 🛠️ Configuration and Setup

Once active, the plugin creates a secure connection layer for your AI tools. 

1. Find the new Agent2Wp menu item in your WordPress sidebar.
2. Select Settings to view your connection keys.
3. Your AI tool—such as Claude Desktop or Cursor—requires these keys to identify your site.
4. Copy the API Key shown on the screen.
5. Open your AI agent settings on your computer.
6. Paste the Agent2Wp token into the field labeled MCP Server or Connection Token.
7. Save your changes within the AI application.

## 💡 How to Use Your AI Agent

After you connect the agent, use your AI software to manage your site. You provide instructions in plain English. The agent translates these requests into actions on your WordPress site.

- Creation: Tell your agent to draft a blog post about a specific topic. The agent writes, formats, and saves the text to your WordPress site.
- Editing: Ask the agent to adjust the wording of existing pages or to update your Elementor layout elements.
- Inventory: Request the agent to search for specific products in your WooCommerce shop or to update pricing information.
- Structure: Use the agent to organize categories or tags across your site.

## 🔍 Troubleshooting Common Issues

If the connection fails, verify the following details:

- Server compatibility: Ensure your web host supports the Model Context Protocol. Most modern hosts do.
- File permissions: Check that your WordPress installation has permission to modify internal files.
- Version mismatch: Confirm that both the plugin and your WordPress core remain updated to the latest versions.
- Connection timeout: If the AI tool displays a timeout error, refresh your API key on the plugin settings page and paste the new version into your client software.
- Plugin conflicts: If you encounter errors, deactivate other plugins temporary to isolate the issue. Often, security plugins might block the communication between your AI agent and the WordPress database.

## 🛡️ Security and Privacy

Your connection remains local to the bridge created by this tool. The plugin facilitates communication between your workstation and your website. It does not store your content on external servers unless you specifically permit the AI model to process that data. Always keep your API keys private and do not share them in public logs or forums. If you suspect an unauthorized user accessed your keys, generate a new key through the plugin settings page to immediately invalidate the old one.

## 📖 Glossary of Terms

- WordPress: The software platform that powers your website.
- Plugin: An add-on that brings new features to WordPress.
- MCP: The Model Context Protocol, the language your AI uses to talk to your site.
- WP-CLI: A command-line tool that lets you manage WordPress without a web browser.
- WooCommerce: A plugin that adds e-commerce features like products and carts to your site.
- Gutenberg: The default editor tool used to create posts and pages in WordPress.
- Elementor: A specialized builder tool that uses visual blocks to design page layouts.
- Agent: An AI tool configured to perform tasks on your behalf through language models.

## 🤝 Support and Community

Report bugs or suggest features through the official GitHub issues tracker. Include your WordPress version and your server PHP version in your report to help developers identify the cause of any errors. You can contribute to the code or help translate the instructions into other languages. This project relies on community feedback to improve stability and performance for all users.
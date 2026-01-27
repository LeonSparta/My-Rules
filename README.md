# My Shadowrocket Rules

This repository hosts custom configuration rules for the [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) iOS application.

## 📋 Description

These rules are designed to optimize routing for specific services. Currently, it focuses on proxying traffic for various Apple media and podcast services.

## 🛠 Usage

### Option 1: Remote Configuration (Recommended)
You can add this configuration file directly to Shadowrocket using the raw GitHub URL (once this repository is pushed to GitHub).

1. Open **Shadowrocket**.
2. Navigate to the **Config** tab.
3. Tap the `+` button or "Add Configuration".
4. Enter the raw URL of `my_rules.conf`.
   * *Example:* `https://raw.githubusercontent.com/<your-username>/My-Shadowrocket-Rules/main/my_rules.conf`
5. Save and select the configuration file to activate it.

### Option 2: Manual Import
1. Copy the contents of [`my_rules.conf`](./my_rules.conf).
2. Create a new local file in Shadowrocket or append the rules to your existing config.

## 📦 Included Rules

The configuration currently dictates that traffic for the following domains be routed through the **PROXY**:

*   `mzstatic.com`
*   `podcasts.apple.com`
*   `play.itunes.apple.com`
*   `xp.apple.com`
*   `bookkeeper.itunes.apple.com`

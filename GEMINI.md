# Project Overview

This repository contains custom configuration rules for **Shadowrocket**, a rule-based proxy utility client. The primary purpose is to maintain and share specific routing rules for domains.

## Key Files

*   **`my_rules.conf`**: The core configuration file.
    *   **Name**: My Rules
    *   **Description**: My Own Rules
    *   **Contents**:
        *   `[General]`: General settings (currently commented out).
        *   `[Rules]`: Specific domain suffix rules (e.g., Apple services like `mzstatic.com`, `podcasts.apple.com`) set to use the `PROXY` adapter.

## Usage

These rules are intended to be imported into the Shadowrocket application.

1.  **Direct Import**: If hosted online (e.g., via GitHub Raw), the URL to `my_rules.conf` can be added to Shadowrocket's configuration downloads.
2.  **Local Usage**: The content can be copied or the file transferred to the device running Shadowrocket.

## Development Conventions

*   **Rule Format**: Rules follow the standard Shadowrocket format: `TYPE,DOMAIN,POLICY`.
*   **Metadata**: The file includes metadata headers (`#!name` and `#!desc`) for easy identification within the app.

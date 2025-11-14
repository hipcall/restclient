# REST Client Setup

This repository provides example `.http` request files for testing Hipcall APIs with REST Client extensions in VS Code or Cursor.

## Installation

1. Open VS Code or Cursor.
2. Press `Ctrl+Shift+X` (Extensions panel).
3. Search for **REST Client**.
4. Select `humao.rest-client` and click **Install**.
5. Restart your editor after installation.

## Usage

1. Open any `.http` file (e.g., `APIv3/Sales.http`).
2. Hover over the request block and click **Send Request**.
3. Inspect the response panel for status, headers, and body.
4. Configure environment variables (like `base_url` or `token`) via `http-client.env.json` or the extension settings.

Once installed, you can interact with all provided API samples directly from VS Code or Cursor without additional tooling.
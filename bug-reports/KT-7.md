# [KT-7] Broken product images and unclickable buttons under problem_user

- **Project:** Kanban Team
- **Issue Type:** Bug
- **Status:** TO DO
- **Priority:** Medium
- **Reporter:** Hania Imran
- **Assignee:** Hania Imran
- **Environment:** 1001.0.0-SNAPSHOT / Chrome Browser

## Defect Summary
When authenticating into Swag Labs using `problem_user`, the product grid fails to load correct item assets and displays placeholder/broken image URLs.

## Pre-conditions
- Target URL: `https://www.saucedemo.com/`
- Credentials: `problem_user` / `secret_sauce`

## Steps to Reproduce
1. Navigate to the login page.
2. Enter username `problem_user` and password `secret_sauce`.
3. Click Login.
4. Inspect the item catalog on `/inventory.html`.

## Expected Result
Each product displays its unique item image asset.

## Actual Result
All product items render the same placeholder image (`/static/media/sl-404.168b1cce.jpg`).

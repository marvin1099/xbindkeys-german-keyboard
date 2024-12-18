# Xbindkeys-German-Config  

This configuration emulates the German keyboard's third layer functionality from Windows on Linux systems. It maps many `Ctrl + Alt` shortcuts to the keys that are usually accessed with `AltGr + key`, allowing you to type special characters like `@` or `€`.  

By default, Linux uses `AltGr` (Right Alt) for third-layer input. This configuration enables using `Ctrl + Alt` as an alternative for convenience or compatibility with workflows accustomed to the Windows layout.

[Deutsche Anleitung (German Instructions)](#deutsche-anleitung-german-instructions)

---

## Compatibility  

This configuration is compatible with Linux systems based on:  
- **Arch Linux**  
- **Debian-based distributions** (e.g., Ubuntu, Linux Mint)  
- **Red Hat-based distributions** (e.g., Fedora, CentOS)  
- **Other systems**, such as Gentoo and OpenSUSE.  

The setup relies on `xbindkeys` and `xvkbd`, which are widely available.  

---

## Installation  

Follow these steps to set up `xbindkeys` and `xvkbd` and download the configuration file.  

### **Step 1: Install Required Tools**  

#### **On Arch-based Systems**  
```bash
sudo pacman -S xbindkeys xvkbd
```  

#### **On Debian-based Systems**  
```bash
sudo apt update
sudo apt install xbindkeys xvkbd
```  

<details>  
<summary>Click here for Red Hat, Gentoo and OpenSUSE</summary>  


#### **On Red Hat-based Systems**  
```bash
sudo dnf install epel-release
sudo dnf install xbindkeys xvkbd
```  

#### **On Gentoo**  
```bash
sudo emerge x11-misc/xbindkeys x11-misc/xvkbd
```  

#### **On OpenSUSE**  
```bash
sudo zypper install xbindkeys xvkbd
```  
</details>  


---

### **Step 2: Download the Configuration File**  

#### **Automatic Download**  
To automatically download the configuration file:  
```bash
curl -o ~/.xbindkeysrc 'https://codeberg.org/marvin1099/xbindkeys-german-keyboard/raw/branch/main/.xbindkeysrc'
```  

#### **Manual Download**  
1. Visit the repository:  
   [Xbindkeys German Keyboard Configuration](https://codeberg.org/marvin1099/xbindkeys-german-keyboard).  
2. Download the `.xbindkeysrc` file.  
3. Save it to your home directory as `~/.xbindkeysrc`.  

---

### **Step 3: Start and Test**  

1. Start `xbindkeys` to activate the configuration:  
   ```bash
   xbindkeys
   ```  
2. Test the key bindings by trying `AltGr + Q` for `@`, or other third-layer symbols.  

For troubleshooting or customization, you can edit the configuration file (`~/.xbindkeysrc`) using a text editor.  

3. To make this permanent, add the `xbindkeys` command to your system's startup applications.

---




# Deutsche Anleitung (German Instructions)

Diese Konfiguration emuliert die dritte Ebene der deutschen Tastaturbelegung von Windows auf Linux-Systemen. Sie ordnet viele `Strg + Alt`-Kombinationen den Tasten zu, die normalerweise mit `AltGr + Taste` erreichbar sind, sodass Sie Sonderzeichen wie `@` oder `€` eingeben können.  

Standardmäßig verwendet Linux `AltGr` (Rechte Alt-Taste) für die Eingabe der dritten Ebene. Diese Konfiguration ermöglicht die Nutzung von `Strg + Alt` als Alternative, um die Bedienung zu erleichtern oder mit Workflows, die dem Windows-Layout entsprechen, kompatibel zu sein.

---

## Kompatibilität  

Diese Konfiguration ist kompatibel mit Linux-Systemen, die auf folgenden Distributionen basieren:  
- **Arch Linux**  
- **Debian-basierte Distributionen** (z. B. Ubuntu, Linux Mint)  
- **Red Hat-basierte Distributionen** (z. B. Fedora, CentOS)  
- **Andere Systeme**, wie Gentoo und OpenSUSE.  

Die Einrichtung basiert auf `xbindkeys` und `xvkbd`, die universell verfügbar sind.  

---

## Installation  

### **Schritt 1: Erforderliche Werkzeuge installieren**  

#### **Auf Arch-basierten Systemen**  
```bash
sudo pacman -S xbindkeys xvkbd
```  

#### **Auf Debian-basierten Systemen**  
```bash
sudo apt update
sudo apt install xbindkeys xvkbd
```  


<details>  
<summary>Klick hier für Red Hat, Gentoo und OpenSUSE</summary>  


#### **Auf Red Hat-basierten Systemen**  
```bash
sudo dnf install epel-release
sudo dnf install xbindkeys xvkbd
```  

#### **Auf Gentoo**  
```bash
sudo emerge x11-misc/xbindkeys x11-misc/xvkbd
```  

#### **Auf OpenSUSE**  
```bash
sudo zypper install xbindkeys xvkbd
```  
</details>  


---

### **Schritt 2: Konfigurationsdatei herunterladen**  

#### **Automatischer Download**  
```bash
curl -o ~/.xbindkeysrc 'https://codeberg.org/marvin1099/xbindkeys-german-keyboard/raw/branch/main/.xbindkeysrc'
```  

#### **Manueller Download**  
1. Besuchen Sie das Repository:  
   [Xbindkeys German Keyboard Configuration](https://codeberg.org/marvin1099/xbindkeys-german-keyboard).  
2. Laden Sie die Datei `.xbindkeysrc` herunter.  
3. Speichern Sie sie im Home-Verzeichnis als `~/.xbindkeysrc`.  

---

### **Schritt 3: Starten und Testen**  

1. Starten Sie `xbindkeys`, um die Konfiguration zu aktivieren:  
   ```bash
   xbindkeys
   ```  
2. Testen Sie die Tastenbelegungen, z. B. `AltGr + Q` für `@`.  

Zur Fehlersuche oder Anpassung können Sie die Konfigurationsdatei (`~/.xbindkeysrc`) mit einem Texteditor bearbeiten.  

3. Um dies dauerhaft zu machen, fügen Sie den Befehl `xbindkeys` zu den Autostart-Anwendungen Ihres Systems hinzu.

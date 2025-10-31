# 🇬🇧 FConvert Updates (English)

This repository provides update information and binary files for the FConvert app. It is used by the application to automatically check for new versions and download them securely.

## 📁 Structure

```
update.json          # Contains current version information
fconvert_v1.3.0.exe  # Latest app version
README.md            # This description
```

## 🔄 How It Works

The app automatically checks the `update.json` file on startup or when clicking “Check for Updates.”

Example content:

```json
{
  "version": "1.3.0",
  "url": "https://yourname.github.io/fconvert-updates/fconvert_v1.3.0.exe",
  "sha256": "<SHA256 hash of the file>"
}
```

If a newer version is found, the app prompts the user to download and install it. After verifying the SHA-256 checksum, the new version is installed and launched automatically.

## 🌐 Hosting

This repository is hosted via **GitHub Pages**:

```
https://yourname.github.io/fconvert-updates/update.json
```

The app uses this URL as its update source.

## 📜 License

See [LICENSE](LICENSE) for license information.

---

# 🇩🇪 FConvert Updates (Deutsch)

Dieses Repository stellt Update-Informationen und Binärdateien für die FConvert-App bereit. Es wird von der Anwendung genutzt, um automatisch nach neuen Versionen zu suchen und diese sicher herunterzuladen.

## 📁 Struktur

```
update.json          # Enthält aktuelle Versionsinformationen
fconvert_v1.3.0.exe  # Neueste App-Version
README.md            # Diese Beschreibung
```

## 🔄 Funktionsweise

Die App überprüft beim Start oder beim Klick auf „Nach Updates suchen“ automatisch die `update.json` Datei.

Beispielinhalt:

```json
{
  "version": "1.3.0",
  "url": "https://deinname.github.io/fconvert-updates/fconvert_v1.3.0.exe",
  "sha256": "<SHA256-Hash der Datei>"
}
```

Wenn eine neuere Version gefunden wird, fragt die App, ob das Update heruntergeladen und installiert werden soll. Nach erfolgreicher Integritätsprüfung (SHA-256) wird die neue Version automatisch installiert und gestartet.

## 🌐 Hosting

Dieses Repository wird über **GitHub Pages** ausgeliefert:

```
https://deinname.github.io/fconvert-updates/update.json
```

Die App nutzt diese URL als Update-Quelle.

## 📜 Lizenz

Siehe [LICENSE](LICENSE) für Lizenzinformationen.

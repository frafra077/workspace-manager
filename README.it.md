<p align="center">
  <img src="app-icon.png" alt="WorkSpace Manager Icon" width="120" height="120" style="border-radius: 28px; box-shadow: 0 10px 30px rgba(0,0,0,0.2);" />
</p>

<h1 align="center">WorkSpace Manager for macOS</h1>

<p align="center">
  <strong>Versione 2.0.1</strong> • Automazione Pro per macOS<br/>
  App, Siti, Cartelle e Terminali aperti in <strong>un click</strong>.
</p>

<p align="center">
  <a href="https://frafra077.github.io/workspace-manager/"><b>🌐 Sito Ufficiale & Offerta</b></a> •
  <a href="https://github.com/frafra077/workspace-manager/releases/latest"><b>📦 Download v2.0 (.dmg)</b></a>
</p>

<!-- BADGES -->
<div align="center">
  <img src="https://img.shields.io/badge/Apple-Notarized_%26_Signed-success?style=for-the-badge&logo=apple&logoColor=white" alt="Apple Notarized" />
<!-- download  <img src="https://img.shields.io/github/downloads/frafra077/workspace-manager/total?style=for-the-badge&logo=github&logoColor=white&color=3b82f6" alt="Downloads" />-->
  <img src="https://img.shields.io/badge/SwiftUI-100%25%20Nativo-blueviolet?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
</div>

<br/>

> [!TIP]
> **Nuovo in v2.0.1:** Localizzazione inglese migliorata e correzioni bug.
> **Nuovo in v2.0:** Supporto completo **TouchID**, sicurezza biometrica e automazioni avanzate.
> L'app è ora **Notarizzata da Apple**: installazione sicura senza avvisi.

---

## ⚡️ Perché WorkSpace Manager?

Smetti di perdere 10 minuti ogni mattina per preparare la tua scrivania digitale.
Con WorkSpace Manager crei dei "contesti" (es. *Lavoro, Università, Freelance*) e li lanci in un istante.

### ✨ Novità v2.0.0

| 🔒 **Privacy & Sicurezza** | 🚀 **Performance** | 🌍 **Multilingua** | 🌗 **Temi** |
|---|---|---|---|
| **TouchID / FaceID** support | Motore nativo riscritto | Italiano 🇮🇹 / English 🇬🇧 | Light/Dark/System |

| 💾 **Backup** | 🔄 **Smart Relaunch** | ⭐ **Preferito** | 📖 **Onboarding** |
|---|---|---|---|
| Esporta/Importa JSON | Riapri elementi singoli | Workspace default | Guida interattiva |

---

## 📸 Anteprima

<p align="center">
  <img src="SCREEN_DASHBOARD.png" alt="WorkSpace Manager Dashboard" width="100%" style="border-radius: 12px; border: 1px solid #333;" />
</p>

---

## 💎 Caratteristiche Principali

✅ **Automazione in un Click**  
Definisci un workspace e WorkSpace Manager aprirà simultaneamente:
- Applicazioni multiple
- Siti web (nel browser predefinito)
- Cartelle del Finder
- Finestre di Terminale (con percorsi specifici)

✅ **Sicurezza Biometrica (New v2.0)**  
Proteggi i tuoi workspace sensibili con **TouchID** o password di sistema.

✅ **Menu Bar Resident 2.0**  
Un'icona discreta nella barra dei menu per lanciare i tuoi setup senza aprire la finestra principale.

✅ **100% macOS Nativo**  
Sviluppato in Swift e SwiftUI. Pesa solo **~15MB**. Niente Electron, niente ventole al massimo.

✅ **Backup & Restore**  
Esporta i tuoi profili in formato JSON e portali su un altro Mac in un secondo.

---

## 📦 Installazione Sicura

Essendo un software certificato Apple, l'installazione è standard:

1. **Scarica** `WorkSpace.2.0.1.dmg` dalla [Release Section](https://github.com/frafra077/workspace-manager/releases/latest)
2. **Trascina** l'icona nella cartella `Applicazioni`
3. **Avvia** e goditi il tuo tempo risparmiato 🚀

*(Nessun avviso di sicurezza strano, nessun "Tasto destro -> Apri" necessario)*

---

## 💼 Licenza & Supporto

WorkSpace Manager è distribuito con modello **Freemium**.
- **Starter (Gratis):** Funzionalità base illimitate nel tempo.
- **Pro License:** Sblocca TouchID, Workspace illimitati e Supporto Prioritario.

👉 [Acquista Licenza PRO sul Sito Ufficiale](https://frafra077.github.io/workspace-manager/#download)

Per segnalare bug o richiedere feature:
- 🐞 **Issue Tracker**: [GitHub Issues](https://github.com/frafra077/workspace-manager/issues)

---

## 📋 Changelog

### v2.0.1 (27 Gennaio 2026)
- ✅ Enhanced English localization (Settings section fully translated)
- 🐛 Minor bug fixes and performance improvements

### v2.0.0 (19 Gennaio 2026)
- 🔒 TouchID / FaceID support
- 🌍 Full Italian & English localization
- 🌗 Light/Dark theme support
- 💾 Backup & Restore
- ⭐ Favorite workspace
- 📖 Interactive onboarding

[View all releases →](https://github.com/frafra077/workspace-manager/releases)

---


## 📱 Requisiti di Sistema

- macOS **Sonoma 14.0** o superiore
- Processore: Apple Silicon (M1/M2/M3) o Intel


![Notarized](https://img.shields.io/badge/macOS-Notarized_%26_Signed-brightgreen?style=for-the-badge&logo=apple&logoColor=white)

-------

⭐ **Star this repo if you find it useful!**

## 👨‍💻 Codice SwiftUI (Anteprima)

```swift
struct WorkspaceItemView: View {
    let workspace: WorkspaceModel
    
    var body: some View {
        HStack {
            Image(systemName: workspace.icon)
                .foregroundStyle(.blue)
                .font(.title2)
            
            VStack(alignment: .leading) {
                Text(workspace.name)
                    .font(.headline)
                Text("$$workspace.items.count) elementi")
                    .font(.caption)
                    .foregroundStyle(.secondary)
            }
            
            Spacer()
            
            Button("Avvia") {
                launchWorkspace(workspace)
            }
            .buttonStyle(.borderedProminent)
        }
        .padding()
        .glassBackgroundEffect()
    }
}


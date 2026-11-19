========================================================================
  DesktopConnect v2.0.0 per TidaLuna — Guida Rapida (Zero Compilazione)
========================================================================

Questa cartella contiene GIA' tutto pronto e compilato (cartella dist/),
quindi NON devi installare nessun programma né compilare nulla.

--- DOVE METTERE LA CARTELLA ---

OPZIONE A — Caricamento locale su Windows (Consigliata):
1. Estrai l'intera cartella "DesktopConnect" da questo file ZIP.
2. Premi i tasti WIN + R sulla tastiera, scrivi:
      %APPDATA%\TIDAL\luna\plugins
   e premi Invio. (Se la cartella "plugins" non esiste dentro luna, creala).
3. Copia l'intera cartella "DesktopConnect" dentro quella cartella
   (il percorso finale deve essere: %APPDATA%\TIDAL\luna\plugins\DesktopConnect).
4. Apri TIDAL -> Impostazioni di TidaLuna -> attiva "Developer Mode" (se non è già attivo)
   e assicurati che "DesktopConnect" sia attivo, mentre "tidal-connect-pro" sia DISATTIVATO.
5. Chiudi completamente TIDAL (anche dall'icona accanto all'orologio in basso a destra) e riaprilo.

OPZIONE B — Se vuoi caricarlo su un tuo repository GitHub:
1. Crea un nuovo repository vuoto su GitHub (es. "DesktopConnect").
2. Trascina tutti i file e le cartelle contenuti dentro "DesktopConnect"
   (package.json, manifest.json, tsconfig.json, dist/, src/) nella pagina del repository e fai Commit.
3. Copia il link del repository GitHub e incollalo nella barra "Install Plugin" dentro TidaLuna.

--- REQUISITO RETE / FIREWALL WINDOWS ---
Se l'app TIDAL sul telefono (collegato allo stesso Wi-Fi del PC) non vede
il dispositivo "TidaLuna: NOME-PC":
- Apri "Windows Defender Firewall" -> "Consenti app o funzionalità attraverso Windows Defender Firewall"
- Trova "TIDAL" e metti la spunta sia su "Privata" sia su "Pubblica".

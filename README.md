# Repository plugin QGIS — Dott. Sarino Alfonso Grande

Repository personalizzato per il [Plugin Manager di QGIS](https://docs.qgis.org/latest/it/docs/user_manual/plugins/plugins.html):
aggiungilo una volta sola e installi/aggiorni i plugin direttamente da QGIS,
come da repository ufficiale.

*Custom QGIS plugin repository: add it once in the QGIS Plugin Manager and
install/update the plugins directly from QGIS.*

**URL del repository / Repository URL:**

```
https://sag1687.github.io/sarinoalfonsogrande/plugins.xml
```

## Installazione / How to install

1. In QGIS apri **Plugins → Gestisci e installa plugin → Impostazioni**
   (*Plugins → Manage and Install Plugins → Settings*)
2. In **Repository dei plugin** (*Plugin Repositories*) premi **Aggiungi** (*Add*)
3. Nome / Name: `SinoCloud` — URL: `https://sag1687.github.io/sarinoalfonsogrande/plugins.xml`
4. Conferma: i plugin compaiono nell'elenco del Plugin Manager e gli
   aggiornamenti vengono proposti automaticamente da QGIS.

## Plugin disponibili / Available plugins

| | Plugin | Versione | QGIS min | Download |
|---|---|---|---|---|
| <img src="icons/q_press.svg" width="24"> | [Q-Press](#q_press) | 2.0.2 | 3.16 | [zip](zips/q_press.zip) |
| <img src="icons/crs.png" width="24"> | [Quick CRS Fixer](#crs) | 2.0.3 | 3.16 | [zip](zips/crs.zip) |
| <img src="icons/geobridge.svg" width="24"> | [GeoBridge](#geobridge) | 1.2.2 | 3.22 | [zip](zips/geobridge.zip) |
| <img src="icons/qgis_ledger.jpg" width="24"> | [QGIS Ledger](#qgis_ledger) | 4.0.3 | 3.0 | [zip](zips/qgis_ledger.zip) |
| <img src="icons/csv_importer_plugin.svg" width="24"> | [GeoCSV Mapper](#csv_importer_plugin) | 2.2.1 | 3.0 | [zip](zips/csv_importer_plugin.zip) |
| <img src="icons/SAR.svg" width="24"> | [STAC Browser](#sar) | 1.6.1 | 3.16 | [zip](zips/SAR.zip) |
| <img src="icons/SARIAG.svg" width="24"> | [SARIAG](#sariag) ⚠️ | 0.2.0 | 3.16 | [zip](zips/SARIAG.zip) |
| <img src="icons/QGIS_TAF_Plugin.png" width="24"> | [TAF Italia](#qgis_taf_plugin) ⚠️ | 2.6.2 | 3.10 | [zip](zips/QGIS_TAF_Plugin.zip) |

⚠️ = sperimentale / experimental

## Dettagli / Details

### <a name="q_press"></a>Q-Press — v2.0.2

Professional cartographic PDF generator for QGIS 4/Qt6. Use Shift+Drag to select an area and export a comprehensive map with automatic or manual scale, custom paper size, filtered attributes, charts, and topographic profiles.

Q-Press allows you to select an area directly from the QGIS canvas using Shift+Drag and instantly generate a professional cartographic PDF. The output includes a technical title block, automatic or manual scale, custom paper size, coordinate grids, legend, overview map, filtered attribute tables, statistical dashboards, and a single-line topographic profile from OpenTopoData or a project DTM/DEM raster.

- **Versione minima QGIS:** 3.16
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/q_press
- **Segnalazione bug:** https://github.com/sag1687/q_press/issues
- **Download diretto:** [zips/q_press.zip](zips/q_press.zip)

### <a name="crs"></a>Quick CRS Fixer — v2.0.3

Strumento avanzato per il rilevamento e la correzione automatica dei problemi di CRS / Advanced tool for automatic detection and correction of CRS issues

[IT] Quick CRS Fixer è un plugin essenziale per individuare e risolvere problematiche legate ai Sistemi di Riferimento delle Coordinate (CRS). Funzionalità principali: rilevamento automatico delle incongruenze geometriche; suggerimento intelligente dell'EPSG corretto tramite toponimi ed estensione spaziale; integrazione con OpenStreetMap (Nominatim) e Wikipedia; scheda Help; selettore lingua italiano/inglese. Compatibile con QGIS 3.x e QGIS 4.0+/Qt6. Sviluppato per ricerca e utilità pubblica. --- [EN] Quick CRS Fixer is an essential plugin for identifying and resolving Coordinate Reference System (CRS) issues. Key features: automatic detection of geometric inconsistencies; smart EPSG suggestions through place names and spatial extents; OpenStreetMap (Nominatim) and Wikipedia integration; Help tab; Italian/English language selector. Compatible with QGIS 3.x and QGIS 4.0+/Qt6. Developed for research and public utility.

- **Versione minima QGIS:** 3.16
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/CRS_FIXER
- **Segnalazione bug:** https://github.com/sag1687/CRS_FIXER/issues
- **Download diretto:** [zips/crs.zip](zips/crs.zip)

### <a name="geobridge"></a>GeoBridge — v1.2.2

IT: Client QGIS non ufficiale per usare le API servizio API IGM (IGM): conversione di coordinate e layer vettoriali. Coadiuvato da AI. / EN: Unofficial QGIS client for API IGMs (IGM): coordinates and vector layers conversion. Assisted by AI.

IT: GeoBridge e' un client QGIS non ufficiale. Il codice del plugin e' distribuito sotto licenza GPL-2.0-or-later. IMPORTANTE: L'autore non si appropria ne' rivendica alcun diritto sui prodotti IGM. Il servizio API IGM, l'infrastruttura, il marchio e le elaborazioni sono e restano di esclusiva proprieta' dell'Istituto Geografico Militare. Sviluppo coadiuvato da AI. EN: GeoBridge is an unofficial QGIS client. The plugin code is licensed under GPL-2.0-or-later. IMPORTANT: The author does not appropriate or claim any rights over IGM products. The servizio API IGM service, infrastructure, brand, and processing results are and remain the exclusive property of the Italian Military Geographic Institute. Development assisted by AI.

- **Versione minima QGIS:** 3.22
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/geobridge
- **Segnalazione bug:** https://github.com/sag1687/geobridge/issues
- **Download diretto:** [zips/geobridge.zip](zips/geobridge.zip)

### <a name="qgis_ledger"></a>QGIS Ledger — v4.0.3

Enterprise-grade Git-like version control for QGIS. Features semantic geometric diffing, deterministic rollback, and multi-cloud synchronization (Nextcloud, WebDAV, Dropbox, OneDrive, Google Drive).

============================================================
ITALIANO
============================================================
QGIS Ledger — Versioning di Livello Enterprise per QGIS
Sistema di tracciamento storico e sincronizzazione cloud progettato per l'integrità dei dati spaziali, senza dipendenze esterne. Ottimizzato per QGIS 3.x e QGIS 4 (Qt6).

FUNZIONALITÀ PRINCIPALI:
- Architettura a Snapshot: Commit atomici di layer e progetti in SQLite locale.
- Diff Semantico-Visuale: Analisi geometrica delle differenze tra versioni.
- Rollback Deterministico: Ripristino istantaneo di dati e stili.
- Sincronizzazione Cloud: Supporto nativo per Nextcloud, WebDAV, Dropbox, OneDrive e GDrive.
- Merge Wizard: Gestione conflitti in split-screen.

============================================================
ENGLISH
============================================================
QGIS Ledger — Enterprise-Grade Version Control for QGIS
Comprehensive historical tracking and cloud synchronization engine engineered for geospatial data integrity, operating entirely dependency-free across QGIS 3.x and QGIS 4 (Qt6).

CORE FEATURES:
- Snapshot Architecture: Atomic commits of layers and projects in local SQLite.
- Semantic Visual Diff: Geometric analysis of differences between versions.
- Deterministic Rollback: Instant restoration of data and styling.
- Cloud Synchronization: Native support for Nextcloud, WebDAV, Dropbox, OneDrive, and GDrive.
- Merge Wizard: Split-screen conflict resolution.

- **Versione minima QGIS:** 3.0
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/qgis_ledger
- **Segnalazione bug:** https://github.com/sag1687/qgis_ledger/issues
- **Download diretto:** [zips/qgis_ledger.zip](zips/qgis_ledger.zip)

### <a name="csv_importer_plugin"></a>GeoCSV Mapper — v2.2.1

IT: Importa file CSV con coordinate in vari formati. Riconoscimento DMS, anteprima mappa e salvataggio GeoPackage. | EN: Import CSV files with coordinates in various formats. DMS recognition, map preview, and GeoPackage saving.

IT: Questo plugin è uno strumento avanzato per l'importazione massiva di punti tramite file CSV in QGIS.\nOffre un potente parser per il riconoscimento automatico sia delle coordinate decimali standard sia dei formati sessagesimali complessi (DMS). Implementa un'anteprima rapida su cartografia OpenStreetMap, verifica in tempo reale la codifica testuale e supporta l'esportazione automatizzata verso il moderno formato standard GeoPackage.\n\nEN: This plugin is an advanced tool for the bulk import of points via CSV files in QGIS.\nIt offers a powerful parser for automatic recognition of both standard decimal coordinates and complex sexagesimal formats (DMS). It features a quick preview on OpenStreetMap cartography, real-time text encoding verification, and automated export support to the modern GeoPackage format.

- **Versione minima QGIS:** 3.0
- **Autore:** Dott. Sarino Alfonso Grande e Geometra Luca Casti
- **Codice sorgente:** https://github.com/sag1687/GeoCSV-Mapper
- **Segnalazione bug:** https://github.com/sag1687/GeoCSV-Mapper/issues
- **Download diretto:** [zips/csv_importer_plugin.zip](zips/csv_importer_plugin.zip)

### <a name="sar"></a>STAC Browser — v1.6.1

Find open Earth-observation data by drawing an area or typing an address. Results are grouped by data type with an adaptive timeline/cards layout, details dialogs, selectable COG band download and opt-in spectral index export. / Trova dati di osservazione della Terra disegnando un'area o digitando un indirizzo. I risultati sono organizzati per tipo dato con timeline/schede adattive, modali dettagli, download selettivo delle bande COG ed export opt-in degli indici spettrali.

EN: Find free and open Earth-observation data by drawing a rectangle, point or line on the map, or by typing an address (Nominatim geocoding). Automatic search queries every STAC catalog and shows only datasets that actually exist for that area, grouped by data type (orthophoto, 1/2/3 bands, multispectral, DEM, radar) with timeline, adaptive cards, details dialogs, selectable COG band download (all or only some) and NDVI/NDWI/False Color comparison. Indices are opt-in: they require an explicit flag, are saved as local GeoTIFFs and show download/processing time. Catalogs: Element84 Earth Search, Microsoft Planetary Computer, USGS LandsatLook, NASA EarthData CMR, OpenLandMap, US GeoPlatform, Copernicus Data Space, Digital Earth Australia. --- IT: Trova dati di osservazione della Terra liberi e gratuiti disegnando un rettangolo, un punto o una linea sulla mappa, oppure digitando un indirizzo (geocoding Nominatim). La ricerca automatica interroga tutti i cataloghi STAC e mostra solo i dataset realmente presenti per quell'area, organizzati per tipo dato (ortofoto, 1/2/3 bande, multispettrale, DEM, radar) con timeline, schede adattive, modali dettagli, scelta delle bande COG da scaricare (tutte o solo alcune) e confronto NDVI/NDWI/Falso Colore. Gli indici sono opt-in: richiedono un flag esplicito, vengono salvati come GeoTIFF locale e mostrano il tempo di download/elaborazione.

- **Versione minima QGIS:** 3.16
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/stac_browser
- **Segnalazione bug:** https://github.com/sag1687/stac_browser/issues
- **Download diretto:** [zips/SAR.zip](zips/SAR.zip)

### <a name="sariag"></a>SARIAG — v0.2.0

> ⚠️ **Plugin sperimentale**: visibile in QGIS solo attivando *"Mostra anche i plugin sperimentali"* nelle impostazioni del Plugin Manager.

Download Sentinel-1 SLC time series and compute East-West / Vertical ground displacement maps via SNAP-based InSAR time series processing. / Scarica serie temporali Sentinel-1 SLC e calcola mappe di spostamento Est-Ovest / Verticale tramite elaborazione InSAR multi-temporale basata su SNAP.

EN: SARIAG automates a multi-temporal InSAR (SBAS-style) workflow inside QGIS: it searches and downloads Sentinel-1 SLC scenes from the Copernicus Data Space Ecosystem for an area of interest, both ascending and descending orbit passes, drives ESA SNAP's Graph Processing Tool (gpt) to coregister, form interferograms, filter and unwrap phase (via SNAPHU), inverts the small-baseline network into per-date line-of-sight displacement time series, and decomposes the ascending+descending LOS results into East-West and Vertical displacement maps loaded directly into QGIS. Requires a local ESA SNAP installation (with the SNAPHU unwrapping plugin) and a free Copernicus Data Space Ecosystem account; SARIAG orchestrates these proven tools rather than reimplementing phase unwrapping from scratch. --- IT: SARIAG automatizza dentro QGIS un flusso InSAR multi-temporale (tipo SBAS): cerca e scarica scene Sentinel-1 SLC dal Copernicus Data Space Ecosystem per un'area di interesse, sia in orbita ascendente sia discendente, pilota il Graph Processing Tool (gpt) di ESA SNAP per coregistrazione, formazione degli interferogrammi, filtraggio e unwrapping di fase (via SNAPHU), inverte la rete a baseline corta in una serie temporale di spostamento lungo la linea di vista (LOS) per ciascuna data, e scompone i risultati ascendente+discendente in mappe di spostamento Est-Ovest e Verticale caricate direttamente in QGIS. Richiede un'installazione locale di ESA SNAP (con il plugin di unwrapping SNAPHU) e un account gratuito Copernicus Data Space Ecosystem; SARIAG orchestra questi strumenti collaudati invece di reimplementare da zero l'unwrapping di fase.

- **Versione minima QGIS:** 3.16
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/sariag
- **Segnalazione bug:** https://github.com/sag1687/sariag/issues
- **Download diretto:** [zips/SARIAG.zip](zips/SARIAG.zip)

### <a name="qgis_taf_plugin"></a>TAF Italia — v2.6.2

> ⚠️ **Plugin sperimentale**: visibile in QGIS solo attivando *"Mostra anche i plugin sperimentali"* nelle impostazioni del Plugin Manager.

Scarica e converte i Punti Fiduciali (TAF) dall'Agenzia delle Entrate in CSV/WGS84 per QGIS. / Downloads and converts Fiducial Points (TAF) from the Italian Revenue Agency into CSV/WGS84 for QGIS.

ITA: TAF Italia automatizza il download dei Punti Fiduciali catastali dall'Agenzia delle Entrate, li converte dal sistema Cassini-Soldner/Gauss-Boaga al WGS84 (EPSG:4326) e li esporta in formato CSV caricabile direttamente in QGIS. ATTENZIONE: i dati potrebbero contenere punti outlier dovuti a errori nella conversione delle coordinate originali. Il plugin determina il sistema di riferimento dal valore della coordinata Est (soglie Gauss-Boaga Ovest/Est, Cassini-Soldner). Le coordinate Cassini-Soldner usano il modello delle 31 Grandi Origini nazionali, non le singole origini comunali, con possibili scostamenti di decine di metri. Include un editor visivo di origini locali (export template CSV, import da file, salvataggio configurazione), generazione automatica link monografie, tematizzazione QGIS (triangolo verde, label PF/FG/COM, azione apertura browser) e mappa interattiva OSM. ENG: TAF Italia automates the download of cadastral Fiducial Points from the Italian Revenue Agency, converts them from Cassini-Soldner/Gauss-Boaga to WGS84 (EPSG:4326) and exports them as CSV files directly loadable in QGIS. WARNING: data may contain outlier points due to errors in the original coordinate conversion. The plugin detects the CRS from the Easting value thresholds. Cassini-Soldner coordinates use the 31 Great National Origins model, not single municipal origins, with possible deviations of tens of meters. Includes a visual local origins editor, automatic monografia link generation, QGIS styling (green triangle, PF/FG/COM labels, browser action) and interactive OSM map.

- **Versione minima QGIS:** 3.10
- **Autore:** Dott. Sarino Alfonso Grande
- **Codice sorgente:** https://github.com/sag1687/TAF_ITALIA_DOWNLOAD
- **Segnalazione bug:** https://github.com/sag1687/TAF_ITALIA_DOWNLOAD/issues
- **Download diretto:** [zips/QGIS_TAF_Plugin.zip](zips/QGIS_TAF_Plugin.zip)

---

Sito / Website: [sinocloud.it](https://sinocloud.it) — Contatto / Contact: sino.grande@gmail.com

*README generato automaticamente dai `metadata.txt` dei plugin — ultimo aggiornamento: 13/07/2026.*

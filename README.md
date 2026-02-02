# Ukrainian → English Kindle Dictionary (Popup Lookup)

This repository contains a **custom Ukrainian → English dictionary** built specifically for **Kindle popup word lookup**. when reading Ukrainian text, you can tap or highlight a word and Kindle will show its translation/definition instantly in a popup.

---

## 📥 Download

Download the dictionary file here:

➡️ **[Download uk-en-dictionary.mobi](./uk-en-dictionary.mobi)**

(If GitHub opens it instead of downloading, use **Right click → Save link as…**)

---

## 📲 How to install on Kindle

1. Connect your Kindle to your computer using a USB cable  
2. Open the Kindle drive on your computer  
3. Navigate to:

   `documents/dictionaries/`

   (If the folder does not exist, create it)

4. Copy the file:

   `uk-en-dictionary.mobi`

5. Safely eject the Kindle

6. On your Kindle, open any Ukrainian book, tap a word, and the dictionary popup should appear  
   (If needed, select this dictionary manually from the popup menu)

---


## 📖 What is included?

This dictionary now contains approximately:

- **62,751+ Ukrainian entries**
- Ukrainian wordforms → English translations/definitions
- Expanded vocabulary including the **most common words extracted from 12 fiction books**
- Improved support for **inflected forms** (declensions, conjugations, plural forms, etc.)
- Cleaned and merged dataset with deduplicated entries


## 🔧 How this dictionary was created


1. Import of a Ukrainian → English combined vocabulary CSV  
2. Expansion using **12 Ukrainian fiction books**:
   - extraction of the **most frequent additional wordforms**
   - removal of duplicates and merging with the base dataset  
3. Cleaning and normalization:
   - Unicode NFC normalization  
   - removal of invalid/invisible characters  
4. Translation enrichment:
   - missing definitions generated automatically via an external **LLM API**  
5. Kindle dictionary formatting:
   - `dictionary.html` built using the official KDP structure  
   - `dictionary.opf` metadata (`uk → en`, proper lookup index)  
6. Final compilation into `.mobi` using **Kindle Previewer 3**


---

## 📌 Disclaimer

This project is experimental and intended for personal/offline language learning use.

---

Feel free to contribute improvements or expanded wordform support 🙂

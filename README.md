# Ukrainian → English Kindle Dictionary (Popup Lookup)

This repository contains a **custom Ukrainian → English dictionary** built specifically for **Kindle popup word lookup**. when reading Ukrainian text, you can tap or highlight a word and Kindle will show its translation/definition instantly in a popup.

---

## 📥 Download

Download the dictionary file here:

➡️ **[Download uk-en-dictionary.mobi](./uk-en-dictionary.mobi)**

(If GitHub opens it instead of downloading, use **Right click → Save link as…**)

---

## 📖 What is included?

This dictionary contains approximately:

- **31,900+ Ukrainian headwords**
- Ukrainian entries → English translations/definitions
- Cleaned and merged vocabulary from a combined CSV dataset

---

## ⚠️ Limitations / Known Issues

Kindle dictionary lookup is strict:

- Kindle does **not** perform full lemmatization  
  (inflected forms may fail unless explicitly present)
- Some rare or irregular wordforms may not be recognized
- The dictionary focuses on headwords rather than exhaustive morphology
- Due to problems with OCR and data cleasing over printed old dictionaries, there are errors in some translations.

---

## 🔧 How this dictionary was created

This dictionary was generated through a reproducible pipeline:

1. Import of a Ukrainian → English combined vocabulary CSV  
2. Cleaning and normalization:
   - Unicode NFC normalization  
   - Removal of invalid/invisible characters  
3. Deduplication:
   - identical headwords merged into a single entry  
4. Kindle dictionary formatting:
   - `dictionary.html` built using the official KDP dictionary structure  
   - `dictionary.opf` metadata with:
     - `DictionaryInLanguage = uk`
     - `DictionaryOutLanguage = en`
     - `DefaultLookupIndex` properly aligned  
5. Final compilation:
   - Exported into `.mobi` dictionary format using **Kindle Previewer 3**

---

## 📌 Disclaimer

This project is experimental and intended for personal/offline language learning use.

---

Feel free to contribute improvements or expanded wordform support 🙂

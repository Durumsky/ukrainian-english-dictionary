# Ukrainian–English Kindle Dictionary (Popup Lookup)

This repository contains a **custom Ukrainian → English dictionary** designed specifically for **Kindle popup word lookup**.

Unlike a normal ebook, this file works as a real Kindle dictionary:  
when reading Ukrainian text, you can tap or highlight a word and Kindle will show its translation/definition in a popup.

---

## 📖 What is included?

- **uk-en-dictionary.mobi**  
  A Kindle dictionary file ready to install and use.

This dictionary contains approximately:

- **83,000+ entries**
- Ukrainian headwords → English definitions/translations
- Multiple merged sources (PDF + CSV dictionaries)

---

## ✅ Features

- Works with Kindle’s built-in dictionary popup
- Supports many word variants:
  - lowercase / UPPERCASE / Capitalized forms  
  - apostrophe variants (`'`, `’`, `ʼ`)
  - Unicode normalization fixes
  - removal of invisible characters (ZWJ, soft hyphen, NBSP, BOM…)
  - punctuation variants (e.g. `word,` or `word.`)

---

## 📥 Download

You can download the dictionary directly here:

➡️ **[Download uk-en-dictionary.mobi](./uk-en-dictionary.mobi)**

(If GitHub opens it instead of downloading, use **Right click → Save link as…**)

---

## 📲 How to install on Kindle

1. Connect your Kindle to your computer with a USB cable
2. Open the Kindle drive
3. Go to the folder: documents/dictionaries/


(If it does not exist, create it)

4. Copy:

uk-en-dictionary.mobi


5. Safely eject the Kindle

---


## 🛠 How to enable it on Kindle

1. Open any Ukrainian ebook
2. Tap a Ukrainian word
3. If the dictionary is not selected automatically:

- Tap the dictionary name in the popup
- Choose **Ukrainian–English Dictionary**

4. Kindle will remember it as default for Ukrainian texts

---

## ⚠️ Limitations / Known Issues

This dictionary is generated from scanned/OCR sources and large merged datasets.

Possible issues include:

- Some entries may contain OCR noise or formatting artifacts
- Some rare wordforms may still not be recognized (Kindle lookup is strict)
- Kindle does not perform lemmatization:
  - inflected forms may fail unless present as variants
  - Some headwords may appear duplicated with merged definitions

---

## 🔧 How this dictionary was created

This dictionary was built using a multi-step pipeline assisted by ChatGPT:

1. Extraction of Ukrainian–English entries from multiple PDF dictionaries  

2. OCR enhancement using `ocrmypdf` + Ukrainian/English language models

3. Merging datasets:
- Existing dictionary base (~41k entries)
- Large PDF dictionary (+40k entries)
- Additional CSV dictionary expansions

4. Cleaning & normalization:
- Unicode NFC/NFKC normalization
- Removal of invisible characters (ZWJ/ZWNJ/soft hyphen/NBSP/BOM)
- Deduplication and definition merging

5. Kindle-specific optimization:
- Regeneration of `dictionary.html` + `dictionary.opf`
- Addition of `<idx:infl>` variants for better word matching
- Final compilation into `.mobi` dictionary format via Kindle Previewer

---

## 📌 Disclaimer

This project is experimental and intended for personal/offline language learning use.  

---

Feel free to edit it :)



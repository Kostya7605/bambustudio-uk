# Bambu Studio Ukrainian Translation 🇺🇦
Unofficial Ukrainian localization for Bambu Studio  
Неофіційна українська локалізація для Bambu Studio

---

## 📥 Download

Download the latest compiled file (`BambuStudio.mo`) from the **Releases** section.

➡️ Go to **Releases** → download `BambuStudio.mo` from *Assets*

---

## 🔧 Compatibility

- Bambu Studio version: **2.5.0.66**
- Locale: **uk_UA**

---

## 📊 Translation Status

- Total strings: **4997**
- Translated: **3427 (68%)**
- Remaining: **1570**

The current translation base was synchronized with the official Ukrainian localization.
Ongoing revisions aim to improve terminology consistency, fix inaccuracies, and refine technical wording.

Поточна база перекладу синхронізована з офіційною українською локалізацією.
Подальша робота спрямована на виправлення неточностей, уніфікацію термінології та покращення технічної коректності.

---

## 🖥 Installation (Windows)

1. Close **Bambu Studio**
2. Download `BambuStudio.mo` from **Releases**
3. Navigate to:
	C:\Program Files\Bambu Studio\resources\i18n\uk\

4. Backup the original file:
- rename `BambuStudio.mo` → `BambuStudio_original.mo`
5. Copy the downloaded `BambuStudio.mo` into this folder
6. Start **Bambu Studio**

To restore the original translation, rename `BambuStudio_original.mo` back to `BambuStudio.mo`.

---

## 🔄 Updating Translation (for contributor)

1. Edit `po/BambuStudio.po`
2. Compile `.mo`:
	msgfmt po/BambuStudio.po -o BambuStudio.mo

3. Commit and push:
	git add .
	git commit -m "Update translation to XX%"
	git push

4. Create a new Release:
- Same app version → new revision tag  
  Example: `v2.5.0.66-r2`


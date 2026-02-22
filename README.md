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

The translation started from the original Ukrainian localization, which at the time of the current official base contained 3,427 strings. After updating the base, it turned out that the current version of the program has 4,997 strings. Thus, the Ukrainian translation covered only about 68% of the strings used in the program. The original translation required corrections and optimization. Work on translating the remaining strings has begun.

Переклад розпочався з оригінальної української локалізації, яка на момент актуальної офіційної бази містила 3,427 рядків. Після оновлення бази виявилося, що актуальна версія програми налічує 4,997 рядків. Таким чином, український переклад покривав лише близько 68% рядків, що використовуються в програмі. Оригінальний переклад потребував правок та оптимізації. Почато роботу над перекладом відсутніх рядків.

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

---

## 📜 License

MIT

# kurdish-philosophy-Hub# Kurdish Philosophy Hub | ناوەندی فەلسەفەی کوردی

[![Website](https://img.shields.io/badge/Website-jiridastkrd.com-blue.svg)](https://jiridastkrd.com/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This repository is the official data hub for the **[jiridastkrd.com](https://jiridastkrd.com/)** project. It contains structured, parallel translations of major philosophical works into the Kurdish language. Our goal is to create a rich, open, and accessible digital resource for students, researchers, and enthusiasts of philosophy in the Kurdish-speaking world.

ئەم ڕیپۆزیتۆرییە ناوەندی فەرمیی داتای پڕۆژەی **[jiridastkrd.com](https://jiridastkrd.com/)**ـە. وەرگێڕانی هاوتەریبی بەرهەمە فەلسەفییە گرنگەکانی بۆ سەر زمانی کوردی لەخۆدەگرێت. ئامانجمان دروستکردنی سەرچاوەیەکی دیجیتاڵیی دەوڵەمەند, کراوە و بەردەستە بۆ قوتابیان، توێژەران و هۆگرانی فەلسەفە لە جیهانی کوردزماندا.

---

## Project Structure | پێکهاتەی پرۆژەکە

The repository is organized hierarchically to ensure clarity and scalability. All translations are stored in `.json` format to maintain a parallel structure between the original text and its Kurdish translation.

پڕۆژەکە بە شێوەیەکی پلەبەندی ڕێکخراوە بۆ دڵنیابوون لە ڕوونی و توانای گەشەکردن. هەموو وەرگێڕانەکان لە فۆرماتی `.json`ـدا هەڵگیراون بۆ پاراستنی پێکهاتەیەکی هاوتەریب لە نێوان دەقی ڕەسەن و وەرگێڕانە کوردییەکەیدا.

The structure is as follows:

### JSON File Format | فۆرماتی فایلی JSON

Each JSON file contains an array of objects, where each object represents a segment of text (e.g., a sentence or paragraph) and its corresponding translation.

هەر فایلێکی JSON زنجیرەیەک ئۆبجێکتی تێدایە، کە هەر ئۆبجێکتێک نوێنەرایەتیی بەشێکی دەق (وەک ڕستەیەک یان پەڕەگرافێک) و وەرگێڕانەکەی دەکات.

```json
[
  {
    "id": "1.1",
    "original_lang": "grc",
    "original_text": "Τὴν περὶ τῆς ψυχῆς ἱστορίαν...",
    "translation_lang": "ku",
    "translation_text": "لێکۆڵینەوە دەربارەی گیان..."
  },
  {
    "id": "1.2",
    "original_lang": "grc",
    "original_text": "...",
    "translation_lang": "ku",
    "translation_text": "..."
  }
]


---


# קוד המקור — צ׳אט כשר 1.2.1-beta

הקובץ `kosher-chat-source.zip` מכיל את קוד המקור המלא של גרסת הבטא, כולל מנוע llama.cpp, רישיונות, בדיקות ומתכוני הכנת המודל. הוא אינו מכיל מפתחות חתימה פרטיים או משקלי מודל.

[הורדת ארכיון המקור המלא](https://github.com/mh0774020798-droid/kosher-chat/releases/download/v1.2.1-beta/kosher-chat-source.zip)

גודל: 17,162,159 בתים; 3,839 קבצים בארכיון.
SHA-256: `2b4261ed0328bf709f21ff712e9297ffd974ce9a822eb54d5d258068e96a75b9`.

לאחר שכפול המאגר:

```bash
unzip source/kosher-chat-source.zip -d work
cd work/kosher-chat
```

הוראות הבנייה המפורטות נמצאות ב־README.md שבתוך הארכיון. הבנייה דורשת JDK 17, Android SDK 35, NDK 27.2.12479018 ו־Gradle 8.9. לבניית APK Full נדרש גם מודל GGUF התואם לזהות המוצמדת בקוד. להפצת עדכון רשמי נדרשת חתימת הבעלים שנשמרת מחוץ למקור הציבורי.

דוח הבדיקות בתוך הארכיון: `docs/VALIDATION-1.2.1-beta.md`. מתכוני המודל: `docs/experiments/alternative-models/`.

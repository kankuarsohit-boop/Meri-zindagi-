MeriZindagi Android starter project

यह एक शुरुआती native Android ऐप है, वेबसाइट नहीं।

शामिल सुविधाएँ:
- बिल / EMI एंट्री
- दस्तावेज़ की तारीख
- परिवार के काम
- जानकारी मोबाइल में सेव
- रोज़ सुबह 9 बजे रिमाइंडर शेड्यूल
- Android notification permission और exact alarm access के लिए विकल्प

महत्वपूर्ण:
- यह शुरुआती संस्करण डेटा केवल इसी मोबाइल में सेव करता है।
- रिमाइंडर Android की alarm/notification permissions और डिवाइस की battery settings पर निर्भर करते हैं।
- अभी इसमें login, cloud sync, payment, premium subscription या Play Store signing शामिल नहीं है।
- Play Store पर डालने से पहले release signing, privacy policy, testing और Play Console की प्रक्रिया पूरी करनी होगी।

GitHub Actions build:
1. इस ZIP को GitHub repository के root में MeriZindagi-Android-Source.zip नाम से upload करें।
2. README के साथ दिए गए build workflow को .github/workflows/build-android.yml में बनाएँ।
3. Actions tab में build पूरा होने पर app-debug.apk artifact डाउनलोड करें।

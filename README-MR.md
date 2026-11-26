# CIE INDIA Attendance – Android APK Project

या प्रोजेक्टमध्ये Android अ‍ॅपचा source code आहे. या वातावरणात Android SDK/Gradle build उपलब्ध नसल्यामुळे थेट install करता येणारी APK फाईल तयार करता आलेली नाही.

## APK कशी तयार करायची (मोफत)
1. हा ZIP GitHub वर नवीन repository मध्ये upload करा.
2. GitHub repository मधील **Actions** tab उघडा.
3. **Build Android APK** workflow निवडा आणि **Run workflow** दाबा.
4. Build पूर्ण झाल्यावर workflow run च्या Artifacts मधून `CIE-India-Attendance-APK` डाउनलोड करा.
5. ZIP extract करून `app-debug.apk` Android फोनवर उघडा आणि install करा. Android ने विचारल्यास त्या स्रोतावरून app install करण्याची परवानगी द्या.

## अ‍ॅपमधील दर
- प्रत्येक हजर दिवस: ₹671
- प्रत्येक 8 तास OT: ₹1,230
- एकाच तारीख + शिफ्टची नोंद पुन्हा सेव्ह केल्यास आधीची नोंद update होते.

## महत्त्वाचे
- हजेरी manually नोंदवावी लागते. CIE India ची अधिकृत attendance प्रणालीशी जोडणी नाही.
- डेटा फोनवरील अ‍ॅपमध्येच साठवला जातो. फोन बदलण्यापूर्वी CSV रिपोर्ट export करा.
- पगार हा दिलेल्या दरांवर आधारित अंदाज आहे; प्रत्यक्ष payroll मध्ये इतर नियम/कपाती असू शकतात.

RCMS OFFLINE ANDROID PROJECT

यह Android Studio / GitHub Actions के लिए source project है।

विशेषताएँ:
- Offline dashboard
- Component, Material, HRPT, Panel, AM-12, Maintenance, Inspection, Water Bill, Soap/Duster forms
- मोबाइल पर local storage में records save/edit/delete
- Component search
- JSON Backup/Restore

सीमाएँ:
- यह अभी prototype है; आपके पुराने PHP/MySQL database का data इसमें import नहीं है।
- MySQL SQL dump को सीधे Android में चलाया नहीं जा सकता; बाद में SQLite import/conversion बनानी होगी।
- APK इस ZIP में नहीं है। GitHub Actions सफल होने पर Actions > latest run > Artifacts से APK डाउनलोड करें।

GitHub upload: ZIP को extract करें और अंदर की सभी फाइलें/folders repository root में सही structure के साथ upload करें। ZIP file को अकेले repository में डालने से build trigger नहीं होगा।

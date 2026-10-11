Messi vs Ronaldo - Screenshot-style Android APK project

এই APK প্রজেক্টে আপনার দেখানো স্ক্রিনশটের penalty game-এর মূল index.html ব্যবহার করা হয়েছে (অন্য ডিজাইনের demo page নয়)।

Android ফোন থেকে GitHub দিয়ে APK বানানো:
1) ZIP extract করুন।
2) GitHub-এ নতুন repository তৈরি করুন।
3) ZIP-এর ভিতরের সব ফাইল ও ফোল্ডার repository-র root-এ upload করুন; .github/workflows/build-apk.yml-ও থাকতে হবে।
4) Commit changes করুন।
5) Actions tab-এ গিয়ে “Build Messi Ronaldo APK” workflow সফল হওয়া পর্যন্ত অপেক্ষা করুন।
6) Workflow run খুলে Artifacts থেকে “Messi-Ronaldo-APK” ডাউনলোড করুন।
7) Artifact ZIP extract করে app-debug.apk ইনস্টল করুন।

দ্রষ্টব্য: এটি পরীক্ষা করার জন্য debug APK। ভয়েস Android WebView/device speech synthesis-এর উপর নির্ভরশীল; এটি Messi/Ronaldo-র আসল রেকর্ড করা কণ্ঠ নয়। Google Fonts লোড করতে ইন্টারনেট লাগতে পারে; মূল গেম লোকালি খোলার জন্য ইন্টারনেট আবশ্যক নয়।

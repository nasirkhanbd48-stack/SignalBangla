Signal Bangla — Android Studio project

এই ZIP-টি Android Studio project source; এটি নিজে থেকে APK নয়।

APK বানানোর ধাপ:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. ZIP extract করুন।
3. Android Studio-তে extracted SignalBanglaAndroid ফোল্ডার Open করুন।
4. Gradle sync শেষ হতে দিন; প্রয়োজন হলে Android SDK Platform 35 ইনস্টল করুন।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
6. সফল হলে app/build/outputs/apk/debug/app-debug.apk ফাইলটি ফোনে কপি করে ইনস্টল করুন।

লাইভ API:
অ্যাপের ভেতরে থাকা HTML-এর Live Data সেটিংস থেকে Twelve Data API key দিতে হয়।
API key শেয়ার করবেন না। ব্রাউজার/ওয়েবভিউ থেকে API request provider-এর CORS বা plan limit-এ ব্যর্থ হতে পারে।
নিরাপদ production সংস্করণে API key server-side রাখা উচিত।

সতর্কতা:
অ্যাপটি শুধু চার্ট ও সম্ভাব্য CALL/PUT/WAIT সংকেত দেখানোর শিক্ষামূলক টুল।
কোনো ব্রোকারে অর্ডার পাঠায় না; লাভ নিশ্চিত করে না।

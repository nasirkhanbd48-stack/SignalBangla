Signal Bangla APK — মোবাইল থেকে ক্লাউড বিল্ড

গুরুত্বপূর্ণ: এই ZIP নিজে APK নয়। GitHub-এর বিনামূল্যের Actions দিয়ে APK বানাতে নিচের ধাপগুলো একবার করতে হবে। GitHub অ্যাকাউন্ট লাগবে।

১) Chrome-এ https://github.com খুলে/লগইন করে একটি নতুন repository তৈরি করুন। নাম দিন SignalBanglaAndroid। Public বা Private যেকোনোটি বেছে নিন।
২) repository-তে Add file > Upload files চাপুন। এই ZIP-টি আগে ফোনে Extract করুন, তারপর Extract করা ফোল্ডারের ভেতরের সব ফাইল ও ফোল্ডার আপলোড করুন। ZIP ফাইলটিকে সরাসরি আপলোড করবেন না। .github ফোল্ডারটিও অবশ্যই আপলোড করতে হবে।
৩) Commit changes চাপুন। এরপর উপরের Actions ট্যাব খুলুন।
৪) “Build Signal Bangla APK” workflow নির্বাচন করে Run workflow চাপুন।
৫) কাজ শেষ হলে build run খুলুন; Artifacts অংশে SignalBangla-debug-apk নামের ফাইল ডাউনলোড করুন। ZIP খুলে app-debug.apk বের করুন।
৬) APK-তে চাপ দিয়ে ইনস্টল করুন। Android চাইলে এই উৎস থেকে অ্যাপ ইনস্টলের অনুমতি দিতে হবে। কাজ শেষে নিরাপত্তার জন্য অনুমতি বন্ধ করে দিন।

নোট:
- প্রথম বিল্ডে কয়েক মিনিট লাগতে পারে। Build failed দেখালে APK তৈরি হয়নি।
- এটি debug/test APK; Play Store release build নয়।
- Signal-গুলো সম্ভাব্যতা-ভিত্তিক ইঙ্গিত, নিশ্চিত লাভ নয়। শুরুতে ডেমো/টেস্ট মোডে ব্যবহার করুন। কোনো স্বয়ংক্রিয় ট্রেডিং নেই।

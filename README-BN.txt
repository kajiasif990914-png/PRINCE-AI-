PRINCE AI - Starter Prototype

এই ZIP-এ একটি মোবাইল-ফ্রেন্ডলি PWA ওয়েবসাইটের প্রাথমিক কাঠামো আছে।

যা কাজ করে:
- বাংলা, English ও Hindi UI ভাষা পরিবর্তন
- মোবাইল-ফ্রেন্ডলি ড্যাশবোর্ড
- টাস্ক তালিকায় কাজ যোগ করা (বর্তমানে শুধু এই সেশনে)
- ব্রাউজার সমর্থন করলে Speech Recognition ডেমো
- PWA manifest ও service worker

গুরুত্বপূর্ণ সীমাবদ্ধতা:
- এটি এখনো সম্পূর্ণ AI Agent নয়।
- AI API, লগইন, ক্লাউড ডেটাবেস, WhatsApp/Instagram সংযোগ এবং ব্যাকএন্ড যুক্ত করা হয়নি।
- Chat এখন ডেমো উত্তর দেয়; কোনো বার্তা AI সার্ভারে পাঠায় না।
- API key কখনো index.html-এ প্রকাশ্যে রাখবেন না। নিরাপদ server/backend দিয়ে যুক্ত করতে হবে।

মোবাইল থেকে পরের ধাপ:
1. ZIP ফাইলটি ডাউনলোড ও Extract করুন।
2. GitHub-এ একটি নতুন Public repository তৈরি করুন।
3. Extract করা ফাইলগুলো repository-তে আপলোড করুন।
4. Repository Settings > Pages > Deploy from a branch > main / root নির্বাচন করে Save করুন।
5. প্রকাশিত HTTPS ওয়েবসাইট Android Chrome-এ খুলে মেনু থেকে Add to Home screen নির্বাচন করুন।

PWA ইনস্টলেশনের জন্য HTTPS hosting প্রয়োজন। GitHub Pages দিয়ে static prototype প্রকাশ করা যায়। লাইভ AI করতে পরে নিরাপদ backend/API integration লাগবে।

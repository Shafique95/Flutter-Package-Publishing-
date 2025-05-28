 Namecheap ব্যবহার করছেন, নিচে Google Search Console-এ আপনার `ba-systems.com` ডোমেইন ভেরিফাই করার জন্য **ধাপে ধাপে গাইড**:

---

## ✅ Step-by-step Guide: Namecheap ডোমেইন Google Search Console-এ ভেরিফাই করা

### 🔹 ধাপ ১: Google Search Console-এ ডোমেইন যুক্ত করা

1. যান: [Google Search Console](https://search.google.com/search-console)
2. “**Start now**” এ ক্লিক করুন (Google অ্যাকাউন্টে সাইন ইন করুন)
3. **Property Type** থেকে **“Domain”** নির্বাচন করুন
4. `ba-systems.com` লিখুন (https\:// ছাড়া)
5. “**Continue**” চাপুন
6. এরপর আপনি পাবেন একটি **TXT রেকর্ড**, দেখতে হবে এরকম:

   ```
   TXT record:  
   google-site-verification=xxxxxxxxxxxxxxxx
   ```

এই রেকর্ডটি আপনাকে Namecheap-এর DNS-এ যোগ করতে হবে।

---

### 🔹 ধাপ ২: Namecheap-এ DNS এ গিয়ে TXT রেকর্ড যুক্ত করা

1. যান: [https://ap.www.namecheap.com/](https://ap.www.namecheap.com/) এবং সাইন ইন করুন

2. উপরে মেনু থেকে “**Domain List**” এ যান

3. `ba-systems.com` ডোমেইনের পাশে “**Manage**” বাটনে ক্লিক করুন

4. ট্যাব থেকে “**Advanced DNS**” এ যান

5. নিচে গিয়ে **"Host Records"** সেকশনে ক্লিক করুন

6. “**Add New Record**” চাপুন

   এখানে নিচের তথ্যগুলো দিন:

   | Type | Host | Value                                                                            | TTL       |
   | ---- | ---- | -------------------------------------------------------------------------------- | --------- |
   | TXT  | @    | `google-site-verification=xxxxxxxxx` ← যেটা আপনি Google Search Console-এ পেয়েছেন | Automatic |

7. “✅ Save” দিন

---

### 🔹 ধাপ ৩: Google Search Console-এ যাচাই শেষ করা

1. এখন আবার যান Google Search Console-এ
2. “**Verify**” বাটনে ক্লিক করুন
3. যদি ঠিকভাবে রেকর্ড যুক্ত করে থাকেন, তাহলে কিছুক্ষণের মধ্যে ভেরিফাই হয়ে যাবে

⏱️ *অনেক সময় DNS পরিবর্তন কার্যকর হতে 5 মিনিট থেকে 1 ঘণ্টা পর্যন্ত লাগতে পারে।*

---

### 🎉 ভেরিফিকেশন সফল হলে

আপনি এখন pub.dev-এ গিয়ে আপনার `ba-systems.com` দিয়ে Verified Publisher তৈরি করতে পারবেন:
👉 [https://pub.dev/publishers](https://pub.dev/publishers)



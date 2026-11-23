Mahmudul Howue Welfare Trust — Offline prototype v2

চালু:
1) ZIP Extract করুন।
2) index.html খুলুন। PWA install/service worker এবং ক্যামেরার জন্য HTTPS/localhost-এ serve করা ভালো।
3) উপকারভোগী ও কার্যক্রম যোগ করুন।

এই সংস্করণ:
- IndexedDB-তে স্থানীয় ডেটা
- ৫ মিনিট অন্তর একই ডিভাইসে স্থানীয় snapshot
- JSON export/import
- আলাদা কার্যক্রমভিত্তিক নির্বাচন ও বিতরণ রেকর্ড
- ID দিয়ে যাচাই; BarcodeDetector সমর্থিত ব্রাউজারে QR scan
- Print dialog থেকে Save as PDF

সীমাবদ্ধতা:
- QR কার্ড জেনারেটর এখনো অন্তর্ভুক্ত নয়; ID ম্যানুয়ালি যাচাই করা যায়।
- ২-৩ ফোনের মধ্যে ডেটা sync নেই। প্রতিটি ফোন আলাদা ডেটাবেস হবে।
- সম্পূর্ণ offline multi-device shared database করতে একটি local Wi-Fi/hotspot network ও LAN server লাগবে।
- local backup একই ডিভাইসেই থাকে; ফোন নষ্ট/ব্রাউজার ডেটা মুছে গেলে আলাদা JSON export প্রয়োজন।
- login/role permission, encryption, audit log, server-side duplicate lock এবং production security এখনো যোগ করতে হবে।
- NID/ব্যক্তিগত ছবি বাস্তব ব্যবহারের আগে নিরাপত্তা যাচাই ছাড়া সংরক্ষণ করবেন না।

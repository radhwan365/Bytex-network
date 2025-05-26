# إعداد اسم المستخدم والبريد الإلكتروني لحساب Git
git config --global user.name "Radhwan Majdoub"
git config --global user.email "radoinmajdoub@gmail.com"

# فك ضغط الملف
unzip BytexNetwork.zip
cd BytexNetwork

# تهيئة مستودع Git جديد
git init

# ربط المستودع المحلي بمستودع GitHub (تأكد من أن الرابط صحيح بدون نقطة في النهاية)
git remote add origin https://github.com/radhwan/bytex-network.git

# إضافة جميع الملفات
git add .

# عمل أول commit
git commit -m "Initial commit of Bytex blockchain by Radhwan Majdoub"

# دفع التغييرات إلى الفرع الرئيسي في GitHub
git branch -M main
git push -u origin main
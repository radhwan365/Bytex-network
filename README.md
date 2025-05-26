git config --global user.name "Radhwan Majdoub"
git config --global user.email "radoinmajdoub@gmail.com"  # استبدله ببريدك الحقيقي

# فك ضغط الحزمة أولًا
unzip BytexNetwork.zip
cd BytexNetwork

# تهيئة Git ورفع المشروع
git init
git remote add origin https://github.com/USERNAME/bytex-network.git  # ضع اسم حسابك بدل USERNAME
git add .
git commit -m "Initial commit of Bytex blockchain by Radhwan Majdoub"
git push -u origin master  # أو: git push -u origin main

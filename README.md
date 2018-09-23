# Bruteforce HTTP Authentication

تخمين يوزر وباسورد صفحات البوب
يدعم  

* Basic HTTP authentication
* Digest HTTP authentication
* NTLM authentication
يعمل بكافة الاشكال تقريبا ويستخدم قوائم ايبيهات دومينات  ببورت بدون برابط او بدون  يعمل اى بى واحد او مجموعة 
يستخدم يوزر واحد او مجموعة يوزرات او باسورد واحد او مجموعة ضخمة  يخزن النتائج فى ملف نصي


أمر التركيب 

pip install -r requirements.txt



أمر التشغيل
التجربة على هدف واحد
-w



python3 auth.py -T IPS.txt -U username.txt -P password.txt -w 30 --verbose



أوامر السكربت

 -t TARGET, --target TARGET
                        URL
                        
  -T TARGETFILE, --targetfile TARGETFILE
                        File of URL
                        
  -u USERNAME, --username USERNAME
                        Username ("username" or "username:password")
                        
  -U USERNAMESFILE, --usernamesfile USERNAMESFILE
                        File of usernames ("username" or "username:password")
                        
  -p PASSWORD, --password PASSWORD
                        Password
                        
  -P PASSWORDSFILE, --passwordsfile PASSWORDSFILE
                        File of passwords
                        
  -w WORKERS, --workers WORKERS
                        Number of threads (interger between 1 and 100)
                        
  -o ORDER, --order ORDER
                        Targets order ("serie" or "parallel")
                        
  -v, --verbose         Verbose

مع تحيات ابو كريم 


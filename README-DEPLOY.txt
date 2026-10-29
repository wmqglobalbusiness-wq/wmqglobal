WMQ GLOBAL LLC - Website Deploy Guide
======================================

Is zip me website deploy karne ke liye sab kuch maujood hai.
index.html ek self-contained file hai - logo aur photos uske andar
hi included hain, is liye koi alag image/CSS file ki zaroorat nahi.

DEPLOY KARNE KA TAREEQA (Vercel)
----------------------------------
1. Is zip ko unzip karo. Ek folder milega jis me index.html hai.
2. Vercel dashboard kholo (vercel.com) aur naya project banao.
   Folder ko drag-and-drop karke deploy karo, ya folder me terminal
   khol kar ye command chalao:
       npx vercel --prod
   Phir screen par aane wale steps follow karo.
3. Deploy complete hone par Vercel aapko live URL dega.

DOMAIN (baad me, jab domain khareed lo)
----------------------------------------
Vercel project > Settings > Domains me ja kar wmqglobal.com add karo
aur Vercel ki di hui DNS records apne domain registrar par lagao.

IMPORTANT NOTE - FORMS
----------------------
Is static website ke forms (Product Request, 3PL, Contact) server se
email nahi bhejte. Form bharne par visitor ke apne mail app me
wmqglobalbusiness@gmail.com par pehle se bhara hua email khul jata hai,
aur visitor ke Send dabane par hi email milta hai. Ye static file ki
limit hai, koi bug nahi hai.

Site: WMQ GLOBAL LLC
Email: wmqglobalbusiness@gmail.com
Address: Wyoming, USA
(c) 2026 WMQ GLOBAL LLC. All Rights Reserved.

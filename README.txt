موقع الشيخ يحيى الحجوري — نسخة أولية

النشر المجاني على GitHub Pages:
1) ارفع ملف index.html إلى المستودع abdulwahab-site في جذر المستودع.
2) افتح Settings في المستودع.
3) افتح Pages.
4) في Build and deployment اختر Deploy from a branch.
5) اختر Branch: main و Folder: /(root)، ثم Save.
6) انتظر ظهور رابط الموقع في صفحة Pages.

إضافة محاضرة:
- افتح index.html واضغط Edit.
- ابحث عن const VIDEOS = [
- أضف سطرًا مثل:
  { title: "عنوان المحاضرة", category: "محاضرة", url: "https://www.youtube.com/watch?v=VIDEO_ID" },
- استبدل VIDEO_ID بمعرّف الفيديو الصحيح، ثم Commit changes.

ملاحظات:
- هذه نسخة تصميم أولية وليست الموقع الرسمي المعتمد من الشيخ.
- أضف روابط يوتيوب الموثوقة فقط، وتحقق من الأذونات قبل إعادة نشر أي محتوى.

قناة يوتيوب المرتبطة: https://youtube.com/@sh.alhajury
ملاحظة: التحديث التلقائي لجميع الفيديوهات يتطلب إعدادًا إضافيًا عبر YouTube Data API أو معرّف قائمة الرفع.

تم تحديث الصفحة لتضمين مشغل يحاول عرض فيديوهات القناة داخل الموقع، مع رابط القناة. دعم listType=user_uploads قد يختلف؛ للتحديث الآلي الكامل داخل بطاقات، يلزم Channel ID / Uploads playlist ID أو YouTube Data API.

GALLERY TURKY — نسخة HTML + CSS + JavaScript

التشغيل:
افتحي index.html.

إضافة منتج:
افتحي js/products.js وأضيفي منتجًا داخل products:
{
 id:"BAG-025",
 name:"شنطة كروس",
 category:"bags",
 subcategory:"crossbody",
 price:550,
 image:"images/bag25.jpg",
 description:"وصف المنتج",
 stock:5,
 status:"available"
}

الحالات:
available + stock أكبر من 2 = متوفر
available + stock 1 أو 2 = متبقي X فقط
available + stock 0 = نفدت الكمية
coming-soon = ستصل قريبًا

تغيير صور المنتجات:
ضعي الصورة داخل images/ ثم عدلي image في products.js فقط.

بيانات التواصل كلها في js/store.js فقط.
التوصيل ثابت 130 جنيه كما تم تحديده.
لا يوجد React أو Backend أو Database أو Search.
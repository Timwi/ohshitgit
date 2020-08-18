---
tags: tip
title: <div class="rtl">אוי לעזאזל, עשיתי משהו ממש גרוע, בבקשה תגיד לי שלגיט יש מכונת זמן קסומה!?!</div>
id: מכונת-זמן-קסומה
order: 1
---
<div class="rtl">

```git
git reflog
# אתם תראו רשימה של כל הדברים
# אשר עשיתם, בכל הברנצ'ים השונים!
# לכל אחד מהם יש אינדקס - HEAD@{index}
# תמצא את האחד לפני ששברת הכל
git reset HEAD@{index}
# מכונת זמן קסומה.
```

אתה יכול להשתמש בזה כדי להחזיר דברים שמחקת בטעות, או רק כדי להסיר כמה דברים שניסית ששברו את הריפו, או לשחזר לאחר מרג' גרוע, או סתם כדי לחזור לתקופה בה הדברים באמת עבדו. אני משתמש הרבה ב`reflog`. תודה להרבה הרבה אנשים שהציעו להוסיף את זה!
</div>
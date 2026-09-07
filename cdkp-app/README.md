# CD KP Performance - APK Build

Yeh folder GitHub par upload karne ke liye ready hai. Upload karne ke baad
GitHub Actions khud APK bana dega — aapko kuch install karne ki zaroorat nahi.

## Steps (GitHub par upload)

1. GitHub.com par login karein, naya **empty** repository banayein
   (README/gitignore add na karein, blank rakhein).
2. Is poori folder ka content us repository mein push/upload kar dein
   (sab files aur folders sameet — `.github` folder bhi zaroor jaye,
   yeh hidden hota hai).
3. Upload hote hi **Actions** tab mein jayein — automatically ek
   build shuru ho jayega ("Build APK").
4. Build complete hone ke baad (2-4 minute), us run par click karein,
   neeche **Artifacts** section mein "CD-KP-Performance-APK" milega —
   yeh download karein, andar `app-debug.apk` hoga.
5. Yeh APK MediaFire ya kisi bhi cloud par upload kar ke link doston
   ko de sakte hain. Unhe phone settings mein "Unknown apps install"
   allow karna hoga (ek dafa).

## Important

- App offline kaam karti hai (data phone mein hi save hota hai).
- PNG/image export feature ke pehle use ke liye internet chahiye ho
  sakta hai (library download), uske baad woh bhi offline available
  rahegi jab tak app dobara install na ho.

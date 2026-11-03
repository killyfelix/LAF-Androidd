L.A.F — Aplikasyon Android (pwojè pou Android Studio)

Sa ki ladan l:
- Dènye fichye L.A.F la entegre nan aplikasyon an (li mache offline).
- Logo L.A.F itilize kòm ikòn aplikasyon an.
- WebView la aktive JavaScript ak DOM Storage pou done localStorage yo ka rete sou telefòn nan.
- Aplikasyon an gen aksè entènèt pou fonksyon senkronizasyon Google Apps Script la.

POU KONPILE APK A:
1. Enstale Android Studio sou yon òdinatè.
2. Louvri Android Studio, chwazi Open, epi chwazi dosye LAF_Android_Studio.
3. Kite Android Studio fini Gradle Sync la. Enstale Android SDK Platform 35 si li mande sa.
4. Chwazi Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Lè li fini, peze Locate. APK debug la ap nan app/build/outputs/apk/debug/app-debug.apk.
6. Voye APK sa sou telefòn Android la, ouvri li, epi otorize enstalasyon aplikasyon ki soti nan sous sa a si Android mande sa.

NÒT ENPÒTAN:
- Mwen prepare pwojè Android la, men mwen pa kapab pwodwi yon APK enstale dirèkteman nan anviwònman sa a paske Android SDK/Gradle build tools pa enstale isit la.
- Done localStorage yo rete sou aparèy kote yo antre a. Pou pataje done ant telefòn ak òdinatè, sèvi ak fonksyon senkronizasyon ki deja nan L.A.F.
- Pa efase done aplikasyon an ni dezenstale aplikasyon an san backup/senkronizasyon, paske sa ka efase done lokal telefòn nan.

KONPILASYON APK AK GITHUB
1. Kreye yon repository prive sou GitHub.
2. Upload tout sa ki anndan dosye LAF_Android_Studio a (pa upload ZIP la kòm yon sèl fichye).
3. Asire w dosye .github/workflows/build.yml la prezan nan rasin repository a.
4. Ale nan Actions > Build LAF Android APK > Run workflow.
5. Lè workflow la fini ak yon siy vèt, antre nan rezilta a epi telechaje Artifact ki rele LAF-Android-APK.
6. Louvri ZIP artifact la pou jwenn app-debug.apk, epi voye APK la sou telefòn Android ou.

Nòt: GitHub Actions bezwen aktive pou repository a. APK debug la se pou enstalasyon/tès; li pa yon APK Play Store siyen pou piblikasyon.

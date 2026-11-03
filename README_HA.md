# VIBRA EARN — Android starter project

Wannan ZIP ɗin **starter project** ne na Flutter don fara gina VIBRA EARN. Ba APK ba ne, kuma ba cikakken tsarin biyan kuɗi da backend da aka riga aka haɗa ba.

## Abubuwan da aka tanada a cikin demo
- Shafin bidiyo mai kama da short-video feed.
- Shafukan Register/Login (demo UI; ba a haɗa authentication na gaske ba).
- Upload video (UI placeholder).
- Wallet mai nuna ƙa'idar ₦50 ga valid view.
- Minimum withdrawal ₦25,000 da sanarwar lokacin da balance ya kai wannan adadi.
- Zaɓin yare da misalan Hausa/English.
- Withdrawal ta banki ko OPay/PalmPay (UI placeholder).
- Admin/backend checklist.

## Muhimmin bayani game da kuɗi
An sa ƙa'idar da ka zaɓa: **₦50 ga kowane valid view**, kuma user zai iya neman withdrawal idan balance ya kai **₦25,000**. Saboda haka ana buƙatar valid views 500 kafin ₦25,000.

Kada a biya bisa ga view da app ɗin waya kawai ya ƙirga. A production, server ne zai tantance valid views, ya hana bots/repeated views, ya adana ledger, sannan ya tabbatar da kuɗin da kamfani zai iya biya. ₦50/view babban alƙawarin kuɗi ne; a tabbatar da hanyar samun kuɗin shiga da iyakar kasafi kafin a kunna biyan kuɗi.

## Abubuwan da ake buƙata kafin a fitar da app
1. Sanya Flutter SDK da Android Studio.
2. Ƙirƙiri Firebase project, sannan a haɗa Android app da `flutterfire configure`.
3. Gina Firebase Authentication, Firestore, Storage da Cloud Functions bisa checklist a `docs/PRODUCTION_CHECKLIST.md`.
4. Gina admin dashboard mai kariyar admin role.
5. Haɗa payment provider/bank payout partner da API keys a server-side kawai. Kada a saka secret keys a cikin app.
6. Ƙara age/consent checks, content moderation, report/block, privacy policy da terms.
7. Gwada security rules da fraud controls kafin biyan kuɗi na gaske.

## Gudanar da demo
```bash
flutter pub get
flutter run
```

Wannan scaffold yana amfani da mock data; ba ya aika bidiyo ko kuɗi zuwa server.

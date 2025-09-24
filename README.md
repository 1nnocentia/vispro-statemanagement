## Ephemeral State
Pada Epehemeral, data di simpan dalam _widget level_ atau _temporary_ sehingga jika data ingin digunakan dalam widget lain, perlu dilakukan _multiple layer pass_ dan sebuah data dapat di _treat_ berbeda.
Sehingga karakteristik Ephemeral yaitu:
1. Single Widget
2. Widget Lifetime
3. Simple
4. Not Shareable
5. Test with widget
Bentuk ini cocok untuk _form validation_ maupun _animation_

## App State
Sebelum memulai, perlu menambahkan dependencies yaitu **scope_model: ^2.0.0**. Tetapi di App State ini bisa sharing data antar widget. App State bisa dibuat menjadi complex tergantung dari kebutuhan aplikasinya.
Karakteristik App State, yaitu:
1. Multiple widget or screen
2. App lifetime
3. Could be complex
4. Shareable
5. Unit test business logic
Bentuk ini cocok untuk _user authentication_, _shopping cart_, maupun _settings_ karena memerlukan kebutuhan yang sama untuk mengakses atau tampilan tiap lamannya.
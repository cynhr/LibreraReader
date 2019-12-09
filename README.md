![Logo](https://raw.githubusercontent.com/foobnix/LirbiReader/master/logo.jpg)


# Librera Reader

Librera Reader is an e-book reader for Android devices; 
it supports the following formats: PDF, EPUB, EPUB3, MOBI, DjVu, FB2, TXT, RTF, AZW, AZW3, HTML, CBZ, CBR, DOC, DOCX, and OPDS Catalogs

Web: [http://librera.mobi/](http://librera.mobi/)

FAQ: [Read](http://librera.mobi/wiki/faq/)

Android Play Market Apps:

[Librera](https://play.google.com/store/apps/details?id=com.foobnix.pdf.reader)

[Librera PRO](https://play.google.com/store/apps/details?id=com.foobnix.pro.pdf.reader)

Application Fonts (**fonts.zip** download to internal sd card, to [Downloads] folder)
[link](https://github.com/foobnix/LirbiReader/tree/master/Builder/fonts) 

[Telegram](https://t.me/LibreraReader)

[Telegram Download Beta apk](https://t.me/LibreraBeta)

[Beta .apk (latest build)](http://beta.librera.mobi)

## Required build libs

~~~~
mesa-common-dev libxcursor-dev libxrandr-dev libxinerama-dev libglu1-mesa-dev libxi-dev pkg-config
~~~~

## Librera Build on MuPdf 1.11 (Default)

~~~~
cd Builder
# Change the paths to mupdf and jniLibs folders
./link_to_mupdf_1.11.sh
cd ..
./gradlew assembleLibrera
~~~~

## Librera Build on MuPdf 1.16.1 (Optional, alpha)

~~~~
cd Builder
# Change the paths to mupdf and jniLibs folders
./link_to_mupdf_1.16.1.sh
cd ..
./gradlew assembleAlpha
~~~~

## Librera depends on:

MuPDF - (AGPL License) https://mupdf.com/downloads/archive/

* EbookDroid
* djvulibre
* hpx
* junrar
* Universal Image Loader
* libmobi
* commons-compress
* eventbus
* greendao
* jsoup
* juniversalchardet
* commons-compress
* okhttp3
* okhttp-digest
* okio
* rtfparserkit
* java-mammoth

Librera is distributed under the GPL

## License

See the [LICENSE](LICENSE.txt) file for license rights and limitations (GPL v.3).

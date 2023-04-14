# Google translate for desktop

Google translate PC desktop is the same Google translate but for Windows as desktop application.

Google Translate windows is a free multilingual neural machine translation service developed by Google, to translate text and websites from one language into another.

1.   It capable of:
     - Text translation: Translate between 108 languages by typing
     - Tap to Translate: Copy text in any app and tap the Google Translate icon to translate (all languages)
     - Offline: Translate with no internet connection (59 languages)
     - Instant camera translation: Translate text in images instantly by just pointing your camera (94 languages)
     - Photos: Take or import photos for higher quality translations (90 languages)
     - Conversations: Translate bilingual conversations on the fly (70 languages)
     - Handwriting: Draw text characters instead of typing (96 languages)
     - Phrasebook: Star and save translated words and phrases for future reference (all languages)
     - Cross-device syncing: Login to sync phrasebook between app and desktop
     - Transcribe: Continuously translate someone speaking a different language in near real-time (8 languages)

2.   Perks of having Google translate windows App:
     - An icon on your quick access spots
     - One-click launch
     - No need for an open browser tab

Google translate desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Desktop Translator App on your Windows platform Desktop or Laptop.

## Installation

You can download Google translate desktop for Windows by running the installer of latest [release](https://github.com/AppsForDesktop/Google-translate-desktop/releases/download/1.0.0/Google.translate.desktop.install.exe).

[Скачать](https://github.com/AppsForDesktop/Google-translate-desktop/releases/download/1.0.0/Google.translate.desktop.install.exe) Google переводчик

## Usage

Run the "Google.translate.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Google translate desktop\Google translate desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

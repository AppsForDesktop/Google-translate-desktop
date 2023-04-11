# Google translate for desktop

Google translate PC desktop is the same Google translate but for Windows as desktop application.

Google Translate is a free multilingual neural machine translation service developed by Google, to translate text and websites from one language into another.
Google Translate supports 109 languages at various levels and as of April 2016, claimed over 500 million total users, with more than 100 billion words translated daily.Launched in April 2006 as a statistical machine translation service, it used United Nations and European Parliament documents and transcripts to gather linguistic data. Rather than translating languages directly, it first translates text to English and then pivots to the target language in most of the language combinations it posits in its grid, with a few exceptions including Catalan-Spanish.

Perks of having Google translate windows App

An icon on your quick access spots

One-click launch

No need for an open browser tab

Google translate works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Desktop Translator App on your Windows platform Desktop or Laptop.

## Installation

You can download Google translate desktop for Windows by running the installer of latest [release](https://github.com/AppsForDesktop/Google-translate-desktop/releases/download/1.0.0/Google.translate.desktop.install.exe).

[Скачать](https://github.com/AppsForDesktop/Google-translate-desktop/releases/download/1.0.0/Google.translate.desktop.install.exe) Google переводчик

## Usage

Run the "Google.translate.desktop.install.exe" and follow installation instructions.

## For professionals

You can build whole application from source code. For that you will need:

Visual studio 2019 with support to build .NET Framework 4.6

If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Google translate desktop\Google translate desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

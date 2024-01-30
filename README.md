# My Time At Sandrock Translation Project

1. [Installation (English)](#english)
1. [Instalacja (Polski)](#polski)
1. [Want to help with translations?](#how-to-help-with-translations)

## English
1. Download latest translation file from "Releases" named after your language of choice (one with highest version number).
1. Copy downloaded translation file.
1. Open File Explorer and navigate to game folder appropriate for your operating system:
	1. For Windows start in "This Computer":
		> C:\\Program Files (x86)\Steam\steamapps\common\My Time At Sandrock\Sandrock_Data\StreamingAssets\AssetBundles\localization
	1. For Linux:
		1. For Native Steam installation:
		> ~/.steam/steam/steamapps/common/My Time At Sandrock/Sandrock_Data/StreamingAssets/AssetBundles/localization
		1. For Flatpak installation:
		> ~/.var/app/com.valvesoftware.Steam/data/Steam/steamapps/common/My Time at Sandrock/Sandrock_Data/StreamingAssets/AssetBundles/localization
1. Rename file named "thailand" for backup, for example to: "thailand backup". You can delete it instead but it is not recommended!
1. Paste your translation file and change it's name to "thailand".
1. Run My Time At Sandrock as usual.
1. Go to "Options" then "Language" and change "English" to "ภาษาไทย".
1. Click "Apply" and enjoy your translated My Time At Sandrock!
## Polski
1. Pobierz najnowsze wydanie o nazwie "polski" w zakładce "Releases" (wybierz to z najwyższym numerem wersji w nazwie)
1. Skopiuj pobrany plik "polski".
1. Otwórz Eksplorator Plików i przejdź do folderu z grą zależnie od twojego systemu operacyjnego:
	1. Dla Windows zacznij w "Ten Komputer":
		> C:\\Program Files (x86)\Steam\steamapps\common\My Time At Sandrock\Sandrock_Data\StreamingAssets\AssetBundles\localization
	1. Dla Linux:
		1. Domyślna instalacja systemowa:
		> ~/.steam/steam/steamapps/common/My Time At Sandrock/Sandrock_Data/StreamingAssets/AssetBundles/localization
		1. Instalacja z Flatpak'a:
		> ~/.var/app/com.valvesoftware.Steam/data/Steam/steamapps/common/My Time at Sandrock/Sandrock_Data/StreamingAssets/AssetBundles/localization
1. Zmień nazwę pliku "thailand" na nazwę zastępczą, na przykład na: "thailand kopia". Możesz go zamiast tego usunąć ale nie jest to zalecane!
1. Wklej plik "polski" i zmień jego nazwę na "thailand".
1. Uruchom My Time At Sandrock.
1. Przejdź do "Options" potem "Language" i zmień pierwsze wystąpienie "English" na "ภาษาไทย".
1. Naciśnij "Apply" i ciesz przetłumaczonym My Time At Sandrock!

## How to help with translations
### For starters
**I thank You very much for considering your selfless contribution to this free community translation project!**
### If you want to help with generating new translations
- In resources you can find link to my translation tool, use it to generate new machine translations.
- Include only JSON files in pull requests. 
- One JSON per pull request.
### If you want to help with translation quality
- Edit JSON file in this repository corresponding to language you're proficient in.
- JSON files are encoded in UTF-8.
- Make sure your translation does not exceed string size for eg:
	```json
		{
			"id": 1003,
			"size": 20,
			"text": "Potwierdź"
		},
	```
	"Potwierdź" contains 8 latin characters (1 byte each) and a polish specific character (2 bytes) so total size 10 is smaller then 20.
- [UTF-8 string size checker. Click here: https://mothereff.in/byte-counter](https://mothereff.in/byte-counter)
- One JSON file at a time (one pull request)
### Resources
- [See my translation tool to familiarize yourself with translation workflow. Click here: github.com/sladkkr/sandrock-translator](https://github.com/sladkkr/sandrock-translator)
- [UTF-8 string size checker. Click here: https://mothereff.in/byte-counter](https://mothereff.in/byte-counter)

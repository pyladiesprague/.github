# .github – společné soubory organizace PyLadies Prague

Tohle repo nastavuje profil organizace [pyladiesprague](https://github.com/pyladiesprague) a výchozí soubory pro všechny její repozitáře.

| Soubor | K čemu je |
| --- | --- |
| [`profile/README.md`](profile/README.md) | úvodní stránka organizace na GitHubu (česky) |
| [`profile/README.en.md`](profile/README.en.md) | anglická verze, odkazuje na ni callout v české verzi |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | jak nahlásit chybu nebo poslat opravu do materiálů |
| [`SUPPORT.md`](SUPPORT.md) | kam se obrátit pro pomoc s kurzem a úkoly |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | pravidla chování na kurzu, na Discordu i na GitHubu |
| [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE/) | formuláře pro nová issues a rozcestník pro dotazy |

## Jak výchozí soubory fungují

GitHub použije `CONTRIBUTING.md`, `SUPPORT.md`, `CODE_OF_CONDUCT.md` a šablony issues v každém repozitáři organizace, který nemá vlastní verzi. Když repo potřebuje něco jiného (například vlastní šablony issues), stačí do něj dát vlastní soubor a ten má přednost.

Obrázek v profilu je fotka z webu kurzu (stránka O nás), odkazuje se na ni absolutní adresou, protože profil se vykresluje na `github.com/pyladiesprague`, ne uvnitř tohoto repa.

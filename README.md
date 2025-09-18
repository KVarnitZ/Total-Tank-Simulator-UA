# Total-Tank-Simulator-UA
Українізатор TTS, який повноцінно додає мову як окрему (перекладено з англійської)
# Переклад триває
Я зайнявся перекладом цієї гри, бо просто хочу пограти в неї українською. Це мій перший переклад повністю в соло, тому йде повільніше, але я вивчаю цю тему як можу. Локалізація створюється таким чином, що розробник зможе її додати в гру використавши ctrl+c та ctrl+v.
# Як завантажити
Усе НЕЙМОВІРНО ПРОСТО!
- Вантажите мій [останній](https://github.com/KVarnitZ/Total-Tank-Simulator-UA/releases/latest/download/ПерекладTTS.zip) випуск.
- Відкриваєте локальні файли гри та закидуєте туди ```TotalTankSim_Data``` з заміною (замінюються тільки технічні файли).
- Гарно так тріпетесь!
# На даний момент такий прогрес:
en_US_Achievement.locale - не перекладено

- [ ] en_US_Battle.locale - не перекладено

- [ ] en_US_Battle2.locale - не перекладено

- [ ] en_US_Battle3.locale - не перекладено

- [ ] en_US_Battle4.locale - не перекладено

- [ ] en_US_Battle5.locale - не перекладено

- [ ] en_US_Battle6.locale - не перекладено

- [ ] en_US_campaign.locale - не перекладено

- [ ] en_US_campaign2.locale - не перекладено

- [ ] en_US_campaign3.locale - не перекладено

- [ ] en_US_CampaignMainMenu.locale - не перекладено

- [ ] en_US_Descriptions.locale - не перекладено

- [ ] en_US_DO_NOT_TRANSLATE.locale - напевно і не потрібно перекладати

- [ ] en_US_Epaulettes.locale - не перекладено

- [ ] en_US_keybinding.locale - не перекладено

- [ ] en_US_keybinding_2.locale - не перекладено

- [ ] en_US_keybinding_generated.locale - не перекладено

- [x] en_US_MainMenu.locale - **перекладено та перевірено**

- [x] en_US_MainMenu2.locale - **перекладено та перевірено**

- [x] en_US_MainMenu3.locale - **перекладено та перевірено**

- [x] en_US_MainMenu4.locale - **перекладено та перевірено**

- [x] en_US_options.locale - **перекладено та перевірено**

- [ ] en_US_test_generated.locale - **перекладено та <ins>НЕ</ins> перевірено**

- [ ] en_US_tutorial_texts.locale - **перекладено та <ins>НЕ</ins> перевірено**

- [ ] en_US_UnitDescriptions.locale - **перекладено та <ins>НЕ</ins> перевірено**
# Опис технічних файлів
## resources.assets
- Усередині файлу доданий ассет uk_UA - MonoBehaviour - Path ID/22140, який встановлює переміну 170 українській локалізації (бо найбільша в китайської, 160);
- Має бути ще додано вирішення з шрифтами.
## Totallytank.TMPro.dll
- Додана змінна в GameLocale uk_UA = 170, яка якраз таки береться самою локалізацією;
- Додане значення в GameLocaleExtensions української мови як ще однієї мови гри.

![Contribution guidelines for this project](/TTS2.png)

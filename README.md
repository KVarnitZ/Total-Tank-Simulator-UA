# Total Tank Simulator Ukrainian Localization
Українізатор TTS, який повноцінно додає мову як окрему (перекладено з англійської та польської). Також шрифт адаптований під українську.
# Про переклад
Я переклав цю гру, бо просто хочу пограти в неї українською. Розробники анонсували другу частину, тож я хочу, щоби перед виходом, можна було пограти в першу частину українською. Локалізація зроблена таким чином, що розробник зможе її додати в гру використавши ctrl+c та ctrl+v.

![Contribution guidelines for this project](/TTS2.png)
![Contribution guidelines for this project](/TTS3.png)
![Contribution guidelines for this project](/TTS4.png)
![Contribution guidelines for this project](/TTS5.png)
# Як завантажити
Усе НЕЙМОВІРНО ПРОСТО!
1. Вантажите мій [останній](https://github.com/KVarnitZ/Total-Tank-Simulator-UA/releases/latest/download/TTS_UA.zip) випуск.
2. Відкриваєте локальні файли гри та закидуєте туди ```TotalTankSim_Data``` з заміною (замінюються тільки технічні файли).
3. Змінюєте мову в налаштуваннях на українську.
4. Гарно так тріпетесь!
# Опис технічних файлів
## resources.assets
- Усередині файлу доданий ассет uk_UA - MonoBehaviour - Path ID/22140, який встановлює переміну 170 українській локалізації (бо найбільша в китайської, 160);
- Змінений шрифт, додані деякі літери та загалом адаптовано під українську мову.
## Totallytank.TMPro.dll
- Додана змінна в GameLocale uk_UA = 170, яка якраз таки береться самою локалізацією;
- Додане значення в GameLocaleExtensions української мови як ще однієї мови гри.

![Contribution guidelines for this project](/TTS.png)

# Голоси Півночі — релізи

Українська озвучка «Відьмака 3» (неофіційний фановий проєкт). Сайт: https://w3.in.ua

**Як поставити:** завантаж `UkrVoiceLauncher-<версія>-setup.exe` з останнього релізу і запусти. Лаунчер сам знайде
гру (Steam, GOG, Epic), поставить озвучку діалогів і українські відеоролики, увімкне українські субтитри і далі
оновлюватиме все сам. Озвучку й ролики можна вмикати окремо. Windows SmartScreen може попередити про невідомого
видавця: «Детальніше» → «Виконати в будь-якому разі».

Релізи з позначкою *pre-release* (`mod-0.9` тощо) — це файли мода, які завантажує лаунчер. Качати їх руками не треба.
Якщо дуже хочеться вручну: зібрати `plpc.w3speech` з частин
(`copy /b plpc.w3speech.001 + plpc.w3speech.002 + plpc.w3speech.003 plpc.w3speech`), покласти в
`Mods\modUkrVoice\content\` разом з `ua.w3strings`, файли `scripts__local__*.ws` — у
`Mods\modUkrVoice\content\scripts\local\` як `ukrvoice.ws`, `ukrvoice_config.ws`, `ukrvoice_text.ws`;
ролики: `blob0.bundle` з частин і `metadata.store` у `Mods\modUkrVoiceVideo\content\`.
У налаштуваннях гри: мова озвучки — польська, мова тексту — українська.

Код пайплайна не публікується.

---

# Voices of the North — releases

Unofficial Ukrainian voice-over for The Witcher 3. Site: https://w3.in.ua. Download the launcher from the latest
release; it finds the game, installs and updates the voice-over and the cutscene videos. Pre-releases hold the mod
files the launcher downloads.

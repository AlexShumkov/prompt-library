# Пример входа 1 — урок LMS со свёрнутой теорией

```
source:        https://university.zerocoder.ru/pl/teach/control/lesson/view?id=<id>
content_root:  auto
include:       all
exclude:       навигация, поиск, формы обратной связи, комментарии, футер, style, script
output_path:   PEd01_kak-masshtabirovat-prompt.md
output_format: md
audience:      студент курса без доступа к странице
language:      ru
mode:          production
```

Почему вход нетривиальный: теория лежит в 7 свёрнутых `<details>`, внутри контентных
блоков вшиты `<style>`, видео вставлены подписанными URL плеера, а блок задания
продублирован виджетом.

Ожидаемое поведение: все заголовки разделов на месте, свёрнутое раскрыто, медиа помечены
счётчиком, ни одной строки CSS, покрытие текста не ниже 90%.

# parse-sb3-blocks
**parse-sb3-blocks** парсит Scratch 3.0 блоки, и конвертирует их в [scratchblocks](https://github.com/scratchblocks/scratchblocks) формат.

Этот форк необходим для того, чтобы парсить проекты в которых есть нестандратные Scratch-блоки.

Если у блока нет перевода, обязательно нужно указать ключ `noTranslation: true`.

## Как получить билд библиотеки?

Нужно запустить следующую команду

```bash
npm run build
```
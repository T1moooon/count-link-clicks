# Обрезка ссылок с помощью VK
Это скрипт для получения сокращенной ссылки из обычной. И просмотра количества переходов по ссылке, если введут уже сокращенную ссылку.
### Как установить
Python3 должен быть уже установлен. Затем используйте pip (или pip3, есть конфликт с Python2) для установки зависимостей:
```bash
pip install -r requirements.txt
```
Для использования скрипта вам нужен 'Сервисный токен приложения', как его получить, можете посмотреть в [документации](https://id.vk.com/about/business/go/docs/ru/vkid/latest/vk-id/connection/tokens/service-token). Его нужно будет поместить в файл `.env`. Будет вглядить примерно так `VK_TOKEN="Сервисный токен приложения"`. 
### Как запустить
1. Откройте терминал или командную строку.
2. Откройте папку в которой лежит скрипт
3. Запустите файл `main.py`, и добавьте ссылку для сокращения или сокращённую ссылку.
```bash
python3 main.py https://dvmn.org/
```
- После запуска скрипт запросит ввод ссылки.
1. Если введена обычная ссылка, она будет сокращена.
2. Если введена уже сокращённая ссылка, вы получите статистику переходов по ней.
### Цель проекта
 Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).

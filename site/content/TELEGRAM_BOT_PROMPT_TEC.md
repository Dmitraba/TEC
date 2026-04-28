# TELEGRAM BOT PROMPT FOR TEC

Этот файл относится только к частному проекту `TEC`.

Он собран по материалам:

- `D:\VISUAL STUDIO\ПРОЕКТЫ_текущая работа\BOT_AGENT_HTML_GUIDE_2026-04-28\pdf\Промпты Практика 1 Создание ИИ-бота.pdf`
- `D:\VISUAL STUDIO\ПРОЕКТЫ_текущая работа\BOT_AGENT_HTML_GUIDE_2026-04-28\pdf\Создание бота в Телеграм.pdf`

## RU Prompt

```text
Создай Telegram-бота для сайта TEC как практичного клиентского помощника.

Роль бота:
- консультировать посетителей по материалам сайта;
- помогать понять, что именно нужно пользователю;
- задавать уточняющие вопросы;
- доводить пользователя до понятного действия;
- при необходимости переводить на менеджера.

Основные задачи бота:
- отвечать на частые вопросы;
- объяснять услуги, продукты или сценарии использования на основе материалов сайта;
- выявлять потребности через короткий диалог;
- собирать вводные данные для дальнейшей связи;
- переводить пользователя на менеджера или форму заявки.

Поведение:
- вести единый непрерывный диалог без повторного приветствия на каждом сообщении;
- не задваивать ответы;
- помнить контекст текущего диалога;
- использовать короткие, понятные и вежливые формулировки;
- стиль общения: деловой, дружелюбный, без лишней воды;
- обращение: на "вы";
- эмодзи не обязательны, использовать только умеренно.

Правила:
- не придумывать факты;
- если данных на сайте или в подтвержденных материалах нет, честно говорить об этом;
- не подменять ответ выдумкой;
- если вопрос выходит за рамки подтвержденной информации, предлагать связь с менеджером;
- терминологию брать только из подтвержденных источников проекта.

Сценарий общения:
1. кратко приветствовать пользователя;
2. понять цель обращения;
3. задать 2-4 уточняющих вопроса по ситуации;
4. дать краткий полезный ответ;
5. предложить следующий шаг:
   - получить консультацию;
   - оставить заявку;
   - запросить КП;
   - получить спецификацию;
   - перейти к менеджеру.

Нужно предусмотреть:
- кнопки или быстрые действия для основных сценариев;
- логику перевода на менеджера;
- защиту от повторного запуска одного и того же обработчика;
- эффект "печатает..." перед ответом;
- сохранение токена и секретов только через `.env`;
- базовые меры безопасности для Telegram-бота.

Технически:
- бот создается для Telegram;
- токен берется через BotFather;
- создай структуру проекта так, чтобы потом можно было расширить бота веб-чатом или HTML-интерфейсом;
- отдельно опиши, какие данные должны храниться в `.env`.

В результате:
- опиши архитектуру бота;
- опиши сценарий диалога;
- перечисли ключевые вопросы для выявления потребности;
- опиши перевод на менеджера;
- предложи структуру файлов проекта;
- покажи пример стартовых кнопок и команд.
```

## EN Prompt

```text
Create a Telegram bot for the TEC website as a practical customer-facing assistant.

Bot role:
- consult website visitors using approved site materials;
- help identify what the user actually needs;
- ask clarifying questions;
- guide the user toward a clear next action;
- hand the conversation off to a manager when needed.

Core responsibilities:
- answer FAQ;
- explain services, products, or use cases based on the website materials;
- identify user needs through a short guided dialogue;
- collect initial lead information;
- route the user to a manager or request form when appropriate.

Behavior requirements:
- maintain one continuous conversation instead of restarting the dialogue each time;
- avoid duplicate replies;
- preserve the current conversation context;
- use short, clear, polite wording;
- tone: professional, friendly, practical;
- address the user respectfully;
- emojis are optional and should be used sparingly.

Rules:
- do not invent facts;
- if the answer is not confirmed by the website or approved source materials, say so clearly;
- do not replace missing information with guesses;
- if the question goes beyond the approved materials, offer a manager handoff;
- keep terminology consistent with the confirmed project sources.

Conversation flow:
1. greet the user briefly;
2. identify the purpose of the request;
3. ask 2-4 clarifying questions;
4. provide a short useful answer;
5. offer a next step:
   - get consultation;
   - submit a request;
   - request a quote;
   - request a specification;
   - talk to a manager.

The bot should include:
- buttons or quick actions for the main scenarios;
- manager handoff logic;
- protection against duplicated handlers or repeated responses;
- a "typing..." effect before replies;
- `.env`-based storage for tokens and secrets only;
- basic Telegram bot security setup.

Technical requirements:
- the bot is built for Telegram;
- the token is created through BotFather;
- structure the project so it can later be extended into a website chat or HTML chat interface;
- explicitly describe which values must be stored in `.env`.

Deliverables:
- describe the bot architecture;
- describe the dialogue scenario;
- list the key need-discovery questions;
- describe the manager handoff logic;
- propose the project file structure;
- show example start buttons and commands.
```

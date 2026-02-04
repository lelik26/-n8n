# Различные примеры автоматизации процессов на платформе low-code | n8n |

## Сценарий A: бот в телеграмм с текстовым запросом и аудио запросом
### 🛠️ **Технологический стек**:
- 💻 **инфраструктура** | workflow n8n |
- 🌐 **ИИ** | OpenAI GPT 4.1 | embeeding OpenAI | Trascribe audio |
- 📄 **База Данных** | Google Drive | Google Sheet | Google Document | Pinecone |
- 📲 **Мессенджер**  | Telegram |


* Вариант бот отвечает на простые текстовые запросы
<img width="512" alt="Снимок экрана 2025-05-08 в 07 56 36" src="https://github.com/user-attachments/assets/ccd8fcce-e947-41dd-91bf-dd02867cc151" />

* Вариант бот отвечает на голосовые и текстовые запросы 

<img width="512" alt="Снимок экрана 2025-05-08 в 08 07 33" src="https://github.com/user-attachments/assets/5bff1b4a-bfa7-44aa-8ccf-052999c466d9" />

* Вариант подключаем чат бота к векторной базе знаний и бот отвечает на вопросы по документам (предварительно файлы размещаем в  папке Google Drive и скачиваем файлы в базу данных Pinecone)

- Пример работы чат бота
<img width="512" alt="Снимок экрана 2025-05-08 в 08 19 37" src="https://github.com/user-attachments/assets/4b9162a6-e437-44ce-80ee-8b8fefa990cf" />

- пример базы данных
<img width="512" alt="Снимок экрана 2025-05-08 в 08 17 50" src="https://github.com/user-attachments/assets/ee0bc0e6-7e29-436a-8dd9-ca6cd75298ff" />


- пример workflow 
<img width="512" alt="Снимок экрана 2025-05-08 в 08 12 25" src="https://github.com/user-attachments/assets/11215313-c6bd-48ed-a63f-bd44bddb8411" />

## Сценарий Б: бот в телеграмм формирование контента
Описание: бот в телеграмм формирование контента с заполнением простой формы n8n формирует темы для создания контента в Google Sheet и создания контента в Google Doc 

### 🛠️ **Технологический стек**:
- 💻 **инфраструктура** | workflow n8n |
- 🌐 **ИИ** | OpenAI GPT 4.1 
- 📄 **База Данных** | Google Drive | Google Sheet | Google Document |
- 📲 **Мессенджер**  | Telegram |

## Сценарий Б: личный ассистент бот в телеграмм
Описание: бот в телеграмм общение текстом или голосом по запросу назанчает событие в календаре и отправляет приглашение участникам , пишет письма пользователям которые есть в списке контактов в базе данных, по запросу ищет релевантную информацию в интернете, создает изображения , вычислять математические выражение с помощью калькулятора
### 🛠️ **Технологический стек**:
- 💻 **инфраструктура** | workflow n8n |
- 🌐 **ИИ** | OpenAI GPT 4.1 | Dalle-3| Tavily |
- 📄 **База Данных** | Google Drive | Google Sheet | Google Document | Baserow | Supabase | PostgreSQL |
- 📲 **Мессенджер**  | Telegram |

- Пример работы чат бота
<img width="512" alt="Снимок экрана 2025-05-08 в 08 33 08" src="https://github.com/user-attachments/assets/da391166-7d09-4af0-ab0d-16811cde556f" />
<img width="512" alt="Снимок экрана 2025-05-08 в 08 33 52" src="https://github.com/user-attachments/assets/8646ada8-125d-4be6-8a9d-eb595a95d547" />
<img width="512" alt="Снимок экрана 2025-05-08 в 08 34 58" src="https://github.com/user-attachments/assets/16bdec48-da68-4321-a9ee-7042fee53896" />

- 
## Список проектов

- [Home_Bot](./Home_Bot/README.md)
- [Анализ вакансий](./Analisys_Vacancy/analisys_vac.pdf)
- [Карьерный консультант](./Career_Consultant/сareer_consultant.pdf)]
- [Новостной парсер телеграм канала](./RSS_TG/parser_TG_canal.pdf)
- [Агент по объяснению кода](./Code_Bot/)
- [Персональный ментор](./Personal_Mentor_Bot/)
____________________________________________________________________________________________________________________________________________________________________________________________________
📫 **Давайте работать вместе!** → [![Telegram](https://img.shields.io/badge/Telegram-blue?logo=telegram&logoColor=white)](https://t.me/Aleks79Sib) | [Портфолио](https://github.com/lelik26)|[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:htclelik@gmail.com)

ЄСІКС
=====

    Тут представлені звіти активностей процесу виробництва ISO-9001 Єдиної Судової
    Інформаційно-комунікаційної Системи (ЄСІКС) або Unified Judicial Information
    Communication System (UJICS), яка складається з 10 томів.

Активності
----------

1) Аудит ЄСІКС (якшо знадобиться);
2) Бізнес-аналіз ЄСІКС згідно методології ISO 42010 і технічні вимоги;
3) Системнний-аналіз, технічне завдання і політики проєкту;
4) Референсна імплементація BPMN процесів "Судопису" і серверів всіх частин ЄСІКС на Elixir;
5) Система контролю якості.
6) Створення OpenAPI 3.0+ документації ЄСІКС.
7) Проєктне планування ЄСІКС (в цьому репозиторії).

Зміст
-----

* `okr` Цілі та ключові результати (метрики)
* `security` Модель профілів безпеки (безпека)
* `audit` Результати аудиту (аудит)
* `policy` Політики (політики)
* `requirement` Технічні вимоги (мотивація)
* `specification` Технічні завдання (специфікація)
* `implementation` Референсна імплементація (реалізація)
* `quality` Система контролю якості (верифікація)
* `documentation` Технічна документація (публікація)

Цілі і результати
-----------------

* [Цілі і результати](okr/okr.pdf)

Безпека
--------

* [Політики безпеки](https://ca.n2o.dev/priv/security-policy.pdf)
* [Галузевий профіль безпеки публічної і конфіденційної інформації](https://ca.n2o.dev/priv/legal_l2_court_profile.pdf)

Політики
--------

* [Політики](policy/policy.pdf)

Технічні вимоги
---------------

* [I. Iнфраструктурнi сервiси](requirement/foundations.pdf)
* [II. Господарська дiяльнiсть](requirement/accounting.pdf)
* [III. Документообiг](requirement/documents.pdf)
* [IV. Реєстри](requirement/registries.pdf)
* [V. Судопис](requirement/court.pdf)
* [VI. Суддiвство](requirement/judges.pdf)
* [VII. Iнтелектуальнi сервiси](requirement/awareness.pdf)
* [VIII. Бiзнес, аналiз i звiтнiсть](requirement/business.pdf)
* [IX. Інформаційно-пошукова система](requirement/portal.pdf)
* [X. Кабінет](requirement/cabonet.pdf)

Кодифікація компонент
---------------------

Субпродукти ЄСІКС, імена відповідають репозиторіям.

```basic
1 PKI EUDI ABAC IAM BPMN HL7 SCHEMA XFORMS
2 BUD FIN ACC CRM
3 DOCX XLSX PDF QR OCR S2T T2S CRDT
4 EXEC ORDER POSITION DIGER CITIZEN ESQ POSITION JUDGE BIZ TREMBITA
5 DEEDS PROSEC COURT AUTOCASE CART
6 JACC FILTER QUALIFY PROFILE VERRIFY
7 EXCERPT RECCOMEND PRACTICE ATTOURNEY ENTITIES
8 CAL TASK PAYMENT ARCHIVE COMMENTS VKZ JOURNALS
9 CMS
```

Credits
-------

* Вища Рада Правосуддя
* Державна Судова Адміністрація
* Інформаційні Судові Системи

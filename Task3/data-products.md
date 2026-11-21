# Дата продукты

| Data product | Домен | Основные данные | Владелец | Потребители |
|---|---|---|---|---|
| Customer 360 | Party / Customer Profile (BIAN: Party Data Management) | Клиент, сегмент, контакты, KYC-статус, согласия | Data Office / CRM-домен | CRM, BI, маркетинг, риск-менеджмент, контактный центр |
| Account & Lending 360 | Account & Lending (BIAN: Current Account, Consumer Loan) | Счета, кредиты, договоры, статусы, просрочка, история изменений | Core Banking / Риск-менеджмент | BI, финансовый департамент, регуляторная отчётность, риск-менеджмент |
| Payments & Transactions Stream | Payments (BIAN: Payment Execution) | Транзакции, платежи, статусы исполнения, AML-флаги | Финансовый департамент / Комплаенс | Антифрод, DWH/BI, регуляторная отчётность (AML) |
| Card Portfolio | Card (BIAN: Card Management) | Карты, карточные транзакции, тарифы карт, статусы | Карточный бизнес | BI, риск-менеджмент, антифрод, маркетинг (кэшбэк/лояльность) |
| Customer Servicing & Cases | Servicing (BIAN: Customer Case Management) | Обращения, темы, SLA, статусы, привязка к продукту | Контактный центр | BI, Product Management, риск-менеджмент (жалобы на мошенничество), Data Office |
| Product & Offer Catalog | Product Management / Sales & Marketing (BIAN Operational Domains «Product», «Sales & Marketing») | product_id, название продукта, категория, линейка, тарифы, условия, статусы (активен/архив), владелец продукта, правила назначения (кому можно предлагать) | Product Team + Core Banking Team (Product—бизнес‑правила, Core—техническая реализация и справочники) | CRM (подбор предложений), Cards, Loans, Marketing, BI (анализ продуктового портфеля), Naive UI (отображение доступных продуктов) |
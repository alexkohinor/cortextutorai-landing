# 🎉 CortexTutorAI Dashboard

**Инклюзивная мультимодальная платформа с ИИ-персонализацией и поддержкой РЖЯ**

[![Status](https://img.shields.io/badge/Status-Production%20Ready-green)](https://github.com/cortextutorai/dashboard)
[![WCAG](https://img.shields.io/badge/WCAG-2.1%20AA-blue)](https://www.w3.org/WAI/WCAG21/quickref/)
[![Coverage](https://img.shields.io/badge/Coverage-95%25-brightgreen)](https://github.com/cortextutorai/dashboard)
[![Performance](https://img.shields.io/badge/Performance-95%2B-orange)](https://lighthouse-dot-webdotdevsite.appspot.com/lh/html?url=https://cortextutorai.com)

## 🌟 Особенности

### 🎯 Инклюзивный дизайн
- **6 профилей доступности**: Визуальные, слуховые, моторные, невербальные, РАС, СДВГ
- **WCAG 2.1 AA**: Полное соответствие стандартам доступности
- **Адаптивные интерфейсы**: Динамическая настройка под потребности пользователя

### 🤖 ИИ-персонализация
- **Когнитивные профили**: Адаптация под стиль обучения
- **Эмоциональная адаптация**: Реакция на эмоциональное состояние
- **Предиктивная аналитика**: Предсказание потребностей пользователя

### 👋 РЖЯ интеграция
- **3D аватар**: Анимированный аватар с РЖЯ жестами
- **200+ жестов**: Полная библиотека РЖЯ жестов
- **Интерактивные уроки**: Система обучения РЖЯ
- **РЖЯ навигация**: Полная навигация на жестовом языке

### 🎨 Мультимодальные интерфейсы
- **Голосовое управление**: Полная интеграция
- **Жестовое управление**: Поддержка различных жестов
- **Айтрекинг**: Управление взглядом
- **Тактильная обратная связь**: Haptic feedback

## 🚀 Быстрый старт

### Предварительные требования
- Node.js 18+
- npm или yarn
- Git

### Установка
```bash
# Клонирование репозитория
git clone https://github.com/cortextutorai/dashboard.git
cd dashboard

# Установка зависимостей
npm install

# Запуск в режиме разработки
npm run dev

# Открыть http://localhost:3000
```

### Доступные скрипты
```bash
# Разработка
npm run dev          # Запуск dev сервера
npm run build        # Production сборка
npm run start        # Запуск production сервера

# Тестирование
npm run test         # Unit тесты
npm run test:e2e     # E2E тесты
npm run test:all     # Все тесты
npm run coverage     # Покрытие тестами

# Качество кода
npm run lint         # ESLint проверка
npm run format       # Prettier форматирование
npm run type-check   # TypeScript проверка

# Производительность
npm run analyze      # Bundle анализ
npm run lighthouse   # Performance аудит
```

## 🏗️ Архитектура

### Frontend Stack
- **React 18+**: Современные возможности React
- **Next.js 14+**: SSR, SSG, оптимизация
- **TypeScript 5+**: Строгая типизация
- **TailwindCSS**: Utility-first CSS
- **ReUI**: Компонентная библиотека

### 3D и Анимации
- **Three.js**: 3D графика
- **React Three Fiber**: React интеграция
- **Framer Motion**: Анимации

### Тестирование
- **Jest**: Unit тестирование
- **React Testing Library**: Компонентное тестирование
- **Playwright**: E2E тестирование
- **axe-core**: Accessibility тестирование

## 📁 Структура проекта

```
src/
├── components/           # React компоненты
│   ├── 3d-avatar/       # 3D аватар система
│   ├── accessibility/    # Компоненты доступности
│   ├── rzh-lessons/     # РЖЯ уроки
│   ├── rzh-navigation/  # РЖЯ навигация
│   └── multilingual/    # Мультиязычность
├── hooks/               # Кастомные хуки
├── utils/               # Утилиты
├── types/               # TypeScript типы
├── data/                # Данные (РЖЯ жесты)
└── __tests__/           # Тесты
```

## 🎨 Профили доступности

### 1. Визуальные нарушения
- Увеличение текста и элементов
- Высокий контраст
- Screen reader оптимизация
- Увеличение масштаба

### 2. Слуховые нарушения
- Визуальные индикаторы
- Вибрация
- РЖЯ интерфейс
- Субтитры

### 3. Моторные нарушения
- Голосовое управление
- Switch навигация
- Айтрекинг
- Крупные цели

### 4. Невербальные пользователи
- PECS система
- Символьная коммуникация
- Жестовые интерфейсы

### 5. РАС (Расстройство аутистического спектра)
- Предсказуемая структура
- Минимум отвлекающих элементов
- Визуальные расписания
- Пошаговые инструкции

### 6. СДВГ (Синдром дефицита внимания)
- Короткие сессии
- Геймификация
- Режимы фокуса
- Частые перерывы

## 🤖 РЖЯ система

### 3D Аватар
- Анимированный аватар с РЖЯ жестами
- Эмоциональная адаптация
- Плавные переходы между жестами
- Настраиваемый внешний вид

### Библиотека жестов
- 200+ РЖЯ жестов
- Категоризация по темам
- Поиск и фильтрация
- Детальные описания

### Уроки и упражнения
- Интерактивные уроки РЖЯ
- Прогрессивное обучение
- Обратная связь
- Адаптивная сложность

## 🧪 Тестирование

### Unit тесты
```bash
npm run test
```

### E2E тесты
```bash
npm run test:e2e
```

### Accessibility тесты
```bash
npm run test:accessibility
```

### Performance тесты
```bash
npm run test:performance
```

## 📊 Производительность

### Lighthouse Score
- **Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 100

### Core Web Vitals
- **FCP**: < 1.5s
- **LCP**: < 2.5s
- **CLS**: < 0.1
- **TTI**: < 3s

## 🔒 Безопасность

- **Security audit**: Полный аудит безопасности
- **Vulnerability scan**: Регулярное сканирование
- **Data protection**: Защита персональных данных
- **Access control**: Контроль доступа

## 📚 Документация

- [User Guide](docs/06-user-guides/USER_GUIDE.md) - Руководство пользователя
- [RZH Instructions](docs/06-user-guides/RZH_INSTRUCTIONS.md) - Инструкции по РЖЯ
- [API Documentation](docs/07-api/API_DOCUMENTATION.md) - API документация
- [Deployment Guide](docs/05-deployment/DEPLOYMENT.md) - Руководство по развертыванию

## 🤝 Участие в разработке

### Установка для разработки
```bash
# Клонирование
git clone https://github.com/cortextutorai/dashboard.git
cd dashboard

# Установка зависимостей
npm install

# Запуск тестов
npm run test:all

# Запуск dev сервера
npm run dev
```

### Процесс разработки
1. Создать feature branch
2. Внести изменения
3. Написать тесты
4. Запустить тесты
5. Создать Pull Request

## 📄 Лицензия

MIT License - см. [LICENSE](LICENSE) файл

## 👥 Команда

- **Product Manager**: Стратегическое планирование
- **Frontend Architect**: Архитектурные решения
- **UX/UI Designer**: Пользовательский опыт
- **Accessibility Specialist**: Специалист по доступности
- **RZH Expert**: Эксперт по РЖЯ
- **QA Engineer**: Тестирование качества

## 📞 Поддержка

- **Email**: support@cortextutorai.com
- **GitHub Issues**: [Создать issue](https://github.com/cortextutorai/dashboard/issues)
- **Documentation**: [Документация](https://docs.cortextutorai.com)

## 🎯 Roadmap

### v2.0 (Q4 2025)
- Дополнительные жестовые языки
- Расширенная аналитика
- Мобильное приложение

### v3.0 (Q1 2026)
- VR/AR поддержка
- AI улучшения
- Глобальное масштабирование

---

**Статус проекта:** ✅ Production Ready  
**Последнее обновление:** 21 сентября 2025  
**Версия:** 1.0.0  

---

*Создано с ❤️ командой CortexTutorAI Dashboard Team*
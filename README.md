# Website for Spectral Text

Минималистичный одностраничный сайт для приложения Spectral Text с профессиональной политикой конфиденциальности.

## Структура

- `index.html` - страница с политикой конфиденциальности, соответствующей требованиям GDPR, CCPA и другим законам о защите данных

## Варианты размещения (бесплатно)

### Вариант 1: GitHub Pages (рекомендуется)

1. Создайте новый репозиторий на GitHub (например, `spectraltext-website`)
2. Загрузите файл `index.html` в корень репозитория
3. В настройках репозитория включите GitHub Pages (Settings → Pages)
4. Выберите ветку `main` и папку `/root`
5. Ваш сайт будет доступен по адресу: `https://ваш-username.github.io/spectraltext-website/`

### Вариант 2: Netlify

1. Зарегистрируйтесь на [netlify.com](https://netlify.com)
2. Перетащите папку `website` в Netlify Drop
3. Получите бесплатный домен типа `spectraltext.netlify.app`
4. Опционально: подключите свой домен

### Вариант 3: Vercel

1. Зарегистрируйтесь на [vercel.com](https://vercel.com)
2. Установите Vercel CLI: `npm i -g vercel`
3. В папке `website` выполните: `vercel`
4. Следуйте инструкциям

### Вариант 4: Firebase Hosting

1. Установите Firebase CLI: `npm install -g firebase-tools`
2. Инициализируйте проект: `firebase init hosting`
3. Укажите папку `website` как public directory
4. Деплой: `firebase deploy`

## Что нужно обновить перед публикацией

1. **Ссылки на магазины приложений:**
   - Замените `https://apps.apple.com/app/spectral-text/idXXXXX` на реальную ссылку из App Store
   - Проверьте ссылку на Google Play

2. **Email адреса:**
   - Замените `greatlovefgy@gmail.com` и `legal@spectraltext.app` на реальные email адреса
   - Или создайте перенаправления на ваш основной email

3. **Домен (опционально):**
   - Если хотите использовать свой домен (например, `spectraltext.app`), настройте его в сервисе хостинга

## Использование в App Store Connect / Google Play

После публикации сайта используйте URL в:
- **App Store Connect**: App Information → Privacy Policy URL
- **Google Play Console**: Policy → Privacy Policy

Пример URL для GitHub Pages:
```
https://ваш-username.github.io/spectraltext-website/
```

Пример URL для Netlify:
```
https://spectraltext.netlify.app/
```

**Важно:** Используйте прямой URL без якорей (#), так как на странице находится только политика конфиденциальности.

## Обновление содержимого

Просто отредактируйте файл `index.html`, закоммитьте изменения в Git (если используете GitHub Pages) или загрузите заново в ваш хостинг.

**Обновление даты:** После внесения изменений обновите дату "Последнее обновление" в начале документа в JavaScript секции (строка в конце файла).


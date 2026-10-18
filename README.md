# CASE DROP

Симулятор кейсов: 40 кейсов, 56 скинов, апгрейд, инвентарь, 15 квестов, 12 классов.

## Играть

Открой `public/index.html` или GitLab Pages: `https://<username>.gitlab.io/casedrop/`

## Сборка APK

1. Залей проект в GitLab
2. Дождись пайплайна Pages (Build → Pipelines)
3. Открой ссылку Pages в PWABuilder (pwabuilder.com) → Android → Generate APK

## Структура

```
public/
  index.html      — игра
  manifest.json   — PWA-манифест
  sw.js           — service worker
  icon-192.png
  icon-512.png
.gitlab-ci.yml    — деплой на GitLab Pages
```

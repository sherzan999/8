# ИП Уколов С. В. — демо-сайт

> **Демо-версия.** Это прототип, а не официальный сайт организации. Он будет удалён по первой просьбе владельца. Данные и фото взяты из публичной карточки на Яндекс Картах (23.11.2026), права на них принадлежат владельцам.

- Организация: ИП Уколов С. В., Бобруйск, ул. Карла Либкнехта, 6
- Карточка: https://yandex.by/maps/-/CXc6qILB
- Дизайн: премиальный минимализм (светлая или тёмная тема, подстраивается под систему)
- Сайт: один файл `index.html`, чистые HTML/CSS/JS без сборки (только шрифт Inter с Google Fonts)
- Данные карточки: `data.json`; фото подгружаются ссылками с серверов Яндекса

## Публикация на GitHub Pages

```bash
git init && git add . && git commit -m "Демо-сайт ИП Уколов С. В."
git branch -M main
git remote add origin https://github.com/<user>/ip-ukolov.git
git push -u origin main
```

Затем: Settings → Pages → Deploy from a branch → `main` / `(root)`.
Адрес: `https://<user>.github.io/ip-ukolov/`

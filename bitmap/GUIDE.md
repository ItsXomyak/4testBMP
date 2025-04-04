# 🖼 Авто-тесты для Bitmap | Version 0.1

![Bitmap Tests](https://i.pinimg.com/originals/84/da/da/84dada0a5dcfd790700df3dd87897aef.gif)

---

## 📘 Руководство по использованию скрипта для Bitmap

### 🚀 Запуск тестов
Чтобы запустить все тесты, используйте:
```bash
bash script.sh
```
> **Не нужно** выдавать права или скачивать дополнительные файлы. Все необходимые BMP-файлы загружаются из GitHub.

---

## 📋 Список тестов
Для вывода всех тест-кейсов:
```bash
bash script.sh list
```

---

## ✅ Ожидаемые результаты
- ✅ <span style="color:lightgreen;">**PASS:**</span> Тест успешно пройден.
- ❌ <span style="color:red;">**FAIL:**</span> Ошибка в тесте. Проверьте программу и выполните тест вручную.
- 🛑 <span style="color:magenta;">**CRITICAL FAIL:** </span>Критическая ошибка или же panica. Перепроверьте тест-кейс и убедитесь в корректности программы.

---

## 🛠 Рекомендации при ошибках
Если вы получили **FAIL** или **CRITICAL FAIL**:
1. Перепроверьте тест вручную — возможно, ошибка в скрипте.
2. Убедитесь в корректности входных данных.
3. Сравните вывод программы с ожидаемым.
4. Используйте список тестов:
   ```bash
   bash script.sh list
   ```
5. При ошибках во всех тестах, возможно, некорректный билд:
   ```bash
   go build -o bitmap
   ```
6. **Важно!** Если `main.go` в другой директории, поместите скрипт туда же.

---

## 🧪 Пример теста

#### [<span style="color:magenta;">CRIT_FAIL</span>] Test - case 20: Unexpected result

Если тест не прошёл, выполните его вручную:

#### ./bitmap apply --filter=green sample.bmp sample-filtered-green.bmp


---

> 📬 **Идеи по улучшению? Свяжитесь со мной в Telegram:** [@scrameee](https://t.me/scrameee) | ```mromanul```


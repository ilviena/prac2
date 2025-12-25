# Практика №7
### Подготовка окружения
1. Создала папку с *Dockerfile* и *entrypoint.sh*, скрипты вставила из методички.

<img width="530" height="178" alt="image" src="https://github.com/user-attachments/assets/017f2d9a-64f2-45f0-b375-b77e2161a619" />

2. Собрала образ.

<img width="750" height="544" alt="image" src="https://github.com/user-attachments/assets/4d8c2c37-ea0e-4fa7-8a7c-bdffb93e9414" />

---

### Задание 1: Вывод логов в файл
1. Запустила контейнер.

<img width="940" height="75" alt="image" src="https://github.com/user-attachments/assets/0164fc96-39fe-4d83-b8fc-7d512f25309a" />


2. Проверила, что контейнер завершил работу.

<img width="940" height="121" alt="image" src="https://github.com/user-attachments/assets/4b5a567d-a0ec-43bf-97b3-3f760162eb8e" />


3. Сохранила логи в *tmp/container_logs.txt*, проверила содержимое, очистила.

<img width="940" height="566" alt="image" src="https://github.com/user-attachments/assets/b428e0c3-36d3-4446-ae68-0d14184e414d" />

---

### Задание 2: Проверка docker-stats
1. Запустила второй контейнер, параллельно открыла еще одну вкладку терминала для просмотра статистики в реальном времени.

<img width="940" height="181" alt="image" src="https://github.com/user-attachments/assets/c1188787-4508-47ae-ab41-21f9db036fa6" />

---

### Задание 3: Ограничение ресурсов
1. Запустила контейнер с ограничениями cpu и памяти, проверила статистику. Далее при работающем контейнере изменила ограничения, снова проверила статистику. Очистила.

<img width="940" height="348" alt="image" src="https://github.com/user-attachments/assets/f2179028-5ebe-47d3-9a46-41cafe4430a3" />

---

### Задание 4: Экспорт в tar
1. Запустила контейнер, подождала его завершения. Экспортировала контейнер в *tar*, проверила размер архива. Просмотрела содержимое.

<img width="940" height="639" alt="image" src="https://github.com/user-attachments/assets/07a0f30e-f9fd-43c7-94af-6bf0ec5759c8" />

---

### Задание 5: Импорт из tar
1. Загрузила образ из архива, проверила наличие образа.

<img width="940" height="86" alt="image" src="https://github.com/user-attachments/assets/501949c2-dbff-4782-ae64-6c0326b1d6d0" />

2. Запустила контейнер из загруженного образа, проверила его логи.

<img width="940" height="850" alt="image" src="https://github.com/user-attachments/assets/ad5aeabc-62ad-4bb5-be49-171e92cd4461" />

3. Очистила.

<img width="750" height="150" alt="image" src="https://github.com/user-attachments/assets/b0ec4fee-4ff9-4f67-9663-13e5f1829e79" />

---

# Вывод
В ходе практической работы были изучены дополнительные возможности *Docker* для управления жизненным циклом контейнеров, мониторинга их состояния и оптимизации использования системных ресурсов. 

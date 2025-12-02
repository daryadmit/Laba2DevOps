# Отчёт по лабораторной работе на тему "Автоматизация сборки и деплоя Python Docker-приложений через Jenkins с интеграцией GitHub"
---
## Введение
Цель данной лабораторной работы — освоить практические навыки автоматизации процесса непрерывной интеграции и развертывания (CI/CD) с использованием Jenkins — мощного инструмента автоматизации сборки, а также наладить взаимодействие с удалённым репозиторием GitHub посредством webhook, обеспечивающим мгновенный запуск сборки при каждом изменении кода.

В рамках работы создадим собственный Jenkins job, используя готовый Pipeline скрипт (Jenkinsfile), освоим управление параметрами сборки, настройку вебхуков для инициирования автоматических сборок, запустим тесты в изолированном Docker-контейнере и развернем приложение с учётом индивидуальных параметров (порт, имя студента).

---
## Практическая часть
Создали и настроили проект в jeenkins
<img width="1715" height="746" alt="image" src="https://github.com/user-attachments/assets/38ca5093-bf21-4072-b855-0d52cb899c34" />
<img width="1713" height="795" alt="image" src="https://github.com/user-attachments/assets/891da810-207e-4a13-bad4-28c0036cb14f" />
<img width="1715" height="846" alt="image" src="https://github.com/user-attachments/assets/67cccb13-bc0d-425c-9af9-c58e9a43e5c7" />
Настроили Webhooks в репозитории
<img width="990" height="286" alt="image" src="https://github.com/user-attachments/assets/6a1c5a0d-a818-4374-886c-60869f4036a1" />
Собрали проект
<img width="1364" height="906" alt="image" src="https://github.com/user-attachments/assets/93d73c6f-374c-46f9-853f-346e42c5410a" />
Результат
<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/20d648de-e214-486e-ad20-1118a422e497" />
[Результат лабы](http://158.160.194.244:8093/)

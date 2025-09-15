University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)  
Year: 2024/2025  
Group: U4225  
Author: Lunegov Egor Sergeevich  
Lab: Lab4   
Date of create: 15.09.2025  
Date of finished:  

*Этапы описания приложения*  
1. Начальная разработка
2. Тестирование партнерами
3. Продовое решение

**Начальная разработка**  
Этапы:  
1. Пользователь запускает модель
2. Модель разворачивается на Cloud Run
3. Данные сохраняются в Cloud Storage
4. Дополнительная информация — в Firestore
<img width="850" height="151" alt="image" src="https://github.com/user-attachments/assets/b33ef6f6-7c55-48d4-bbcf-bb9c95eeeaa5" /> 

Стоимость:  
<img width="844" height="355" alt="image" src="https://github.com/user-attachments/assets/b9c45a1b-4d15-406c-985b-9208c77346e3" />

Обоснование: 
- Cloud Run удобен для старта: масштабирование по требованию, нет затрат при простое
- Firestore легко интегрируется и не требует ручного управления
- Cloud Storage используется для хранения бинарных или медиафайлов

**Тестирование партнерами**  
На данном этапе разработки мы добавим отслеживание ошибок, а перед запуском Cloud Run'a используем Cloud Load Balancing для распределения нагрузки
<img width="804" height="211" alt="image" src="https://github.com/user-attachments/assets/cc0d4617-1f58-4404-8e60-db6567cea753" />

Стоимость:  
<img width="843" height="358" alt="image" src="https://github.com/user-attachments/assets/c791957d-b3e8-4d31-9833-0a1e1d906eae" />

Обоснование:
- Cloud Load Balancing позволяет распределить нагрузку между инстансами
- Cloud Monitoring необходим для анализа работы модели под нагрузкой

**Продовое решение**  
Этапы:  
1.

Стоимость:  
<img width="842" height="359" alt="image" src="https://github.com/user-attachments/assets/d5d90f23-d6e3-4519-90e0-97a230bd761a" />

Обоснование:


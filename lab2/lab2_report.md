University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)  
Year: 2024/2025  
Group: U4225  
Author: Lunegov Egor Sergeevich  
Lab: Lab2   
Date of create: 15.09.2025  
Date of finished:  

**Путь выполнения работы**
1. Я зашел внутри Google Cloud в Cloud Run, нажал "Deploy" и заполнил данные, нажав на базовый предлагаемый контейнер "hello". Все базовые настройки оставил в силе, только открыв публичный доступ (порт остался 8080).  
<img width="945" height="832" alt="image" src="https://github.com/user-attachments/assets/008c651a-9f8f-43fc-a458-f97bba803721" />

2. Я нажал на кнопку "Создать" и перешел по предоставленной ссылке:  
<img width="1471" height="544" alt="image" src="https://github.com/user-attachments/assets/98b4df75-25c9-4ce3-a6bc-c8543d99711b" />

3. Там я увидел такое окно, понял, что все сработало и вернулся в консоль:
<img width="970" height="809" alt="image" src="https://github.com/user-attachments/assets/e5f86d42-28b6-40b5-84b3-ac5c4d58cbe1" />  

4. Затем заглянул в логи и метрики (очень удобный функционал):  
<img width="1291" height="525" alt="image" src="https://github.com/user-attachments/assets/e5551390-ac31-4c04-8bd4-90e5743af634" />  
<img width="1653" height="988" alt="image" src="https://github.com/user-attachments/assets/217ba92c-0ce7-4c6c-b51c-2950cf23b2f7" />  

5. После этого поменял порт на 8090:  
<img width="922" height="785" alt="image" src="https://github.com/user-attachments/assets/c0999bb3-4057-4adf-b72e-94fd8e377b5d" />

6. Распределил пополам трафик:  
<img width="1019" height="303" alt="image" src="https://github.com/user-attachments/assets/63037326-f388-46af-b437-84428aa3328d" />  

7. Сравним логи и статистику:
- Во-первых, в логах отразилось изменение порта, а потом распределение трафа 50 на 50 (однако при изменении распределения на 20-80 и 80-20 я занчимых изменений не заметил)
 <img width="1181" height="434" alt="image" src="https://github.com/user-attachments/assets/317cbd85-2c3c-489e-82c8-24a258ac2328" />  
- Во-вторых, задержки в районе 10 мс
 <img width="1242" height="511" alt="image" src="https://github.com/user-attachments/assets/a1cb5622-3ab1-4522-8677-ed51c27d3a7b" />
- В-третьих, CPU 1%, а память 3-6%
 <img width="1239" height="520" alt="image" src="https://github.com/user-attachments/assets/4229dbca-b1cb-42da-8892-2530feef4710" />  

8. Все удалено по завершении работы.
<img width="999" height="517" alt="image" src="https://github.com/user-attachments/assets/eb5b4ea4-53b3-46c8-aef3-a92525b3fab7" />  



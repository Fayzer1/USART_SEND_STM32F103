# USART_SEND_STM32F103
Подпрограмма, реализующая отправку данных в асинхронном режиме через модуль USART2. В регистре R1 хранится указатель на начало отправляемой строки, признаком конца строки являются два подряд идущих непечатных символа 0x0D и 0x0A. 

### 2.	Алгоритм работы подпрограммы

<img width="290" height="1302" alt="image" src="https://github.com/user-attachments/assets/ed550f44-4170-4785-9b5d-c9003214ecb5" />

##### Необходимо передать строку «Knock! Knock!» по  USART2

Загрузка первого символа «K» в режиме отладки

<img width="847" height="97" alt="image" src="https://github.com/user-attachments/assets/96d67da9-0361-4e00-ad2c-ebd66eb70a52" />

Установка флага TC

<img width="509" height="142" alt="image" src="https://github.com/user-attachments/assets/3302f5b7-6538-4eea-bca7-d9eee1c7e666" />

Результат передачи первого символа

<img width="1015" height="337" alt="image" src="https://github.com/user-attachments/assets/f6fa1bb7-cfcd-46cc-a9a0-0a74e0ffb427" />

<img width="494" height="270" alt="image" src="https://github.com/user-attachments/assets/2c2fd809-8c19-4fd2-bd34-6e33a20ae529" />

Результат передачи первого слова

<img width="308" height="208" alt="image" src="https://github.com/user-attachments/assets/07830a6b-0a1f-4735-9312-fde7b8a7ead3" />

Результат передачи строки и символов конца строки

<img width="308" height="208" alt="image" src="https://github.com/user-attachments/assets/f5bea945-e549-4db7-b8fd-fdd10e15c67c" />




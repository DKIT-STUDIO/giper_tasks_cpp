## Четвёртая практическая

> [!NOTE]
> # Компиляция
> 
> ## ```g++ main.cpp -o main.exe```
> 

### 1 - 20
>Создайте базовый класс Shape с виртуальной функцией area(). Реализуйте производные классы Circle и Rectangle, которые выбрасывают исключение при некорректных параметрах (например, отрицательный радиус или стороны).
>
>Реализуйте класс Animal с виртуальной функцией speak(). Создайте классы Dog и Cat, которые выбрасывают исключение, если их имя пустое.
>
>Создайте класс BankAccount с виртуальной функцией withdraw(), которая выбрасывает исключение при недостаточном балансе. Реализуйте производные классы SavingsAccount и CheckingAccount.
>
>Напишите базовый класс FileHandler с виртуальной функцией open(), которая выбрасывает исключение, если файл не найден. Реализуйте классы TextFileHandler и BinaryFileHandler.
>
>Создайте класс Shape с виртуальной функцией draw(), которая выбрасывает исключение, если попытаться нарисовать фигуру с некорректными параметрами. Реализуйте классы Triangle и Square.
>
>Реализуйте класс Person с виртуальной функцией display(), которая выбрасывает исключение, если имя или возраст некорректны. Создайте производные классы Student и Teacher.
>
>Создайте класс Calculator с виртуальной функцией calculate(), которая выбрасывает исключение при делении на ноль. Реализуйте классы Addition и Division.
>
>Напишите базовый класс Game с виртуальной функцией start(), которая выбрасывает исключение, если игра не может начаться. Реализуйте классы Chess и Tennis.
>
>Создайте класс Document с виртуальной функцией save(), которая выбрасывает исключение, если не удается сохранить документ. Реализуйте классы PDFDocument и WordDocument.
>
>Реализуйте класс Matrix с виртуальной функцией getElement(), которая выбрасывает исключение при выходе за пределы матрицы. Создайте производные классы IntMatrix и FloatMatrix.
>
>Создайте класс Vehicle с виртуальной функцией fuelEfficiency(), которая выбрасывает исключение при некорректных данных. Реализуйте классы Car и Truck.
>
>Реализуйте класс User  с виртуальной функцией login(), которая выбрасывает исключение при неверном пароле. Создайте производные классы AdminUser  и RegularUser .
>
>Напишите базовый класс Shape с виртуальной функцией scale(), которая выбрасывает исключение при попытке масштабирования на отрицательное значение. Реализуйте классы Circle и Square.
>
>Создайте класс Library с виртуальной функцией borrowBook(), которая выбрасывает исключение, если книга недоступна. Реализуйте классы FictionLibrary и NonFictionLibrary.
>
>Реализуйте класс Order с виртуальной функцией process(), которая выбрасывает исключение при некорректных данных заказа. Создайте производные классы OnlineOrder и InStoreOrder.
>
>Создайте класс Shape с виртуальной функцией rotate(), которая выбрасывает исключение при некорректных углах. Реализуйте классы Triangle и Rectangle.
>
>Реализуйте класс Payment с виртуальной функцией processPayment(), которая выбрасывает исключение при недостаточном балансе. Создайте классы CreditCardPayment и PayPalPayment.
>
>Напишите базовый класс ExceptionHandler с виртуальной функцией handle(), которая выбрасывает исключение при некорректных данных. Реализуйте классы FileExceptionHandler и NetworkExceptionHandler.
>
>Создайте класс Course с виртуальной функцией enroll(), которая выбрасывает исключение при переполнении группы. Реализуйте классы OnlineCourse и OfflineCourse.
>
>Реализуйте класс ShoppingCart с виртуальной функцией checkout(), которая выбрасывает исключение при пустом корзине. Создайте классы RegularCart и DiscountedCart.
>
![image](https://github.com/user-attachments/assets/effc811c-388f-4e28-b7e3-5dbea5447a64)

### 21
>Создайте класс Shape с виртуальной функцией translate(), которая выбрасывает исключение при попытке перемещения фигуры на недопустимые координаты. Реализуйте классы Circle и Rectangle.

![image](https://github.com/user-attachments/assets/6a41ce2f-45b1-4922-b168-f9b2138498c5)

### 22
>Реализуйте класс Database с виртуальной функцией connect(), которая выбрасывает исключение при ошибке подключения. Создайте производные классы MySQLDatabase и SQLiteDatabase.

![image](https://github.com/user-attachments/assets/dc70f83a-c1d7-4fee-a418-72f7544d68e7)

### 23
>Создайте класс Task с виртуальной функцией execute(), которая выбрасывает исключение при попытке выполнения неинициализированной задачи. Реализуйте классы PrintTask и EmailTask.

![image](https://github.com/user-attachments/assets/5c866014-d833-4a95-b77c-d9c021e884c0)

### 24
>Напишите базовый класс Shape с виртуальной функцией getPerimeter(), которая выбрасывает исключение при некорректных параметрах. Реализуйте классы Triangle и Square.

![image](https://github.com/user-attachments/assets/660d5bfc-a01f-4621-a443-462dc3c9d03a)

### 25
>Реализуйте класс WeatherService с виртуальной функцией getForecast(), которая выбрасывает исключение при недоступности данных. Создайте классы LocalWeatherService и RemoteWeatherService.

![image](https://github.com/user-attachments/assets/eb874a1c-4f31-48ec-bad9-7bed2a8772bf)

### 26
>Создайте класс Transaction с виртуальной функцией commit(), которая выбрасывает исключение при ошибке выполнения транзакции. Реализуйте классы BankTransaction и CryptoTransaction.

![image](https://github.com/user-attachments/assets/49327ead-f4cd-4734-b710-a23975d87ef7)

### 27
>Реализуйте класс Notification с виртуальной функцией send(), которая выбрасывает исключение при ошибке отправки. Создайте классы EmailNotification и SMSNotification.

![image](https://github.com/user-attachments/assets/ae6a432c-efc2-4f8e-89c7-051093bca703)

### 28
>Напишите базовый класс Shape с виртуальной функцией getBoundingBox(), которая выбрасывает исключение при некорректных параметрах. Реализуйте классы Circle и Polygon.

![image](https://github.com/user-attachments/assets/e9bdc63a-3316-420c-a6bc-ad45423fe9bc)

### 29
>Создайте класс User Profile с виртуальной функцией updateProfile(), которая выбрасывает исключение при некорректных данных. Реализуйте классы AdminProfile и GuestProfile.

![image](https://github.com/user-attachments/assets/c85b8982-910f-4193-8dab-065cd607debb)

### 30
>Реализуйте класс PaymentProcessor с виртуальной функцией processPayment(), которая выбрасывает исключение при недостаточном балансе. Создайте классы CreditCardProcessor и DebitCardProcessor.

![image](https://github.com/user-attachments/assets/b48606e0-b3f7-4399-baaf-1ed53cc283b0)


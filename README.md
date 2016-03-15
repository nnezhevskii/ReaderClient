# ReaderClient

* **endpoint** - Автоматически сгенерированная (с помощью утилиты wsimport) иерархия классов для работы с сервером
* **sample.AuthorizationController** - класс, инкапсулирущий авторизацию и регистрацию читателя. Предоставляет информацию о авторизированном пользователе. Реализуется паттерном Singleton
* **sample.Controller** - Компонент соединения пользовательского интерфейса и управляющих методов
* **sample.Main** - основной файл приложения

* **types.adapters** - Классы-адаптеры серверных типов. Для автоматической синхронизации данных между моделью и представлением необходимо, чтоб поля представляли собой Property
* **types.builders** - Фабричные методы для конструирования диалоговых окон
  
* **controllers.BookController** - Инкапсулирует логику работы с записями о книгах. Реализует паттерн Singleton
* **controllers.OperationController** - Инкапсулирует логику работы с записями о пользовательских операциях. Реализует паттерн Singleton
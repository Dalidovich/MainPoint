# MainPoint

Этот репозиторий служит централизованным каталогом всех моих проектов, модулей и полезных компонентов. Здесь собраны ссылки на репозитории с исходным кодом, а также примеры реализаций различных технологий и архитектурных решений.

_UPDATE DATE '06.08.2025 11:50'_

# README **`MainPoint`**

## Описание проекта

Путеводитель по проектам [https://github.com/Dalidovich](https://github.com/Dalidovich?tab=repositories)

## Проекты

- Web App (6)
  - [AdminDashboard.API](https://github.com/Dalidovich/AdminDashboard.API)
  - [DefaultMessager](https://github.com/Dalidovich/DefaultMessager)
  - [FileStatisticsWatcher](https://github.com/Dalidovich/FileStatisticsWatcher)
  - [ImageToQRCodeASP](https://github.com/Dalidovich/ImageToQRCodeASP)
  - PresentationCreator (совместное создание презентаций с использованием SignalR)
    - [PresentationCreator](https://github.com/Dalidovich/PresentationCreator)
    - [PresentationCreatorFrontend](https://github.com/Dalidovich/PresentationCreatorFrontend)
- Web API (9)
  - [AdsPlatformsFinder](https://github.com/Dalidovich/AdsPlatformsFinder)
  - [LocalS3API](https://github.com/Dalidovich/LocalS3API)
  - [WebAPIASPTemplate](https://github.com/Dalidovich/WebAPIASPTemplate)
  - [TestConnector.TestAPI](https://github.com/Dalidovich/TestConnector.TestAPI)
  - HCL project (проект клон Habr)
    - [HCL.APIGateway (на Ocelot)](https://github.com/Dalidovich/HCL.APIGateway)
    - [HCL.ArticleService.API](https://github.com/Dalidovich/HCL.ArticleService.API)
    - [HCL.CommentServer.API](https://github.com/Dalidovich/HCL.CommentServer.API)
    - [HCL.IdentityServer.API](https://github.com/Dalidovich/HCL.IdentityServer.API)
    - [HCL.NotificationSubscriptionServer.API](https://github.com/Dalidovich/HCL.NotificationSubscriptionServer.API)
- Console App (10)
  - System app
    - [ConsoleTransitionsDataByLAN (Consumer и Producer на TCP протоколе)](https://github.com/Dalidovich/ConsoleTransitionsDataByLAN)
    - [ConsoleAudioPlayer](https://github.com/Dalidovich/ConsoleAudioPlayer)
    - [getSystemDeviceData](https://github.com/Dalidovich/getSystemDeviceData)
  - с SFML Визуализацией
    - [ArraySortVisualization](https://github.com/Dalidovich/ArraySortVisualization)
    - [NeuralNetworkExample](https://github.com/Dalidovich/NeuralNetworkExample)
    - [PathFindAlgorithmDemo](https://github.com/Dalidovich/PathFindAlgorithmDemo)
  - [CrackRARArchive](https://github.com/Dalidovich/CrackRARArchive)
  - [FastCreateNote](https://github.com/Dalidovich/FastCreateNote)
  - [neuralNetworkRelationNeuronEachToEach](https://github.com/Dalidovich/neuralNetworkRelationNeuronEachToEach)
  - [xmlParser](https://github.com/Dalidovich/xmlParser)
- Web (JS) (1)
  - [GameLife](https://github.com/Dalidovich/GameLife)

## Модули для переиспользования

- [drag-and-drop js `(ImageToQRCodeASP)`](https://github.com/Dalidovich/ImageToQRCodeASP/blob/master/ImageToQRCodeWebSite/Views/Home/Index.cshtml)
- Сетевые модули
  - [Web soket client `(TestConnector.TestAPI)`](https://github.com/Dalidovich/TestConnector.TestAPI/blob/master/TestConnector/WevSocket/WebSocketClientParser.cs)
  - [gRPC `(HCL.IdentityServer.API)`](https://github.com/Dalidovich/HCL.IdentityServer.API/blob/master/HCL.IdentityServer.API.BLL/Protos/AthorService.proto)
  - TCP
    - [TCP client `(ConsoleTransitionsDataByLAN)`](https://github.com/Dalidovich/ConsoleTransitionsDataByLAN/blob/master/ConsoleTransitionsDataByLAN.Consumer/TCPConsumer.cs)
    - [TCP Listener `(ConsoleTransitionsDataByLAN)`](https://github.com/Dalidovich/ConsoleTransitionsDataByLAN/blob/master/ConsoleTransitionsDataByLAN.Producer/TCPProducer.cs)
- JWT
  - With Refresh token
    - [`DefaultMessager`](https://github.com/Dalidovich/DefaultMessager/blob/infinityScroll/DefaultMessager.BLL/Implementation/AccountService.cs)
    - [`AdminDashboard.API`](https://github.com/Dalidovich/AdminDashboard.API/blob/master/AdminDashboard.API.BLL/Services/RegistrationService.cs)
  - Without Refresh token
    - [`HCL.IdentityServer.API`](https://github.com/Dalidovich/HCL.IdentityServer.API/blob/master/HCL.IdentityServer.API.BLL/Services/TokenService.cs)
- QR CODE
  - [`ImageToQRCodeASP`](https://github.com/Dalidovich/ImageToQRCodeASP/blob/master/ImageToQRCodeWebSite/Models/ImgToQRCodeConverter.cs)
- Сервисы

  - [Generic сервисы и репозитории `(PresentationCreator)`](https://github.com/Dalidovich/PresentationCreator/blob/master/PresentationCreator.BLL/Services/BaseService.cs)
  - [Cast ответов от generic сервисов и репозиториев `(PresentationCreator)`](https://github.com/Dalidovich/PresentationCreator/blob/master/PresentationCreator.BLL/Extensions/ResponseCastExtension.cs)
  - [Update builder `(AdminDashboard.API)`](https://github.com/Dalidovich/AdminDashboard.API/tree/master/AdminDashboard.API.BLL/Services/HelperService)
  - [IEntityTypeConfiguration сложной структуры `(PresentationCreator)`](https://github.com/Dalidovich/PresentationCreator/tree/master/PresentationCreator.DAL/Configuration)
  - Midleware
    - [ExceptionHandling Midleware](https://github.com/Dalidovich/WebAPIASPTemplate/blob/master/WebAPIASPTemplate.API/Midlaware/ExceptionHandlingMiddleware.cs)
  - Hosted service
    - [CheckDB HostedService](https://github.com/Dalidovich/WebAPIASPTemplate/blob/master/WebAPIASPTemplate.API/HostedServices/CheckDBHostedService.cs)
    - [EnterSeedData HostedService](https://github.com/Dalidovich/WebAPIASPTemplate/blob/master/WebAPIASPTemplate.API/HostedServices/EnterSeedDataHostedService.cs)

- [Windows Context Menu Regisrated `(ConsoleAudioPlayer)`](https://github.com/Dalidovich/ConsoleAudioPlayer/blob/master/ConsoleAudioPlayer/PlayerSettings/ContextMenuRegisrated.cs)
- [Benchmark `(PathFindAlgorithmDemo)`](https://github.com/Dalidovich/PathFindAlgorithmDemo/tree/master/PathFindAlgorithmDemo.Benchmark)
- SignalR
  - HUB (`DefaultMessager`)[https://github.com/Dalidovich/DefaultMessager/tree/finalMonolit/DefaultMessager.ChatAPI]
  - HUB (`PresentationCreator`)[https://github.com/Dalidovich/PresentationCreator/tree/master/PresentationCreator.BLL/Hubs]
  - Client (`PresentationCreator`)[https://github.com/Dalidovich/PresentationCreatorFrontend/blob/main/src/pages/Editor.jsx]
- Визуализация
  - Fronend
    - [Frontend на React + Vite `(AdminDashboard)`](https://github.com/Dalidovich/AdminDashboard.API/tree/master/AdminDashboard)
    - [Frontend на React + Vite `(PresentationCreatorFrontend)`](https://github.com/Dalidovich/AdminDashboard.API/tree/master/PresentationCreatorFrontend)
  - SFML
    - [`NeuralNetworkExample`](https://github.com/Dalidovich/NeuralNetworkExample/blob/master/NeuralNetworkExample/ExampleImplement/DataSection/Implement/DataNNSectionWithSFML.cs)
    - [`PathFindAlgorithmDemo`](https://github.com/Dalidovich/PathFindAlgorithmDemo/blob/master/PathFindAlgorithmDemo/HelpFullTools/Display.cs#L141)
    - [`ArraySortVisualization`](https://github.com/Dalidovich/ArraySortVisualization/blob/master/ArraySortVisualization/Visualization.cs#L91)
  - ASCII
    - [`NeuralNetworkExample`](https://github.com/Dalidovich/NeuralNetworkExample/blob/master/NeuralNetworkExample/ExampleImplement/DataSection/Implement/DataNNSectionWithSymbols.cs)
  - Console
    - [`ConsoleAudioPlayer`](https://github.com/Dalidovich/ConsoleAudioPlayer/blob/master/ConsoleAudioPlayer/VisualizeComponent/Visualizer.cs)
- [Iterator `(CrackRARArchive)`](https://github.com/Dalidovich/CrackRARArchive/blob/master/CrackRARArchive/IteratorOnArray.cs)
- [Структура дерево (Node)(`AdsPlatformsFinder`)](https://github.com/Dalidovich/AdsPlatformsFinder)
- OData
  - [`HCL.ArticleService.API` (MongoDB)](https://github.com/Dalidovich/HCL.ArticleService.API/blob/master/HCL.ArticleService.API/DIManger.cs#L37)
  - [`HCL.CommentServer.API` (PostgreSQL)](https://github.com/Dalidovich/HCL.CommentServer.API/blob/master/HCL.CommentServer.API/DIManger.cs#L43)
- HCL project
  - У каждого сервиса
    - **JWT** _(для регистрации/авторизации/аунтификации)_
    - **Elasticsearch + Serilog**
    - **docker-compose**
    - **интеграционные и unit тестирование**
  - [IdentityServer](https://github.com/Dalidovich/HCL.IdentityServer.API)
    - **PostgreSQL**
    - **Redis** _(для кеширования публичных данных пользователя)_
    - **gRPC** _(для передачи публичных данных пользователя)_
    - **CI/CD** _GitHub Actions_
  - [ArticleService](https://github.com/Dalidovich/HCL.ArticleService.API)
    - **MongoDB** _(для хранения статей произвольного формата)_
    - **OData** _(гибкий способ получения данных)_
    - **gRPC** _(для получения публичных данных пользователя, если нет кешированных данных)_
    - **Redis** _(для получения кешированных публичных данных пользователя)_
    - **Kafka** _(сообщения при создании статьи)_
    - **Hangfire** _(обновления состояния актуальности статьи)_
  - [CommentServer](https://github.com/Dalidovich/HCL.IdentityServer.API)
    - **PostgreSQL**
    - **OData** _(гибкий способ получения данных)_
    - **SignalR** _(Real-time связь)_
    - **Kubernetes** _(опционально)_
  - [NotificationSubscriptionServer](https://github.com/Dalidovich/HCL.IdentityServer.API)
    - **PostgreSQL**
    - **Kafka** _(получение сообщений при создании статьи для уведомлений)_
    - **OData** _(гибкий способ получения данных)_

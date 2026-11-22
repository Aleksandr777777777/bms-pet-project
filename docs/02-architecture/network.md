# Сетевая архитектура

```mermaid
flowchart LR
    A[Виртуальные устройства<br/>Modbus TCP :5020-5025] --> B[Сервис-шлюз<br/>Python + pymodbus]
    B --> C[REST API<br/>FastAPI]
    C --> D[Веб-интерфейс<br/>React / Vue]

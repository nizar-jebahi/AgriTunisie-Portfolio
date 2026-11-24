
flowchart TB
    U["👨‍🌾 Farmer / User"]

    subgraph FRONTEND["Frontend Layer"]
        A["Angular + Ionic"]
        B["Agricultural Dashboard"]
    end

    subgraph BACKEND["Backend Layer"]
        C["FastAPI"]
        D["API Services"]
    end

    subgraph AI["Artificial Intelligence Layer"]
        E["YOLOv8 - Disease Detection"]
        F["EfficientNetB0 - Classification"]
        G["XGBoost - Irrigation Prediction"]
        H["RAG - Agricultural Assistant"]
    end

    subgraph IOT["IoT Layer"]
        I["Raspberry Pi"]
        J["DHT11 / BH1750"]
        K["Soil Moisture Sensor"]
    end

    L[("MongoDB")]

    U --> A
    A --> B
    B <--> C
    C --> D
    D --> E
    D --> F
    D --> G
    D --> H
    I --> J
    I --> K
    I --> C
    D <--> L

                    Mobile App (Flutter)
                           │
                    API Gateway (Nginx)
                           │
        ┌──────────────────┴──────────────────┐
        │                                     │
 Authentication Service              Messaging Service
        │                                     │
        └──────────────┬──────────────────────┘
                       │
                WebSocket Gateway
                       │
          ┌────────────┴────────────┐
          │                         │
      PostgreSQL                Redis
          │                         │
          └────────────┬────────────┘
                       │
                 Object Storage
                    AWS S3
                       │
              Push Notification Service
             Firebase / Apple Push

inventory-orders-api/
├── prisma/
│   ├── schema.prisma           # Modelos y relaciones de PostgreSQL
│   └── seed.ts                 # Script para poblar datos iniciales
├── src/
│   ├── config/
│   │   └── env.ts              # Validación de variables de entorno con Zod
│   ├── middlewares/
│   │   ├── auth.middleware.ts  # Verificación de JWT y roles
│   │   ├── validate.middleware.ts # Validación de body/query con Zod
│   │   └── error.middleware.ts # Captura global de errores
│   ├── modules/                # Cada entidad aislada con su lógica
│   │   ├── auth/               # auth.routes.ts, auth.controller.ts, auth.service.ts, auth.schema.ts
│   │   ├── products/   
│   │   └── orders/
│   ├── utils/
│   │   ├── AppError.ts         # Clase personalizada para errores HTTP
│   │   ├── jwt.ts
│   │   └── password.ts
│   ├── app.ts                  # Configuración de Express (middlewares y rutas)
│   └── server.ts               # Inicio del servidor
├── tests/                      # Suite de API Testing con Playwright
├── .env.example
├── package.json
└── tsconfig.json
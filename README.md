# EventosU - Modelo de amenazas

Tarea de Ciberseguridad (Universidad Galileo): modelado de amenazas del sitio web ficticio EventosU, en fase de diseño.

## Integrante
- Alessandro Alecio - 21001224

## Alcance
Sitio web (React/CDN), API, base de datos, bucket, panel `/admin`, app de puerta y los flujos hacia Microsoft Entra ID, la pasarela de pagos y el servicio de correo. Quedan fuera el interior de esos servicios externos y la infraestructura física del proveedor de nube. Los activos y supuestos están en el informe.

## Estructura
```
eventosu-threat-model/
├── README.md
├── model/eventosu.json    # modelo de Threat Dragon
└── docs/
    ├── informe.pdf        # informe final
    └── amenazas.csv       # tabla de amenazas
```

## Cómo abrir el modelo
1. Entrar a [threatdragon.com](https://threatdragon.com) (versión web de OWASP Threat Dragon).
2. Elegir abrir un modelo existente e importar `model/eventosu.json`.
3. El modelo tiene el DFD nivel 0 y nivel 1.

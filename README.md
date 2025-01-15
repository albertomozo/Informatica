# Informatica
Manual introductorio a la informática



```mermaid
graph TD
    A[Hardware] --> A1[Procesadores]
    A --> A2[Memoria]
    A --> A3[Periféricos]
    A --> A4[Electrónica]

    B[Software] --> B1[Sistemas operativos]
    B --> B2[Utilidades]
    B --> B3[Controladores]

    C[Informática] --> A
    C --> B

    B --> C1[Sistemas]
    B --> C2[Desarrollo]

    %% Sistemas
    C1 --> D1[Redes]
    C1 --> D2[Equipos]
    C1 --> D3[Bases de datos]

    %% Desarrollo
    C2 --> E1[Escritorio]
    C2 --> E2[Web]
    C2 --> E3[Móviles]
    C2 --> E4[IA]
    C2 --> E5[Videojuegos]
    C2 --> E6[IoT]
    C2 --> E7[Nube]
    C2 --> E8[Blockchain]


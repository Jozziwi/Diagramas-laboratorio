# Diagramas de Laboratorio

## 1. Prueba Presuntiva

```mermaid
graph TD
    A([INICIO]) --> B[Agitar vigorosamente para una distribución uniforme de la muestra]
    B --> C[Diluir muestras con alta concentración bacteriana]
    C --> D[Dispensar tubos: 3 tubos con 10 mL doble concentración y 6 tubos con 10 mL dosis simple]
    D --> E[Colocar tubo Durham invertido en cada tubo]
    E --> F[Adicionar muestra: 10 mL en doble concentración; 1 mL y 0.1 mL en concentración simple]
    F --> G[Incubar tubos a 35°C ± 0.5°C por 24 h - 48 h ± 3 h]
    G --> H{¿Presencia de turbidez y gas en tubo Durham?}
    H -- SÍ --> I[POSITIVO]
    H -- NO --> J[NEGATIVO]
    J --> K[Incubar tubos negativos 24 h ± 3 h]
    K --> L[Examinar nuevamente]
    I --> M([FIN])
    L --> M
```

## 2. Pruebas Confirmativas

### 2.1 Coliformes Totales
```mermaid
graph TD
    A([INICIO]) --> B[Inocular tubos de caldo lactosa bilis verde brillante con tubo Durham invertido]
    B --> C[Incubar 35°C ± 0.5°C por 24 h – 48 h ± 3 h]
    C --> D[Examinar producción de gas]
    D --> E([FIN])
```

### 2.2 Coliformes Fecales Termotolerantes
```mermaid
graph TD
    A([INICIO]) --> B[Inocular tubos con caldo lactosa bilis verde brillante con tubo Durham invertido]
    B --> C[Incubar a 44.5 °C ± 0.2 °C por 24 h ± 2 h]
    C --> D[Examinar producción de gas]
    D --> E([FIN])
```

### 2.3 E. coli
```mermaid
graph TD
    A([INICIO]) --> B[Inocular tubos de agua Triptona o agua peptonada]
    B --> C[Incubar a 44.5 °C ± 0.2 °C por 24 h ± 2 h]
    C --> D[Adicionar de 0.2 mL a 0.3 mL de reactivo de Kovac o su equivalente]
    D --> E[Agitar]
    E --> F{¿Coloración roja en superficie?}
    F -- SÍ --> G[POSITIVO]
    F -- NO --> H[NEGATIVO]
    G --> I[Enumerar NMP / 100 mL según serie de tubos usada]
    H --> I
    I --> J([FIN])
```

## 3. Preparación de Agar Nutritivo

```mermaid
graph TD
    A([INICIO]) --> B[Suspender 23 g de medio en 1 L de agua purificada]
    B --> C[Mezclar y calentar con agitación suave hasta disolver]
    C --> D[Hervir por un minuto]
    D --> E[Esterilizar en autoclave: 121 °C durante 15 minutos]
    E --> F[Dejar enfriar hasta 45-50 °C]
    F --> G[Verter en cajas de Petri estériles]
    G --> H([FIN])
```

## 4. Siembra de la Muestra en Agar Nutritivo

```mermaid
graph TD
    A([INICIO]) --> B[Realizar por procedimiento interno del laboratorio]
    B --> C[Incubar a 35 °C ± 2 °C de 18 h a 24 h]
    C --> D([FIN])
```

## 5. Diagramas de Aislamiento

### 5.1 Preparación Inicial de Aislamiento
```mermaid
graph TD
    A([INICIO]) --> B[Aislar microorganismos a partir de un cultivo mixto en un caldo ordinario]
    B --> C[Sembrar 2 placas: Placa A por agotamiento de asa y Placa B por estrías escocesas y en cuadrante]
    C --> D([FIN])
```

### 5.2 Agotamiento de Asa
```mermaid
graph TD
    A([INICIO]) --> B[Homogenizar cultivo mixto]
    B --> C[Flamear asa bacteriológica y tomar muestra de cultivo]
    C --> D[Flamear boca del tubo al abrir y cerrarlo]
    D --> E[En una placa con agar nutritivo, tocar con suavidad la superficie y extender la muestra]
    E --> F[Cerrar la placa y dejar en posición invertida]
    F --> G[Incubar a 37 °C]
    G --> H[Examinar a las 24 h las colonias formadas]
    H --> I([FIN])
```

## 6. Controles de Determinación de Coliformes Totales

### 6.1 Control Positivo de E. coli
```mermaid
graph TD
    A([INICIO]) --> B[Tomar colonia de cepa E. coli ATCC 25922 aislada en agar plate count con asa redonda estéril]
    B --> C[Inocular en 100 mL de agua estéril]
    C --> D[Agregar medio colilert y mezclar]
    D --> E[Verter en bolsa quanti-tray/2000 marcada y sellar]
    E --> F[Incubar a 35 ± 0.5 °C por 24 h]
    F --> G[Resultado esperado: Presentar crecimiento, color amarillo y fluorescencia bajo luz UV]
    G --> H([FIN])
```

### 6.2 Control Positivo Coliformes Totales
```mermaid
graph TD
    A([INICIO]) --> B[Tomar colonia de cepa Klebsiella pneumoniae ATCC 4352 aislada en agar plate count con asa redonda estéril]
    B --> C[Inocular en 100 mL de agua estéril]
    C --> D[Agregar medio colilert y mezclar]
    D --> E[Verter en bolsa quanti-tray/2000 marcada y sellar]
    E --> F[Incubar a 35 ± 0.5 °C por 24 h]
    F --> G[Resultado esperado: Presentar crecimiento y color amarillo]
    G --> H([FIN])
```

### 6.3 Control Negativo
```mermaid
graph TD
    A([INICIO]) --> B[Tomar colonia de cepa P. aeruginosa ATCC 27853 aislada en agar plate count con asa redonda estéril]
    B --> C[Inocular en 100 mL de agua estéril]
    C --> D[Agregar medio colilert y mezclar]
    D --> E[Verter en bolsa quanti-tray/2000 marcada y sellar]
    E --> F[Incubar a 35 ± 0.5 °C por 24 h]
    F --> G[Resultado esperado: No debe presentar crecimiento]
    G --> H([FIN])
```

## 7. Pruebas de Oxidasa

### 7.1 Procedimiento de Prueba de Oxidasa
```mermaid
graph TD
    A([INICIO]) --> B[Colocar 2-3 gotas de reactivo de oxidasa preparado recientemente en un papel filtro sobre caja Petri]
    B --> C[Dispensar porción de la colonia sobre el papel filtro]
    C --> D{¿Aparición de color azul-morado en un lapso de 10 s?}
    D -- SÍ --> E[POSITIVO]
    D -- NO --> F[NEGATIVO]
    E --> G([FIN])
    F --> G
```

### 7.2 Pruebas de Control para el Reactivo de Oxidasa
```mermaid
graph TD
    A([INICIO]) --> B[Realizar prueba de control para el reactivo de oxidasa]
    B --> C[Control positivo: Pseudomonas aeruginosa]
    B --> D[Control negativo: E. coli]
    C --> E([FIN])
    D --> E
```

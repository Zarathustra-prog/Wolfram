# Wolfram

Este proyecto muestra cómo implementar compuertas lógicas básicas mediante **perceptrones** en Wolfram Language (Mathematica).  
Cada compuerta se define como un perceptrón con pesos y sesgos, y en el caso de la XOR se utiliza una red multicapa.  

---

## 📂 Archivos incluidos

### 🔹 Compuerta AND
- **Archivo:** `AND_mod.nb`
- **Pesos:** `{1, 0.9}`
- **Sesgo:** `-1.3`
- **Implementación:** perceptrón con entrada `{x1, x2}` → salida binaria.

#### ▶️ Cómo ejecutarlo
1. Abrir el archivo `AND_mod.nb` en Wolfram Mathematica.  
2. Ejecutar todas las celdas (`Shift + Enter`).  
3. Se mostrará una tabla `2x2` con los valores de salida para las entradas posibles.

#### ✅ Resultados esperados
| x1 | x2 | salida |
|----|----|--------|
| 0  | 0  |   0    |
| 0  | 1  |   0    |
| 1  | 0  |   0    |
| 1  | 1  |   1    |

---

### 🔹 Compuerta OR
- **Archivo:** `OR_mod.nb`
- **Pesos:** `{1, 1}`
- **Sesgo:** `-0.7`
- **Implementación:** perceptrón sencillo.

#### ▶️ Cómo ejecutarlo
1. Abrir el archivo `OR_mod.nb`.  
2. Ejecutar todas las celdas.  
3. Se mostrará la tabla con los resultados de la compuerta OR.

#### ✅ Resultados esperados
| x1 | x2 | salida |
|----|----|--------|
| 0  | 0  |   0    |
| 0  | 1  |   1    |
| 1  | 0  |   1    |
| 1  | 1  |   1    |

---

### 🔹 Compuerta XOR
- **Archivo:** `XOR_mod.nb`
- **Arquitectura:** red de perceptrones multicapa:
  - NAND: pesos `{-1, -1}`, sesgo `+1.2`
  - OR: pesos `{1, 1}`, sesgo `-0.6`
  - AND final: pesos `{1, 1}`, sesgo `-1.2`
- **Descripción:** al combinar estas capas se obtiene el comportamiento XOR.

#### ▶️ Cómo ejecutarlo
1. Abrir el archivo `XOR_mod.nb`.  
2. Ejecutar todas las celdas.  
3. Se calcularán los resultados de la compuerta XOR como red multicapa.

#### ✅ Resultados esperados
| x1 | x2 | salida |
|----|----|--------|
| 0  | 0  |   0    |
| 0  | 1  |   1    |
| 1  | 0  |   1    |
| 1  | 1  |   0    |

### XOR
| x1 | x2 | salida |
|----|----|--------|
| 0  | 0  |   0    |
| 0  | 1  |   1    |
| 1  | 0  |   1    |
| 1  | 1  |   0    |

# git-challenges

Este repositorio es un repositorio de desafios a resolver. Cada rama contiene un caso diferente al que te deberas enfrentar.

# 🧩 Problema 6: Resolver un conflicto complejo en una fusión (problema-6-conflicto-fusion-avanzado)
## 🎯 Desafío:
Dos ramas (develop y feature-reportes) han evolucionado de forma paralela. Ambas modifican el mismo archivo (reportes.py) en las mismas líneas, con diferentes enfoques. Necesitas fusionar estas ramas manualmente resolviendo los conflictos de forma inteligente.

## 📝 Escenario:
La rama develop tiene una versión refactorizada del archivo con nuevos métodos.
La rama feature-reportes implementa una lógica específica que también edita las mismas líneas.
Al hacer merge, se generan conflictos en el archivo.

# 📝 Instrucciones para ti:
Cambia a la rama develop.
Intenta fusionar la rama feature-reportes.
Git mostrará un conflicto en el archivo reportes.py.
Resuelve el conflicto eligiendo lo mejor de ambas ramas:
Mantén la estructura refactorizada de main.
Integra la lógica de feature-reportes de forma ordenada.
Completa la fusión.

## ✅ ¿Cómo sabes que lo lograste?
No quedan conflictos.
El archivo reportes.py tiene tanto el refactor de main como la funcionalidad de feature-reportes.
El historial muestra un commit de fusión.
El proyecto sigue funcionando.
# Decisiones del proyecto

<<<<<<< HEAD
## D-002 · Estructura Maven multimódulo
Fecha: 19/10 · It. 0 · Acta: 19/10 · Issue: #12
Contexto: hay dos aplicaciones, servidor y cliente, en un mismo repositorio.
Decisión: pom padre radiodiagnostico con dos módulos: servidor y cliente.
Alternativas: dos repositorios; un solo módulo.
Motivo: un mvn verify construye todo y las versiones se fijan una vez en el padre.
Consecuencias: cada módulo con su versión; al cambiar la del padre, actualizar <parent>.
=======
## D-001 Crear el proyecto en Maven  

Fecha 19/10 - iteración 0
Se decide crear el proyecto en Maven siguiendo las instrucciones del PDF, utilizando pom.xml y la estructura cliente-servidor
>>>>>>> 7b7c26c76d5edb5e75dc0c8ae2ff4a48145e81f6

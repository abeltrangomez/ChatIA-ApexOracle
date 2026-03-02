
# ChatIA-ApexOracle

Este repositorio contiene un **taller** para construir un **chat con IA generativa** dentro de **Oracle APEX**, usando **OCI Generative AI** y **datos en Oracle** como fuente de conocimiento.

**Origen del taller:** Adaptación de *Oracle LiveLabs* “Building Intelligent APEX Apps with OCI Gen AI and Your Oracle Data”.  
Referencia: https://livelabs.oracle.com/ords/r/dbpm/livelabs/view-workshop?wid=4255&clear=RR,180&session=134445940433032

---

## Objetivo general

Desarrollar una aplicación en **Oracle APEX** que permita a los usuarios hacer preguntas en lenguaje natural y recibir respuestas generadas por un modelo de IA, **contextualizadas con información almacenada en Oracle**.

---

## Prerrequisito

Haber finalizado el taller anterior: **creación de la base de datos con políticas de IA en un compartimento**.

---

## Resultados de aprendizaje

Al finalizar el taller, podrás:

- Crear y configurar un **Workspace** en Oracle APEX.
- Preparar un **servicio de IA generativa** en Oracle Cloud Infrastructure (OCI).
- Gestionar autenticación con **API Keys** y **credenciales web en APEX**.
- Integrar un **chat** dentro de una página APEX y conectarlo con un servicio GenAI.

---

## Taller paso a paso

### 1. Crear el Workspace

Se crea el *Workspace* donde se realizará el desarrollo de la aplicación APEX y su configuración asociada.

**Recurso (video):**  
https://uniempresarial-my.sharepoint.com/:v:/g/personal/abeltran_uniempresarial_edu_co/IQAmQYQKDgavTZ3p6WfHkXldAR1Ae0GOjnEb5Wmr6E1Pm78?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jndGF2

---

### 2. Creación de GenAI Service en OCI

Se configura el servicio de **IA generativa en OCI** que será consumido desde APEX para generar respuestas a partir de prompts y contexto.

**Recurso (video):**  
https://www.loom.com/share/f4027434d20244029f37bf0e26cc90c9

---

### 3. Crear la App básica en APEX

Se construye una aplicación mínima en APEX que servirá como base para integrar el chat y la lógica de interacción con GenAI.

**Recurso (video):**  
https://uniempresarial-my.sharepoint.com/:v:/g/personal/abeltran_uniempresarial_edu_co/IQAqaAO02u-tQLppurfu9ZdoAYXUo9m48iUgjS_z7DiywvI?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=PBO7Jn

---

### 4. Crear las API Key en OCI

Se generan las **API Keys** requeridas para autenticar y autorizar las llamadas desde APEX hacia los servicios de OCI.

**Recurso (video):**  
https://www.loom.com/share/6867b4cfc0474469a4dce5614e968889

---

### 5. Copiar las OCI Keys

Se recopilan los valores necesarios asociados a las llaves y al usuario en OCI para completar la configuración de conexión con APEX.

**Recurso (video):**  
https://www.loom.com/share/3022f70cbdb444fb8acbbc8bb76a65c7

---

### 6. Crear credenciales Web para APEX

Se registran las credenciales dentro de APEX para permitir el consumo de endpoints externos (OCI GenAI) desde la aplicación.

**Recurso (video):**  
https://www.loom.com/share/1f6aa3ba375e4be1857128385de7ceb1

---

### 7. Crear la Generative AI para estudiantes

Se configura la funcionalidad de IA generativa orientada al caso de uso de estudiantes, definiendo el comportamiento esperado del asistente.

**Recurso (video):**  
https://www.loom.com/share/741a2dd1db704c95acca14a699c7e755

---

### 8. Implementar el chat en la página de APEX

Se integra el componente de chat en la interfaz APEX y se conecta con el servicio GenAI para habilitar la conversación con los datos.

**Recurso (video):**  
https://www.loom.com/share/f121e02c98704053aa223b76e14aed0c

---

## Créditos

- Taller base: Oracle LiveLabs — “Building Intelligent APEX Apps with OCI Gen AI and Your Oracle Data”.
- Adaptación académica: **ChatIA-ApexOracle** (este repositorio).
```


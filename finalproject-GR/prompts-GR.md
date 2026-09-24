> Detalla en esta sección los prompts principales utilizados durante la creación del proyecto, que justifiquen el uso de asistentes de código en todas las fases del ciclo de vida del desarrollo. Esperamos un máximo de 3 por sección, principalmente los de creación inicial o  los de corrección o adición de funcionalidades que consideres más relevantes.
Puedes añadir adicionalmente la conversación completa como link o archivo adjunto si así lo consideras


## Índice

1. [Descripción general del producto](#1-descripción-general-del-producto)
2. [Arquitectura del sistema](#2-arquitectura-del-sistema)
3. [Modelo de datos](#3-modelo-de-datos)
4. [Especificación de la API](#4-especificación-de-la-api)
5. [Historias de usuario](#5-historias-de-usuario)
6. [Tickets de trabajo](#6-tickets-de-trabajo)
7. [Pull requests](#7-pull-requests)

---

## 1. Descripción general del producto

EXPLORE the current repository for functional detail of what the app in developmeant is and does. Generate a detailed PRD document withouth ANY technical/stack or implementataion detail, only user facing functionality. This document is meant to be consumed for an eventual, ai agentically driven implementation, so keep it tech-agnostic.
The final output can be an .md file

*Nota*: Este prompt fue ejecutado en el proyecto/repo original. El output de dicho prompt (el PRD) fue luego importado al proyecto actual.

**Prompt 2:**

**Prompt 3:**

---

## 2. Arquitectura del Sistema

### **2.1. Diagrama de arquitectura:**

Based on the PRD, let´s start defining arquitecture and tech stack for a WEB application. Present alternatives (5 at most) for each service layer, with pros and cons and list the top three combinations. Each decision we make together will eventually be documented in an ADR document so keep track of the rationale we apply.

**Prompt 2:**

**Prompt 3:**

### **2.2. Descripción de componentes principales:**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.3. Descripción de alto nivel del proyecto y estructura de ficheros**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.4. Infraestructura y despliegue**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.5. Seguridad**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

### **2.6. Tests**

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

---

### 3. Modelo de Datos

Based on the existing PRD and ADR(s) documents, define a data model that fits the tech stack, arquitecture and funcional intent of the application. Illustrate the model with a mermaid graph and add reference to the corresponding documents when applicable.
Make sure to add detailed descriptions for each of the main entities already defined in the documentation.

**Prompt 2:**

**Prompt 3:**

---

### 4. Especificación de la API

Based on the existing PRD and ADRs documents, describe the 3 most important API endpoints in OpenAPP format. Add references to the corresponding documents when applicable. For each endpoint add a request-response example. 

**Prompt 2:**

**Prompt 3:**

---

### 5. Historias de Usuario

Based on the existing PRD and ADRs documents, document the three main functionalitites as User Stories. The stories must include acceptance criterias clearly defined in Gherkin

----------------------------------------------------------------------------------------------
The three user stories you have defined in the document have two different functionalitites merged in one (create test case AND organize in folders, create execution AND run it, open Overview Dashboard AND browse to the origin test case). Modify them to only cover ONE of these for each user story (create test case, create execution, browse to the original test case from bug)

**Prompt 3:**

---

### 6. Tickets de Trabajo

Define the three main technical work tickets for development: one for backend, one for frontend, one for databse. Provide all necessary details to develop the task end to end observing good practices and all specifications already covered within the PRD and ADR documentation.

**Prompt 2:**

**Prompt 3:**

---

### 7. Pull Requests

**Prompt 1:**

**Prompt 2:**

**Prompt 3:**

# Intelligent Therapy Scheduling System

## Overview

The Intelligent Therapy Scheduling System is a conceptual architecture proposal for an AI-assisted system designed to organize medical prescriptions into structured therapeutic schedules.

This system does not prescribe, modify, or recommend medications. It operates exclusively as an organizational and scheduling support tool based on prescriptions previously issued by licensed healthcare professionals.

---

## Problem Statement

Patients frequently experience difficulty managing medication schedules, especially when:

- Multiple medications are prescribed simultaneously
- Doses require fixed intervals (e.g., every 6, 8, or 12 hours)
- Treatments span multiple days with specific start times
- Manual time calculations lead to confusion or errors

In clinical environments, nursing professionals must coordinate medication administration for multiple patients per shift, increasing operational complexity.

---

## Proposed Solution

The proposed system leverages AI-based natural language interpretation to:

- Parse prescription instructions written in natural language
- Calculate dose intervals automatically
- Generate structured therapeutic schedules
- Define treatment start and end times
- Associate each medication with its respective time slot
- Enable automated reminder or alert generation

The system functions strictly as a scheduling and organizational engine.

---

## Scope and Limitations

This project:

- Does NOT perform medical diagnosis
- Does NOT prescribe medications
- Does NOT recommend dosage changes
- Does NOT replace professional medical evaluation
- Operates only after a prescription has been issued by a licensed healthcare provider

The purpose is organizational automation, not clinical decision-making.

---

## Conceptual Architecture

### Input Layer
- Natural language prescription entry  

### Processing Layer
- Prescription parsing  
- Interval calculation engine  
- Treatment duration computation  
- Schedule generation logic  

### Output Layer
- Structured schedule  
- Time-specific medication listing  
- Optional notification trigger system  

Future extensions may include audit logging and multi-patient management modules.

---

## Application Layers

### Consumer Application (B2C)

A simplified interface for individual users to:

- Organize personal prescriptions  
- Automate medication reminders  
- Reduce scheduling errors  

### Clinical Support Application (B2B)

A professional version designed for healthcare environments, potentially including:

- Multi-patient management  
- Administration logging  
- User-based access control  
- Integration with hospital systems  

---

## Future Development

- Prototype implementation
- AI parsing refinement
- Notification automation module
- Secure data handling model
- Clinical environment compliance exploration

---

## License

This project is currently a conceptual proposal intended for research and development purposes.
---

## 🚀 Atualização – Versão 1.1 (Fevereiro 2026)

O projeto evoluiu de um protótipo inicial para um sistema funcional completo.

### ✅ O que foi implementado:

- Suporte a múltiplos medicamentos no mesmo tratamento  
- Geração automática de doses com base em intervalo e duração  
- Organização cronológica das medicações  
- Confirmação de próxima dose via ENTER  
- Barras de progresso individuais por medicamento  
- Barra de progresso geral do tratamento  
- Salvamento automático em arquivo JSON  
- Continuação do tratamento após reabrir o programa  
- Geração de executável (.exe) com PyInstaller  

### 📦 Status Atual

🟢 Sistema funcional  
🟢 Executável gerado e testado  
🟡 Melhorias visuais em desenvolvimento (Versão 1.2)

---

Projeto em evolução contínua 🚀

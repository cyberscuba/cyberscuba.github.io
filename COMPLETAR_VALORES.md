# Instrucciones para Completar Tu CV - Valores Numéricos y Específicos

Tu CV está optimizado para ATS y listo para publicar. **Solo necesitas reemplazar los valores marcados con [X%] o [Monto] con tus números reales.**

## 🎯 Dónde Buscar Cada Valor

### 1. **Sección Celuweb - Líder en Infraestructura**

#### Campo: `reducción de [X%] en deployment manual`
- **Qué es:** % de reducción en tiempo de deployment o cantidad de deployments manuales antes vs después de IaC
- **Dónde obtenerlo:**
  - Revisa tu histórico de deployments en Jenkins/GitLab
  - Tiempo antes (manual): ¿Cuántas horas/días tomaba un deployment?
  - Tiempo después (automatizado): ¿Cuánto toma ahora?
  - Cálculo: `(antes - después) / antes × 100 = X%`
- **Ejemplo:** "reducción de 75% en deployment manual" (antes 4 horas → ahora 1 hora)

#### Campo: `eliminación de [X] vulnerabilidades críticas`
- **Qué es:** Número específico de vulnerabilidades críticas que mitigaste
- **Dónde obtenerlo:**
  - Reportes de seguridad / vulnerability scans (AWS Security Hub, Azure Security Center)
  - Tickets de seguridad cerrados
  - Auditorías de seguridad completadas
- **Ejemplo:** "eliminación de 23 vulnerabilidades críticas en IAM y firewalls"

#### Campo: `reducción de [X%] en incidentes por deployment`
- **Qué es:** % de reducción en incidentes post-deployment
- **Dónde obtenerlo:**
  - Incident tracking system
  - Jira / Azure DevOps: tickets de "post-deployment issues"
  - Métricas de calidad: antes vs después de CI/CD
- **Ejemplo:** "reducción de 60% en incidentes por deployment"

---

### 2. **Sección Skina Technologies - Administrador Linux**

#### Campo: `para [X] clientes corporativos`
- **Qué es:** Número de clientes que administraste
- **Dónde obtenerlo:** Linkedin, email, CRM de la empresa
- **Ejemplo:** "Administré servidores Linux para 12 clientes corporativos"

#### Campo: `para [X] aplicaciones críticas`
- **Qué es:** Número de aplicaciones que mantuviste en alta disponibilidad
- **Dónde obtenerlo:** Documentación de infraestructura, lista de servidores
- **Ejemplo:** "disponibilidad para 18 aplicaciones críticas"

#### Campo: `reducción [X%] incidentes de seguridad`
- **Qué es:** % de reducción en incidentes de seguridad (ataques, accesos no autorizados, etc.)
- **Dónde obtenerlo:**
  - Logs de firewall / IDS
  - Reportes de seguridad trimestral/anual
  - Tickets de seguridad resueltos
- **Ejemplo:** "reducción 45% incidentes de seguridad" (de 20/mes → 11/mes)

#### Campo: `tiempo de resolución de incidencias en [X%]`
- **Qué es:** % de mejora en MTTR (Mean Time To Resolution)
- **Dónde obtenerlo:**
  - Tickets en Jira: MTRE antes vs después
  - SLA tracking
  - Reportes de disponibilidad
- **Ejemplo:** "Redujo tiempo de resolución de incidencias en 40%" (de 4 horas → 2.4 horas)

---

## 📋 Checklist para Completar tu CV

```markdown
[ ] Celuweb - "reducción de [X%] deployment manual"
[ ] Celuweb - "eliminación de [X] vulnerabilidades críticas"
[ ] Celuweb - "reducción [X%] incidentes por deployment"
[ ] Skina - "Administré servidores Linux para [X] clientes"
[ ] Skina - "disponibilidad para [X] aplicaciones críticas"
[ ] Skina - "reducción [X%] incidentes de seguridad"
[ ] Skina - "Redujo tiempo resolución incidencias [X%]"
```

---

## 🔧 Cómo Editar el CV

### Opción 1: Editar en GitHub (Recomendado)
1. Ve a: `github.com/cyberscuba/cyberscuba.github.io`
2. Click en `index.html` → Click ícono de lápiz (Edit)
3. Busca `[X%]` o `[Monto]` con Ctrl+F
4. Reemplaza con tu valor
5. Click "Commit changes"

### Opción 2: Editar Localmente
1. Abre `index.html` con un editor de texto
2. Busca y reemplaza `[X%]` con tus valores
3. Guarda cambios
4. Git commit y push: 
```bash
git add index.html
git commit -m "Update CV with specific metrics"
git push
```

---

## 💡 Tips para Encontrar Tus Números

### Si No Tienes Acceso a Sistemas Antiguos:
- **Pregunta a tu manager:** "¿Cuál fue el impacto de X proyecto?"
- **Revisa LinkedIn:** Si hay publicaciones de tu empresa sobre logros
- **Documentación de proyectos:** Reportes finales, presentations, wikis internos
- **Memoria personal:** ¿Recuerdas aproximadamente?
  - "Creo que reducimos deployments de 3 horas a 45 minutos" → 75% (válido)

### Valores Conservadores vs Agresivos:
- **CONSERVADOR (más seguro):** "reducción de 35% en deployment manual"
- **AGRESIVO (si estás seguro):** "reducción de 75% en deployment manual"
- **RECOMENDACIÓN:** Usa lo que puedas justificar en entrevista. Mejor conservador y verificable que agresivo e indefendible.

---

## ⚠️ Importante: Antes de Publicar

**Revisa esto ANTES de enviar tu CV a empresas:**

- [ ] Todos los `[X%]` han sido reemplazados con números reales
- [ ] Todos los `[X]` han sido reemplazados con números específicos
- [ ] Los números son verificables (podrías explicarlos en entrevista)
- [ ] No hay referencias a números hipotéticos o estimados no verificables
- [ ] El CV se ve bien en navegador (abre `cyberscuba.github.io`)

---

## 📊 Ejemplos Finales (Con Valores Completados)

### ANTES (Con placeholders):
```
• Diseñé e implementé arquitectura multi-nube con redundancia geográfica | 
  Terraform, CloudFormation | Resultado: 99.95% uptime durante 18+ meses

• Orquesté automatización completa de infraestructuras mediante IaC | 
  Terraform, Ansible, Python | Resultado: reducción de [X%] deployment manual
```

### DESPUÉS (Con valores reales):
```
• Diseñé e implementé arquitectura multi-nube con redundancia geográfica | 
  Terraform, CloudFormation | Resultado: 99.95% uptime durante 18+ meses

• Orquesté automatización completa de infraestructuras mediante IaC | 
  Terraform, Ansible, Python | Resultado: reducción de 70% en tiempo de deployment (6h → 1.8h)
```

---

## 🚀 Próximos Pasos

1. **Completa los valores numéricos** (máximo 30 minutos)
2. **Commit y push** a GitHub
3. **Verifica en:** https://cyberscuba.github.io/
4. **Usa este CV** en todas tus aplicaciones corporativas
5. **Personaliza por puesto:** Reordena secciones según relevancia del puesto

¿Necesitas ayuda con algún valor específico? 📧

---

**Creado:** 2026-06-10 | **Versión:** ATS Optimizada v1.0 | **Estado:** Listo para Publicar

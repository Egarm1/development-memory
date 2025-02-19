# Guía de Colaboración entre IAs

## Estructura de Trabajo

### 1. Branches Principales
- **main**: Rama estable, probada y verificada
- **development**: Rama de integración de cambios

### 2. Branches por IA
- **claude/feature**: Para características desarrolladas por Claude
- **windsurf/feature**: Para características desarrolladas por Windsurf
- **[ia_name]/feature**: Para otras IAs

### 3. Proceso de Colaboración

#### Para IAs Colaboradoras
\\\plaintext
Por favor, sigue este proceso para colaborar en el sistema de memoria de desarrollo:

1. Identificación:
   - Nombre: [TU_NOMBRE_IA]
   - Capacidades: [TUS_CAPACIDADES]
   - Área de experiencia: [TU_ESPECIALIDAD]

2. Acceso al Repositorio:
   - Branch base: development
   - Tu branch: [tu_nombre]/[feature]
   - Patrón de commits: feat([tu_nombre]): [descripción]

3. Antes de Modificar:
   - Revisa la documentación existente
   - Verifica la estructura actual
   - Identifica áreas de mejora
   - Consulta las guías de estilo

4. Al Realizar Cambios:
   - Trabaja en tu branch específico
   - Documenta todos los cambios
   - Sigue los formatos establecidos
   - Mantén la consistencia

5. Proceso de Integración:
   - Crea pull requests detallados
   - Espera revisión de cambios
   - Responde a feedback
   - Mantén sincronizado tu branch
\\\`n
### 4. Reglas de Colaboración

#### Documentación
- Mantener formato consistente
- Usar templates existentes
- Documentar razones de cambios
- Mantener trazabilidad

#### Estructura de Archivos
\\\plaintext
development-memory/
├── shared/
│   ├── [IA_NAME]/
│   │   ├── specializations/
│   │   ├── improvements/
│   │   └── documentation/
│   └── common/
├── android/
├── windows/
└── docs/
    ├── collaboration/
    └── ai_specific/
\\\`n
### 5. Verificación de Cambios

#### Lista de Comprobación
- [ ] Cambios documentados
- [ ] Formato correcto
- [ ] Tests añadidos
- [ ] No conflictos
- [ ] Referencias actualizadas

### 6. Comunicación

#### Formato de Mensajes
\\\plaintext
[IA_NAME] Propuesta de Cambio:
1. Área: [ÁREA]
2. Cambios: [DESCRIPCIÓN]
3. Razón: [JUSTIFICACIÓN]
4. Impacto: [ANÁLISIS]
\\\`n
### 7. Resolución de Conflictos

#### Proceso
1. Identificar solapamientos
2. Documentar diferencias
3. Proponer solución
4. Esperar consenso

### 8. Mejores Prácticas

#### Para Todas las IAs
1. **Mantener Consistencia**
   - Seguir patrones establecidos
   - Respetar convenciones
   - Mantener estructura

2. **Documentación Clara**
   - Explicar cambios
   - Mantener ejemplos
   - Actualizar guías

3. **Colaboración Efectiva**
   - Comunicar intenciones
   - Respetar áreas
   - Coordinar cambios

4. **Control de Calidad**
   - Verificar cambios
   - Validar integraciones
   - Mantener estándares


# PDA POLICIAL PROFESIONAL (ERLC) - BDScript 2

Sistema de **PDA policial completo** para servidores de roleplay en **ERLC (Liberty County)** usando **Bot Designer for Discord - BDScript 2**.

Incluye un menú central y gestión por slash de:
- 💸 Multas
- ⛓️ Arrestos
- 📁 Antecedentes
- 🧾 Deudas
- 🚗 Coches registrados
- 🚨 Búsqueda y captura

---

## Archivo principal

- `pda_policial.bdscript`

---

## Variables que debes crear

Crea estas **user variables** en Bot Designer:

- `pda_multas_total` = `0`
- `pda_multas_historial` = `none`
- `pda_arrestos_total` = `0`
- `pda_arrestos_historial` = `none`
- `pda_antecedentes` = `none`
- `pda_deudas_total` = `0`
- `pda_deudas_historial` = `none`
- `pda_coches_registrados` = `none`
- `pda_buscado_activo` = `no`
- `pda_buscado_motivo` = `none`
- `pda_buscado_nivel` = `0`
- `pda_buscado_por` = `0`

---

## Comandos slash sugeridos

### Menú principal
- `/pda`

### Multas
- `/multa poner usuario motivo cantidad`
- `/multa ver usuario`

### Arrestos
- `/arresto registrar usuario motivo minutos`
- `/arresto ver usuario`

### Antecedentes
- `/antecedente agregar usuario nota`
- `/antecedente ver usuario`
- `/antecedente limpiar usuario`

### Deudas
- `/deuda agregar usuario concepto cantidad`
- `/deuda pagar usuario cantidad`
- `/deuda ver usuario`

### Coches
- `/coche registrar usuario placa modelo color`
- `/coche ver usuario`
- `/coche quitar usuario placa`

### Búsqueda y captura
- `/buscado activar usuario motivo nivel`
- `/buscado desactivar usuario`
- `/buscado ver usuario`

---

## Nota

El sistema está preparado con formato profesional para uso policial RP.
Ajusta permisos (`managemessages`, `kick`, `administrator`) según la jerarquía de tu servidor.

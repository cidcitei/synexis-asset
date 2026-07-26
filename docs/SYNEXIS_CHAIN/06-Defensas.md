# 06. Escenarios de Ataque y Defensa v3.0

## Ataque 1: Falsificación de descubrimientos (Sybil científico)

**Escenario**: Actor crea múltiples identidades y genera descubrimientos falsos para mintear SYNA.

**Defensa**:
- Triple Verificación: Oráculo + Nodos + Peer Review
- Deflator de Frecuencia (DF): muchos descubrimientos triviales = emisión tendiendo a cero
- Reputación de creador: descubrimientos de cuentas nuevas tienen II ajustado a la baja
- Vesting con condición: refutado = tokens quemados
- **Costo del ataque > beneficio**

## Ataque 2: Compra masiva post-descubrimiento

**Escenario**: Fondo compra todo el SYNA existente para controlar gobernanza.

**Defensa**:
- SYNA comprado no gobierna durante 365 días
- MCH = 0.1 para compradores puros
- Anti-Whales: límite 10% del poder de voto
- Supply escaso: precio sube hasta que la compra deja de ser rentable

## Ataque 3: Estancamiento de la red

**Escenario**: Nadie genera descubrimientos. La red se estanca.

**Defensa**:
- La red sigue funcionando: certificación, simulación, almacenamiento operan con fees
- Fondo Comunitario puede subsidiar descubrimientos iniciales
- La escasez es el incentivo: el primer descubrimiento tiene valor máximo
- **Una blockchain sin tokens sigue siendo una blockchain**

> "La seguridad de Synexis Chain no depende de la criptografía sola. Depende de que atacarla sea más costoso que contribuir legítimamente."

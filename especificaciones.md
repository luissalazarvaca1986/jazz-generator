# Especificaciones – Piano a dos manos

## Mano derecha

### Notas disponibles

| # | Cifrado | Nombre |
|---|---------|--------|
| 1 | A | La |
| 2 | C | Do |
| 3 | D | Re |
| 4 | D# / Eb | Re sostenido / Mi bemol (tecla negra) |
| 5 | E | Mi |
| 6 | G | Sol |
| 7 | A | La (octava superior) |

### Comportamiento

- **Selección de notas:** al azar entre las notas disponibles.
- **Duración de cada nota:** aleatoria, entre **0.25 s y 0.75 s**.
- **Silencios:** cada **3 notas**, puede aparecer al azar (o no) un silencio de **0.75 s**.
- **Repetición:** continúa indefinidamente.

## Mano izquierda

### Notas disponibles

| # | Cifrado | Nombre |
|---|---------|--------|
| 1 | E | Mi |
| 2 | F | Fa |
| 3 | G | Sol |
| 4 | A | La |

### Comportamiento

- **Orden fijo:** A → G → F → E
- **Duración de cada nota:** **1 s**
- **Repetición:** bucle infinito, vuelve a empezar desde A.
- **Referencia de tempo:** metrónomo a **60 BPM** (1 nota por golpe).

## Notas generales

- Ambas manos suenan al mismo tiempo, de forma independiente.
- Las duraciones se expresan en segundos (0.25 ms sería inaudible).

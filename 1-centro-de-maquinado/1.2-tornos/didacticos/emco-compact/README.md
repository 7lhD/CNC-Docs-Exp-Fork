# Emco Compact - Torno Didáctico CNC

## Descripción Breve
El Emco Compact es un torno didáctico diseñado para la enseñanza de los fundamentos del mecanizado CNC. Combina la seguridad de una máquina educativa con la funcionalidad de un control industrial, permitiendo a los estudiantes transicionar suavemente de la teoría a la práctica.

![Emco Compact](/assets/images/emco-amarillo-frontal.jpg)

## Ficha Técnica de Especificaciones

| Parámetro | Especificación | Unidad |
|-----------|---|---|
| Fabricante | Emco | - |
| Modelo | Compact 5 CNC | - |
| Tipo | Didáctico | - |
| Recorrido X | 50 | mm |
| Recorrido Z | 300 | mm |
| RPM Máximo | 2000 | rpm |
| Potencia Motor | 0.5 | kW |
| Voltaje Requerido | 220 | V |

## Seguridad e Información Crítica

{% hint style="danger" %}
**Equipo de Protección Obligatorio (EPP):**
- Gafas de seguridad (ISO 11161)
- Guantes de taller (NO con máquina en movimiento)
- Zapatos de seguridad con punta de acero
{% endhint %}

{% hint style="warning" %}
**Ubicación de Parada de Emergencia:** Botón rojo ubicado en el panel frontal.
**Procedimiento:** Presionar en caso de emergencia, luego girar para desbloquear.
{% endhint %}

## Procedimiento de Encendido

{% stepper %}
{% step title="Verificar Seguridad" %}
Confirma que la cubierta está cerrada y la zona está despejada.
{% endstep %}

{% step title="Conectar Alimentación" %}
Gira la llave de power a la derecha. El panel debe iluminarse.
{% endstep %}

{% step title="Esperar Inicialización" %}
El CNC tarda aproximadamente 30 segundos en auto-diagnosticar.
{% endstep %}

{% step title="Referencia de Ejes" %}
Realiza el procedimiento de "Reference Point" para calibrar los ejes X y Z.
{% endstep %}
{% endstepper %}

## Operación Básica

{% cards %}
{% card title="Modo Manual" description="Operación convencional para refrentado y cilindrado simple" icon="🛠️" %}
{% card title="Modo CNC" description="Ejecución de programas G-Code desde la memoria o PC" icon="💻" %}
{% endcards %}

## Mantenimiento

{% details title="Mantenimiento Diario" %}
- Limpiar virutas de la bancada.
- Verificar nivel de aceite de guías.
{% enddetails %}

## Recursos y Descargas

[Descargar Manual General de Máquinas (PDF)](/assets/pdfs/Maquinas.pdf)

# Optimill F80 - Centro de Fresado CNC

## Descripción Breve
La Optimill F80 es una fresadora CNC compacta y versátil, ideal para la fabricación de piezas prismáticas pequeñas y medianas. Cuenta con un cambiador automático de herramientas y se integra con sistemas CAD/CAM modernos.

![Optimill F80](/assets/images/optimill-f80-fresadora.jpg)

## Ficha Técnica de Especificaciones

| Parámetro | Especificación | Unidad |
|-----------|---|---|
| Fabricante | Optimum | - |
| Modelo | F80 | - |
| Controlador | Siemens 808D | - |
| Recorrido X | 400 | mm |
| Recorrido Y | 230 | mm |
| Recorrido Z | 400 | mm |
| RPM Máximo | 4000 | rpm |
| Herramientas | ATC 10 posiciones | - |

## Requisitos de Aire Comprimido

{% hint style="warning" %}
**Atención:** Esta máquina requiere suministro constante de aire comprimido (6 bar) para el cambio de herramientas.
Verificar que el **Compresor Meba** esté encendido y con presión antes de operar.
{% endhint %}

## Procedimiento de Cambio de Herramienta

{% stepper %}
{% step title="Verificar Presión de Aire" %}
Confirma que el manómetro marca al menos 6 bar.
{% endstep %}

{% step title="Modo MDI" %}
Selecciona el modo MDI en el panel de control.
{% endstep %}

{% step title="Comando de Cambio" %}
Ingresa `T[número] M06` (ej. `T1 M06`) y presiona Cycle Start.
{% endstep %}

{% step title="Verificación Visual" %}
Observa que el brazo cambiador realice el ciclo sin obstrucciones.
{% endstep %}
{% endstepper %}

## Video Tutorial

{% embed url="https://www.youtube.com/watch?v=example" %}
Operación Básica Optimill F80 - Tutorial
{% endembed %}

## Recursos y Descargas

[Descargar Ficha Técnica Optimill F80 (PDF)](/assets/pdfs/optimill f80.pdf)

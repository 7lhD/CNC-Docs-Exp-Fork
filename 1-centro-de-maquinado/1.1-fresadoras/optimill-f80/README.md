# Optimill F80

## Descripción Breve

La Optimill F80 es una fresadora CNC compacta y versátil, ideal para la fabricación de piezas prismáticas pequeñas y medianas. Cuenta con un cambiador automático de herramientas y se integra con sistemas CAD/CAM modernos.

## Ficha Técnica de Especificaciones

| Parámetro    | Especificación    | Unidad |
| ------------ | ----------------- | ------ |
| Fabricante   | Optimum           | -      |
| Modelo       | F80               | -      |
| Controlador  | Siemens 808D      | -      |
| Recorrido X  | 400               | mm     |
| Recorrido Y  | 230               | mm     |
| Recorrido Z  | 400               | mm     |
| RPM Máximo   | 4000              | rpm    |
| Herramientas | ATC 10 posiciones | -      |

## Requisitos de Aire Comprimido

{% hint style="warning" %}
**Atención:** Esta máquina requiere suministro constante de aire comprimido (6 bar) para el cambio de herramientas. Verificar que el **Compresor Meba** esté encendido y con presión antes de operar.
{% endhint %}

## Procedimiento de Cambio de Herramienta

{% stepper %}
{% step %}
Confirma que el manómetro marca al menos 6 bar.
{% endstep %}

{% step %}
Selecciona el modo MDI en el panel de control.
{% endstep %}

{% step %}
Ingresa `T[número] M06` (ej. `T1 M06`) y presiona Cycle Start.
{% endstep %}

{% step %}
Observa que el brazo cambiador realice el ciclo sin obstrucciones.
{% endstep %}
{% endstepper %}

## Video Tutorial

{% embed url="https://www.youtube.com/watch?v=example" %}
Operación Básica Optimill F80 - Tutorial
{% endembed %}

## Recursos y Descargas

\[Descargar Ficha Técnica Optimill F80 (PDF)]\(/assets/pdfs/optimill f80.pdf)

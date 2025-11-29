# GSK CNC210 - Torno Industrial de Producción

## Descripción Breve
El GSK CNC210 es un torno de producción industrial equipado con un controlador GSK 980TDc. Ofrece alta precisión, rigidez y velocidad para operaciones de mecanizado complejas, siendo el estándar para la formación técnica avanzada.

![GSK CNC210](/assets/images/gsk-cnc210-completa.jpg)

## Ficha Técnica de Especificaciones

| Parámetro | Especificación | Unidad |
|-----------|---|---|
| Fabricante | GSK | - |
| Modelo | CNC210 | - |
| Controlador | GSK 980TDc | - |
| Recorrido X | 210 | mm |
| Recorrido Z | 400 | mm |
| RPM Máximo | 3000 | rpm |
| Potencia Motor | 3.7 | kW |
| Voltaje Requerido | 380 | V |

## Seguridad e Información Crítica

{% hint style="danger" %}
**Riesgo de Atrapamiento:** Mantener manos alejadas del plato durante la rotación.
**EPP:** Gafas, zapatos de seguridad y ropa ajustada obligatoria.
{% endhint %}

## Modos de Operación

{% tabs %}
{% tab title="Operación Manual (JOG)" %}
El modo JOG permite mover los ejes manualmente utilizando las teclas de dirección o el volante electrónico (MPG).
1. Seleccionar modo JOG.
2. Elegir eje (X o Z).
3. Presionar +/- para mover.
{% endtab %}

{% tab title="Programación (EDIT)" %}
El modo EDIT permite ingresar y modificar programas G-Code.
1. Seleccionar modo EDIT.
2. Ingresar número de programa (Oxxxx).
3. Escribir bloques de código.
{% endtab %}

{% tab title="Automático (AUTO)" %}
Ejecución continua del programa.
1. Seleccionar modo AUTO.
2. Verificar "Cycle Start" habilitado.
3. Presionar botón verde.
{% endtab %}
{% endtabs %}

## Solución de Problemas

{% details title="Alarma de Presión de Aceite" %}
Verificar el nivel de aceite en el tanque de lubricación automática. Rellenar si es necesario con aceite de guías ISO 68.
{% enddetails %}

{% details title="Error de Límite de Eje (Overtravel)" %}
La máquina ha excedido su recorrido físico.
1. Cambiar a modo Manual.
2. Mantener presionado el botón "Overtravel Release".
3. Mover el eje en dirección opuesta al límite.
{% enddetails %}

## Recursos y Descargas

[Descargar Manual GSK (PDF)](/assets/pdfs/gsk.pdf)

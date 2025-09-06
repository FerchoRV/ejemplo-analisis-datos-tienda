# Descripcion del caso de estudio

Basado en los datos de la carpeta datos-llamadas hacer un informe que contenga lo siguiente.

1. **Reporte llamadas totales por categoria**:Cantidad total de minutops en llamadas contestadas
2. **Reporte llaamdas por agente**:  Cantidad de total de minutos que utilizo un agente.
3. **Generar graficos con el comportamiento de los datos**
4. **Almacenar en documentos csv o excel los reportes o datos relevantes**

## Descripcion de los datos:

Los datos se comportn de la siguiente manera:

1. **fecha**: Fecha de la llamada
2. **fuente**: Quien hizo la llamada es decir es el codigo de la extencion del agente
3. **destino**: El usario final al que llamaron es un numero telefonido
4. **canal origen**: La troncal sip se puede omitir
5. **pin**: canal destino se puede omitir
6. **estado**: registra estado de la llamada entre contestado y no contestado
7. **duracion**: tiempo exacto real de la llamada en minutos y segundos se puede omitir es infromativa
8. **minutos**: tiempo que duro la llamada redondeado superior a cobrar importante.
9. **aplicacion**: no sabe
10. **id**: es el id del registro de la llamada en la base de datos.
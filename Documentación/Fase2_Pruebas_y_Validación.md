# Fase 2: Pruebas y Validación

## Diseño del estudio
El estudio será experimental in-vitro.

## Muestra
La muestra estará conformada por saliva artificial con variaciones de pH y temperatura, las cuales serán medidas con el sensor para la medición continua de pH salival con el sensor Wireless experimental y el potenciómetro. Las mediciones se trabajarán por triplicado de acuerdo con Phlo referido por Choi et al. Los grupos experimentales serán los siguientes:
- 20_2: pH2 a 20 ℃
- 20_3: pH3 a 20 ℃
- 20_4: pH4 a 20 ℃
- 20_5: pH5 a 20 ℃
- 20_6: pH6 a 20 ℃
- 20_7: pH7 a 20 ℃

- 37_2: pH2 a 37 ℃
- 37_3: pH3 a 37 ℃
- 37_4: pH4 a 37 ℃
- 37_5: pH5 a 37 ℃
- 37_6: pH6 a 37 ℃
- 37_7: pH7 a 37 ℃

## Definición operacional de variables
- **pH:** Índice que expresa el grado de acidez o alcalinidad de una disolución. Operacionalmente es la acidez de la saliva artificial medida con el sensor wireless. Variable de tipo cualitativa, nominal politómica. Las categorías son: 2, 3, 4, 5, 6, 7.
- **Temperatura:** Magnitud física que expresa el grado de frío o calor de los cuerpos o del ambiente. Operacionalmente es la temperatura a la que se medirá el pH salival con el sensor Wireless experimental y el potenciómetro. Variable cualitativa, nominal, politómica. Las categorías son: 20 ℃ y 37 ℃.

## Procedimientos y técnicas

### Desarrollo de dispositivo Wireless
Para el desarrollo del dispositivo wireless, se utilizará la metodología VDI 2225 para definir la lista de requerimientos funcionales y no funcionales. Tras formular los módulos necesarios (Energy harvest, transmisión inalámbrica, medición), se procederá a elaborar una matriz de componentes electrónicos, eligiendo la propuesta más adecuada y costo-efectiva. Se trata de un sensor basado en tecnología ISFET, es decir, transistores sensibles a efectos de campo, lo que nos permitirá asegurar que el dispositivo mantenga una escala pequeña que facilite su posterior colocación dentro de un paladar de ortodoncia, similar a la configuración mostrada por Ma et al. El sensor estará acompañado por un LMP91200, usado ampliamente en aplicaciones de detección de pH de baja potencia, y un ATTiny como microcomputadora del circuito de pequeñas dimensiones. Los datos capturados se mostrarán a través de un aplicativo móvil y serán exportados en un archivo tipo texto (.txt). Para la comunicación, se usará tecnología NFC (Near Field Communication), que trata de una tecnología inalámbrica que funciona en la banda de los 13.56 MHz, la cuál no requiere licencia de uso. Una vez culminada la manufactura electrónica del sensor, se realizarán pruebas de laboratorio para establecer la curva de medición y su función de transferencia, así como la exactitud, precisión y margen de error.

### Preparación de saliva
Se preparará saliva artificial a partir de la disolución de 1,6802 g de bicarbonato de sodio (NaHCO3), 0,41396 g de fosfato de sodio monobásico monohidratado (NaH2PO4.H2O) y 0,11099 g de cloruro de calcio anhidro (CaCl2) en suficiente agua desionizada bajo agitación y calentamiento. De ser necesario se ajustará el pH por adición de gotas de solución de ácido clorhídrico. Finalmente, se vertirá la solución a temperatura ambiente a una fiola de vidrio de 1 L y se enrasará con agua desionizada. 

### Medición de pH
La medición del pH se realizará con un potenciómetro (ThermoFisher Scientific Orion Versa Star Pro, EE. UU) y un electrodo de pH de vidrio (Orion™ 8102BNUWP ROSS Ultra™). Antes de cualquier medición el equipo será calibrado, para lo cual se sumergirá el electrodo de vidro en una solución buffer de pH 1,68. La sensibilidad del equipo será programada a 95% hasta obtener el valor 1,68. Seguidamente el electrodo será retirará y lavará con agua destilada y se secará cuidadosamente con papel tissue sin frotarlo. Se repetirá el procedimiento con soluciones a pH 4,01 y 7,00 para finalizar la calibración. Una vez calibrado el equipo se procederá a medir el pH de las diferentes preparaciones de pH de saliva empleando 5 ml de saliva para cada medición. Los pH empleados para las mediciones serán 2, 3, 4, 5, 6 y 7. Se realizarán 3 mediciones por grupo. Para cada lectura se empleará una nueva preparación de saliva en el pH específico. 

### Calibración de la temperatura
Los registros de pH se realizarán a las temperaturas de 20 ℃ y 37 ℃. Para la temperatura de        20 ℃ se programará la temperatura del aire acondicionado del Laboratorio. Para la temperatura de 37 ℃ se empleará un agitador con sensor de temperatura MEDILAB HSC-19T para mantener las soluciones a la temperatura deseada durante las lecturas de pH.

## Plan de análisis
Los datos obtenidos de pH según temperatura empleada para el potenciómetro y el sensor Wireless se almacenarán en una base de datos de Microsoft Office Excel 2010 (Los Angeles, CA, USA). Para el análisis de los datos de precisión (detalle con el que un instrumento o procedimiento puede medir una variable), exactitud (de la medición del instrumento al valor real), error (diferencia entre el valor real y el medido). Se empleará el programa R Studio v.09.1+494 (R Studio, Boston, MA, USA). Se utilizará un intervalo de confianza de 95%. 

## Consideraciones éticas
El presente estudio se ejecutará en el Laboratorio de Materiales Dentales de la Facultad de Estomatología con el apoyo de Ingeniería Biomédica de la Facultad de Ciencias e Ingeniería - UPCH para lo cual se solicitarán los permisos respectivos. Posteriormente se registrará en la Dirección Universitaria de Investigación, Ciencia y Tecnología (DUICT) de la Universidad Peruana Cayetano Heredia. Posterior a la evaluación y registro del proyecto se ejecutará de la presente investigación.



<img width="1000" alt="Captura de pantalla 2024-09-03 a la(s) 01 25 28" src="https://github.com/user-attachments/assets/73420883-e5ea-4e1e-8d2b-be203207161e">

## PROYECTO DE BIODISEÑO 1
# GRUPO 4
Integrantes:
- Villaseca Ho, Sophia Mercedes
- Casanova Reymer, Samara Patricia
- Ayala García, Miriam Lisbeth
- Yupanqui Muñoz, Micaela Sumaq
- Laurente Salazar, Pablo Andres

![IMG_3389](https://github.com/user-attachments/assets/9acc4a91-8a09-4a72-b4fc-0f3a51b0c224)

## PRESENTACIÓN 
Las crisis febriles se definen como episodios convulsivos que ocurren mayormente en niños de entre 6 meses y 5 años en un contexto de fiebre donde la temperatura corporal excede los 38 °C, sin evidencia de infección del sistema nervioso central ni antecedentes de epilepsia.

Estas se clasifican en simples, si duran menos de 15 minutos y no recurren en un día; o complejas si son prolongadas, focales o repetitivas en un lapso de 24 horas. La importancia de una prevención y manejo correctos radica en su impacto directo sobre el bienestar del paciente, permitiendo una adecuada estratificación del riesgo y evitando intervenciones innecesarias. Una clasificación clínica precisa, ajustada a estándares internacionales como los de la American Academy of Pediatrics, es vital para comunicar un pronóstico certero a la familia y reducir la ansiedad parental. Además, un diagnóstico riguroso permite un uso racional de recursos, limitando la realización de exámenes auxiliares costosos o invasivos, como punciones lumbares, EEG o neuroimágenes, a casos estrictamente necesarios. Dado que en la práctica clínica existe una marcada heterogeneidad diagnóstica, la implementación de sistemas de monitoreo objetivos es fundamental para mejorar la eficacia en la identificación de los episodios. 

En el contexto nacional, donde la evidencia sobre características clínicas aún es limitada, la estandarización del abordaje clínico contribuye a optimizar la toma de decisiones en los servicios de emergencia. Un manejo preventivo eficaz no solo implica controlar la temperatura, sino también asegurar un examen físico completo para descartar causas secundarias graves que comprometan la salud del infante. La correcta caracterización de la semiología de la crisis, ya sea focal o generalizada, es el paso clave para determinar el manejo clínico posterior. Al integrar tecnologías de monitoreo, se facilita la obtención de datos precisos sobre la duración y recurrencia, factores críticos para definir la severidad del evento. Esto resulta esencial para evitar errores diagnósticos que conduzcan a tratamientos inadecuados o altas hospitalarias prematuras. 

En última instancia, el bienestar del paciente depende de una respuesta médica organizada que minimice las inconsistencias clínicas y garantice una atención basada en criterios estandarizados y evidencia local relevante. De esta forma, se protege el desarrollo neurológico del niño y se optimiza la calidad de vida de su entorno familiar durante estos episodios críticos. (1)

## PROBLEMÁTICA
Las crisis febriles representan la causa más frecuente de convulsiones pediátricas, afectando del 2% al 5% de niños entre 6 meses y 5 años, lo que justifica la creación de un sistema de monitoreo enfocado en esta población vulnerable. Existe actualmente una gran variabilidad diagnóstica que dificulta distinguir con precisión entre crisis simples y complejas, lo que impacta directamente en el pronóstico y manejo del paciente.

En este contexto, el monitoreo es vital para recolectar datos objetivos sobre la duración de la crisis en minutos y la recurrencia en 24 horas, criterios esenciales que definen si una crisis es compleja cuando dura más de 15 minutos o se repite en un mismo día. 

Además, el registro automatizado de la semiología de la crisis ayudaría a los médicos a evitar errores en la identificación y clasificación de los episodios. Esto es especialmente relevante dado que la evidencia nacional sobre las características clínicas precisas es aún limitada, lo que genera inconsistencias en la práctica de los servicios de emergencia. Al implementar esta tecnología, se facilita una correcta estratificación del riesgo y un uso más racional de recursos diagnósticos costosos como el EEG o las neuroimágenes. 

El monitoreo continuo permitiría detectar signos neurológicos sutiles y asegurar que los criterios de alta hospitalaria se basen en información fidedigna y no solo en reportes subjetivos de los padres. En conclusión, la propuesta tecnológica presentada es una herramienta clave para la estandarización del abordaje clínico y la mejora de la eficacia diagnóstica de las crisis febriles en el Perú. (1)

## PROPUESTA DE SOLUCIÓN 
Para abordar la necesidad de un monitoreo constante y no invasivo del usuario, se propone el desarrollo de un dispositivo biomédico de tipo wearable controlado por un módulo ESP32. Esta solución permite registrar de manera continua la temperatura corporal exacta mediante el sensor MAX30205 y evaluar la postura o posibles caídas del paciente a través del acelerómetro y giroscopio MPU6050. La arquitectura del circuito está pensada para la portabilidad, utilizando una batería recargable optimizada por un cargador TP4056 y un regulador de voltaje. El estado del paciente se visualiza inmediatamente en una pantalla OLED integrada y cuenta con un buzzer para activar alarmas sonoras en caso de lecturas críticas, facilitando una respuesta rápida y una supervisión remota eficiente mediante las capacidades de conectividad del microcontrolador.

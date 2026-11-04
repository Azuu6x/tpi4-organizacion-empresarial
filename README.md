# Sistema de Gestión de Turnos Médicos - Clínica Médica San Martín

# Descripción del Proyecto
Este proyecto consiste en el diseño y planificación de un sistema de información web centralizado para la Clínica Médica San Martín. El objetivo principal es automatizar el proceso de reserva y asignación de citas médicas, optimizando las agendas de los profesionales de las áreas de Pediatría, Cardiología y Clínica General, y disminuyendo significativamente la carga administrativa del personal de secretaría.

# Integrantes (Grupo N° 9)
Azul Belén Rendón

# Objetivos y Metas Cuantitativas
Objetivo General: Desarrollar una plataforma web accesible que centralice la gestión de turnos, agilice la atención y elimine las planillas físicas o archivos manuales.
Tiempo de Respuesta: Confirmación y registro de turnos en la base de datos en un tiempo menor a 1.2 segundos.
Escalabilidad: Soporte óptimo de almacenamiento e historial para hasta 20.000 pacientes activos sin degradar las búsquedas.
Plazo Temporal: Ciclo de desarrollo e implantación completado en un máximo de 9 semanas.

# Historias de Usuario (Backlog Ágil)

# Historia de Usuario 1: Reserva de Citas Online
Como Paciente de la clínica,
Quiero poder ingresar al sistema web, seleccionar una especialidad, un médico y elegir un horario disponible,
Para reservar mi turno de forma autónoma sin necesidad de llamar por teléfono o acudir presencialmente.

# Historia de Usuario 2: Gestión de Agenda Médica
Como Personal de Atención al Paciente (Secretaría),
Quiero visualizar de forma clara el cronograma de atención de turnos y validar la disponibilidad de los médicos en tiempo real,
Para registrar solicitudes presenciales y evitar la superposición de citas.

# Historia de Usuario 3: Control Operativo de Turnos
Como Director Médico / Administrator del Sistema,
Quiero modificar el estado de las citas (Pendiente, Atendido, Cancelado) y verificar qué médicos están activos o de licencia,
Para auditar la calidad de atención y coordinar eficazmente el trabajo del personal de salud.

# Mecanismos de Control y Estándares de Desempeño
Para asegurar la calidad y el éxito de la implantación del prototipo funcional en la semana 9, se establecen los siguientes indicadores de auditoría técnica:

1) Auditoría de Tiempos de Respuesta (Performance): Pruebas de carga automatizadas mediante la inyección de datos ficticios en la Semana 8 de pruebas de calidad para verificar que las transacciones sigan manteniéndose por debajo del umbral crítico de 1.2 segundos.
2) Tasa de Error en el Flujo de Procesos (BPMN): Monitoreo del porcentaje de solicitudes que caen en la compuerta de "No hay disponibilidad" para evaluar la efectividad de la asignación automática de horarios alternativos propuestos por el sistema.
3) Consistencia y Atomicidad de Datos: Verificación de la integridad referencial en la base de datos para asegurar que cada registro en la entidad TURNO esté perfectamente vinculado a un id de la entidad PACIENTE y un id de la entidad MEDICO, bloqueando cualquier intento de duplicación de turnos en una misma combinación de fecha, hora y profesional.


# Declaración de Uso de IA
En cumplimiento con las normas de la cátedra, se declara el uso de Inteligencia Artificial en este trabajo:

Prompts utilizados: 
"Ayudame a mejorar la redacción de los objetivos y metas de un sistema de turnos médicos."
"Cuáles son las amenazas más comunes al digitalizar un consultorio médico."
 Control humano: Se revisaron todas las sugerencias de la IA para corregir errores y asegurar que se adapten a la realidad de la Clínica Médica San Martín y a los diagramas realizados.

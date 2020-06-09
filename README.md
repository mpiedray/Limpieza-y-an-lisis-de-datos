# Limpieza-y-análisis-de-datos
En esta práctica hemos trabajado con el dataset obtenido de https://www.kaggle.com/jessemostipak/hotel-booking-demand

Donde trabajos con un dataset que recoge las reservas hecha a los hoteles, reservas que son canceladas y reservas que han sido efectuadas
el dataset consta de 33 variables que limpiamos y reducimos hasta quedarnos con un total de 13 y de las cuales estraemos informacion como:

Existe una relacion entre el precio y los meses del año?
Varia la Tarifa diaria promedio en funcion del hotel que se elija?
varia la Tarifa diaria promedio en funcion del numero de personas adultas que haga las reserva?

Estas y otras preguntas son las que intentamos responder con el estudio de este dataset.

## Resumen de variables y explicación de cada una de ellas

- Hotel :Hotel (H1 = Resort Hotel or H2 = City Hotel)
-  Is_canceled:  Indica si la reserva fue cancelada (1) o no (0)
Lead_time: Número de días transcurridos entre la fecha de entrada de la reserva en sistema de gestión de reservas (PMS) y la fecha de llegada
Arrival_date_year: Año
Arrival_date_month: Mes
Arrival_date_week_number: Día de la semana
Arrival_date_day_of_month: Día del mes en el que entró en el hotel
Stays_in_weekend_nights: Número de noches de fin de semana (sábado o domingo) que el huésped se hospedó o reservó para quedarse en el hotel
Stays_in_week_nights: Número de noches entre  semana (Lunes a viernes) que el huésped se hospedó o reservó para quedarse en el hotel
Adults: Número de adultos
Children:  Número de niños.
Babies: Número de bebes.
Meal: Type of meal booked: Las categorías se presentan en paquetes estándar de comidas de hospitalidad: Indefinido / SC - sin paquete de comidas; BB -
Alojamiento y desayuno; HB - Media pensión (desayuno y otra comida, generalmente cena); FB - Pensión completa (desayuno, almuerzo y cena).
Country: País de origen
Market_segment: Designación del segmento de mercado. En categorías, el término "TA" significa "Agentes de viajes" y "TO" significa "Operadores turísticos"
Distribution_channel: Canal de distribución de reservas. El término "TA" significa "Agentes de viajes" y "TO" significa "Operadores turísticos"
Is_repeated_guest:Valor que indica si el nombre de la reserva era de un huésped repetido (1) o no (0)
Previous_cancellations: Número de reservas anteriores que el cliente canceló antes de la reserva actual
Previous_bookings_not_canceled: Número de reservas anteriores no canceladas por el cliente antes de la reserva actual
Reserved_room_type: Código de tipo de habitación reservado. El código se presenta en lugar de la designación por razones de anonimato.
Assigned_room_type: Código para el tipo de habitación asignada a la reserva. A veces, el tipo de habitación asignada difiere del tipo de habitación reservada debido
a razones de operación del hotel (por ejemplo, sobreventa) o por solicitud del cliente. El código se presenta en lugar de la designación por razones de anonimato.
Booking_changes:Número de cambios / modificaciones realizados en la reserva desde el momento en que se ingresó en el PMS (sistema de gestión de reservas) hasta el
momento del check-in o cancelación.
Deposit_type: Indicación de si el cliente realizó un depósito para garantizar la reserva. Esta variable puede asumir tres categorías: Sin depósito: no se realizó
ningún depósito; Sin reembolso: se realizó un depósito por el valor del costo total de la estadía; Reembolsable: se realizó un depósito con un valor por debajo del costo total de la estadía.
Agent: Identificación de la agencia de viajes que realizó la reserva
Company: Identificación de la empresa / entidad que realizó la reserva o responsable de pagar la reserva. Se presenta la identificación en lugar de la designación por razones de anonimato
Days_in_waiting_list: Número de días que la reserva estuvo en la lista de espera antes de ser confirmada al cliente
Customer_type: Tipo de reserva, asumiendo una de cuatro categorías: Contrato: cuando la reserva tiene una asignación u otro tipo de contrato asociado; Grupo: cuando la reserva está
asociada a un grupo; Transitoria: cuando la reserva no forma parte de un grupo o contrato, y no está asociada a otra reserva transitoria; Parte transitoria: cuando la reserva es
transitoria, pero está asociada a al menos otra reserva transitoria


Adr: Tarifa diaria promedio según se define dividiendo la suma de todas las transacciones de alojamiento por el número total de noches de estadía
Required_car_parking_spaces: Número de plazas de aparcamiento requeridas por el cliente.
Total_of_special_requests: Número de solicitudes especiales realizadas por el cliente (por ejemplo, cama doble o piso alto)
Reservation_status: Último estado de la reserva, asumiendo una de tres categorías: Cancelada: la reserva fue cancelada por el cliente; check-out: el cliente se ha registrado pero
ya se ha ido; No-Show: el cliente no hizo el check-in e informó al hotel del motivo.
Reservation_status_date: Fecha en la que se estableció el último estado. Esta variable se puede usar junto con el Estado de reserva para comprender cuándo se canceló la reserva
o cuándo el cliente realizó el check-out del hotel


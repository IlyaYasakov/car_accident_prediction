# car_accident_prediction
**Необходимо построить модель для предсказания попадения в ДТП автомобиля, забронированного в каршеринговой компании.**
# Про данные
В качестве данных используются три таблицы из базы данных.
## Описание таблиц
- **collisions** - общая информация о дтп
- **parties** - информация об участниках дтп
- **vehicles** - информация о пострадавших машинах
## Описание данных
- **collisions**
  - case_id - идентификационный номер в базе данных
  - county_city_location - номер географических районов, где произошло дтп
  - county_location - названия географических районов, где произошло дтп
  - distance - расстояние от главной дороги (метры)
  - direction - направление движения
  - intersection - является ли место происшествия перекрестком
  - weather - погода в момент происшествия
  - location_type - тип дороги
  - collision_damage - серъезность происшествия
  - party_count - количество участников
  - primary_collision_factor - основной фактор аварии
  - pcf_violation_category - категория нарушения
  - type_of_collision - тип аварии
  - motor_vehicle_involved_with - дополнительные участники дтп
  - road_surface - дорожное покрытие
  - road_condition - состояние дороги
  - lighting - освещение
  - control_device - устройство управления
  - collision_time - время происшествия
  - collision_date - дата происшествия
- **parties**
  - id
  - case_id
  - party_number
  - party_type
  - at_fault
  - insurance_premium
  - party_sobriety
  - party_drug_physical
  - cellphone_in_use
- **vehicles**
  - id
  - case_id
  - party_number
  - vehicle_type
  - vehicle_transmission
  - vehicle_age

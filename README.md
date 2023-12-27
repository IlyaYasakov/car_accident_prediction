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
  - case_id
  - county_city_location
  - county_location
  - distance
  - direction
  - intersection
  - weather
  - location_type
  - collision_damage
  - party_count
  - primary_collision_factor
  - pcf_violation_category
  - type_of_collision
  - motor_vehicle_involved_with
  - road_surface
  - road_condition
  - lighting
  - control_device
  - collision_time
  - collision_date
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

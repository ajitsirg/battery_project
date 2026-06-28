# Event Topology

## Kafka Topics
- auth.events
- battery.events
- station.events
- inventory.events
- swap.events
- payment.events
- notification.events
- telemetry.events

## MQTT Topics
- battery/{battery_id}/telemetry
- battery/{battery_id}/faults
- station/{station_id}/health
- station/{station_id}/inventory
- charger/{charger_id}/status

## Event Flow Example
Rider Login -> Auth Event -> Station Lookup -> Battery Reservation -> Swap Completed -> Payment Captured -> Notification Sent

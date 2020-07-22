# stm32_temperature_sensitive_tower_fan
This project makes use of the stm32f446re microcontroller, a DHT11 temperature sensor, a circuit relay, and a tower fan. It initializes the DHT11 sensor and turns on or off a circuit relay, depending on current temperature read. If the relay is on due to a certain high temperature, the fan is powered up the temperature drops below 34 degrees C.

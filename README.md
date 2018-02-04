# New types for Apple HomeKit

Hello dear developer community. Let's clean up the new types of HomeKit.
While Apple has forgotten about our needs, everyone adds their services and characteristics as he wants.
At the same time, in every project or even a HometKit-rady device - completely different data types and storage locations can be used - for the same kinds of data.
As a result, it can not be controlled. Please let's stick to a single standard until Apple remembers us.

---

### About

The principles of Apple were taken as the basis of the library.

XXXXXXXX-0000-1000-8000-0026BB765291 - Standard apple key for services and characteristics

We use

XXXXXXXX-0000-2000-8000-0026BB765291 - For services
XXXXXXXX-000C-1000-8000-0026BB765291 - For characteristics

Let's develop and expand this library.

---

### Changelog

#### 1.0.0
- New service PowerMeter with characteristics: Volts, Amperes, Watts, VoltAmperes, KilowattHours, KilowattVoltAmpereHour
- New service AtmosphericPressureSensor with characteristics: AtmosphericPressureLevel
- New service NoiseSensor with characteristics: NoiseDetected, NoiseLevel

# Laser-Ldr-Alarm-System
This low-cost security system uses a laser and Light-Dependent Resistor (LDR) to detect door openings and trigger alarms. The signal is processed via a comparator and 555 Timer IC to trigger a buzzer and LED for audible and visual alerts. It’s designed to provide simple, reliable, and affordable home security, especially for vulnerable groups like elderly individuals living alone.

# Working Principle:
The laser shines on the LDR, keeping the system passive. When the door opens, the laser beam is interrupted, causing the LDR’s resistance to change. This triggers a comparator, activating a 555 Timer IC to sound an alarm (buzzer) and light an LED.

# Components:
Laser: Illuminates the LDR and keeps the system passive.
LDR: Detects changes in light intensity when the laser is interrupted.
Comparator: Compares the LDR’s signal to a reference voltage.
555 Timer: Triggers the alarm system when activated. It works in astable configuration.
Alarm (Buzzer + LED): Provides audible and visual alerts.

# Circuit Overview:
When the laser beam is interrupted, the LDR’s resistance increases, altering the comparator’s output. This activates the 555 Timer, producing a signal that drives the buzzer and LED.

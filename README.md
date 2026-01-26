# Home Assistant Medication Manager

- Multi-Medikamenten Blueprint
- 2x täglich Einnahme
- iOS Push mit Buttons
- Alexa & Home Assistant Assist
- NFC-Tag Auffüllung
- Bestands- und Rezept-Reminder

## Installation

1. Ordner `packages` in HA aktivieren (`configuration.yaml`):

```yaml
homeassistant:
  packages: !include_dir_named packages

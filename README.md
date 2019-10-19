# Installation
Copy all files to `/config/custom_components/airly`.
You might need to create `custom_components` and `airly` directories yourself.

# Setup
In your `configuration.yaml`:
```
sensor:
  - platform: airly
    latitude: 52.2312146
    longitude: 20.9762476
    api_key: 'YOUR_API_KEY'
```

# Api-Key
Mandatory. Register at [Airly Developer](https://developer.airly.eu/login) to get one.

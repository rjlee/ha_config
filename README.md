# Home Assistant Configuration

This is my Home Assistant Configuration.  It's constructed using the <a href="">packages</a> approach for the integrations, sensors and automations and then retains the <a href="https://www.home-assistant.io/lovelace/">Lovelace</a> UI for managing dashboards:

* Configuration - <a href="/packages">`/packages`</a>
* UI - <a href="/.storage">`/.storage`</a>

# Main Features

These are some of my favourite automations/integrations/devices:

## Child Sleep Sensor

<img src="/docs/images/sleep_sensor.png" />

Uses a combination of sensors (<a href="https://www.withings.com/us/en/sleep">withings sleep matt</a>, <a href="https://www.samsung.com/us/support/owners/product/motion-sensor-version-2">smartthings motion sensor</a>, <a href="https://github.com/rjlee/ha_noise_sensor">pi noise sensor</a>) to detect if my son is asleep.

See <a href="/packages/areas/upstairs/bedroom1/noise_sensor">`/packages/areas/upstairs/bedroom1/noise_sensor`</a>.

## Hot Tub Water Quality Sensor

<img src="/docs/images/hot_tub_sensor.png" />

For the laz-y-spa hot tub, I built my own <a href="https://github.com/rjlee/grove_orp_exporter">water quality sensor</a> so I know when to add chemicals to the tub.  The hot tub is also automated via <a href="https://github.com/B-Hartley/bruces_homeassistant_config/tree/master/packages/areas/garden/hottub-lay-z-spa">lay-z-spa hottub</a>.

## Dog friendly auto vacuuming

Using a waterproof <a href="https://www.thetileapp.com/en-us/store/tiles/sticker">tile tracker</a>, home assistant knows when the dog is out for a walk and will start cleaning the house with the <a href="https://www.ecovacs.com/us/deebot-robotic-vacuum-cleaner/DEEBOT-OZMO-T8-AIVI">ecovacs</a> vacuums, plus do a quick spot clean shortly after she returns.

See <a href="/packages/areas/downstairs/kitchen/vacuum/">`/packages/areas/downstairs/kitchen/vacuum/`</a>.

## Automating Bedtime

Coming soon

## School reminders

Coming soon

## Brush your teeth reminder

Coming soon


## Inspired by

* https://github.com/B-Hartley/bruces_homeassistant_config

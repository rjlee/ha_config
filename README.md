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

## Brush your teeth reminder

<img src="/docs/images/toothbrush_sensor.png" />

This one is a little silly, but I'm terrible at remembering to brush my teeth in the evening.  Using an <a href="https://www.oralb.co.uk/en-gb/product-collections/electric-toothbrushes#series=genius">Oral B Genius toothbrush</a>, a <a href="https://www.samsung.com/uk/smartthings/outlet/smartthings-smart-plug-gp-wou019bbdwg/">smartthings power monitoring plug</a> and <a href="https://github.com/zewelor/bt-mqtt-gateway">bt-mqtt-gateway</a>, I get a reminder from the Alexa next to my bed if I forget to do it before going to bed.

See <a href="/packages/areas/upstairs/upstairs_bathroom/">`/packages/areas/upstairs/upstairs_bathroom/`</a>.

## Dog friendly auto vacuuming

Using a waterproof <a href="https://www.thetileapp.com/en-us/store/tiles/sticker">tile tracker</a>, home assistant knows when the dog is out for a walk and will start cleaning the house with the <a href="https://www.ecovacs.com/us/deebot-robotic-vacuum-cleaner/DEEBOT-OZMO-T8-AIVI">ecovacs</a> vacuums, plus do a quick spot clean shortly after she returns.

See <a href="/packages/areas/downstairs/kitchen/vacuum/">`/packages/areas/downstairs/kitchen/vacuum/`</a>.

## Automating Kids Bedtime

Using <a href="https://www.veluxusa.com/products/smart-home/velux-active">Velux Active Blinds</a>, <a href="https://www.kasasmart.com/us/products/smart-plugs">Kasa Plugs</a> and scheduled powering off of devices, lots of the repetitive kids bedtime tasks are removed (other than tidying clothes !).

See <a href="/packages/areas/upstairs/bedroom1/automation_bedroom1_good_morning_and_night.yaml">`/packages/areas/upstairs/bedroom1/automation_bedroom1_good_night.yaml`</a> and <a href="/packages/areas/upstairs/spare_bedroom/automation_spare_room_xbox_scheduled_off.yaml">`/packages/areas/upstairs/spare_bedroom/automation_spare_room_xbox_scheduled_off.yaml`</a> for examples.

## School reminders

Some simple reminders for my son, to <a href="/packages/areas/upstairs/bedroom1/automation_bedroom1_wake_up_reminder.yaml">wake up</a> and then <a href="/packages/areas/upstairs/spare_bedroom/automation_spare_room_leave_reminder.yaml">leave for school</a> via the Alexa.

## Inspired by

* https://github.com/B-Hartley/bruces_homeassistant_config

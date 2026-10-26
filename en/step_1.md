
The Sense HAT has two sensors capable of reading the ambient temperature: the humidity sensor and the pressure sensor. `get_temperature_from_humidity` reads the temperature from the humidity sensor (`get_temperature` is a short version of the same command). `get_temperature_from_pressure` reads the temperature from the pressure sensor.

- In a Python file, enter the following code:

    ```python
    from sense_hat import SenseHat

    sense = SenseHat()
    sense.clear()

    temp = sense.get_temperature()
    print(temp)
    ```

    <iframe src="https://editor.raspberrypi.org/en/embed/viewer/rpi-sensehat-temperature-example" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

    [Open this code in the Code Editor](https://editor.raspberrypi.org/en/projects/rpi-sensehat-temperature-example){:target="_blank"}

- You should see something like this:

    ```bash
    28.6293258667
    ```



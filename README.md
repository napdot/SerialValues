# SerialValues
Simple python class for reading serial input

## Usage

Starting the class

```python
mySerialValues = SerialValues(port='/dev/ttyS#', baudrate=9600 )
```

For reading serial.

```python
content = SerialValues.read_serial
```

For reading serial with time since reading execution

```python
content, content_time = SerialValues.read_serial_and_time
```


#!/bin/bash

# 1. Crear los Sinks (Salidas virtuales)
pactl load-module module-null-sink sink_name=System sink_properties=device.description=System
pactl load-module module-null-sink sink_name=Discord sink_properties=device.description=Discord
pactl load-module module-null-sink sink_name=Games sink_properties=device.description=Games
pactl load-module module-null-sink sink_name=Browser sink_properties=device.description=Browser

echo "Canales de audio creados exitosamente."

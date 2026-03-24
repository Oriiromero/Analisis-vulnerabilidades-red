# Análisis de Tráfico y Mitigación de Escaneos de Red (NIST & ENS)

## Simulación de una fase de reconocimiento (Footprinting) sobre un activo vulnerable (Metasploitable2) y su posterior detección mediante análisis forense de red con Wireshark. El proyecto demuestra la capacidad para identificar escaneos sigilosos (TCP SYN Stealth Scan), interpretar el comportamiento del stack TCP/IP y proponer medidas de mitigación alineadas con el Esquema Nacional de Seguridad (ENS) de España y la normativa ISO 27001.

## Tecnologias usadas: Linux (Ubuntu), Metasploitable2, Nmap, Wireshark, UFW.

## Habilidades demostradas: 
  * Análisis de protocolos TCP/IP.
  * Identificación de escaneos "Stealth".
  * Propuesta de controles basados en el ENS (Esquema Nacional de Seguridad).

## Troubleshooting: Durante las pruebas de mitigación con UFW en localhost, se observó que el sistema prioriza el tráfico de loopback, resultando en estados 'Closed' en lugar de 'Filtered'. Este comportamiento subraya la importancia de validar las reglas de firewall desde hosts externos para confirmar la efectividad de las políticas de denegación (DROP) en entornos productivos.

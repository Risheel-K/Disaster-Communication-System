# Disaster-Communication-System
An XBee-based disaster communication system enabling 2 km connectivity using mesh networks, Arduino modules, and onboard ML for shortest path prediction. It supports Bluetooth messaging, voice modules, and internet-based alerts, ensuring communication without cellular/internet reliance.

In the wake of natural disasters such as floods, earthquakes, or cyclones, traditional communication systems like mobile networks often become non-functional due to infrastructure collapse. This disruption hampers rescue operations and delays emergency responses, putting countless lives at risk. Our project presents a solution rooted in the principle: “Nobody Should Be Left Behind.”

We propose a resilient, long-range, and independent communication system using XBee S2C Pro modules that create a self-sustaining mesh network. These modules transmit data using RF frequencies, hopping messages between nodes without requiring internet or cellular towers. The system supports coverage of up to 20 km, allowing rescue teams and affected individuals to communicate seamlessly even in the most remote or obstructed environments.

The project integrates:

    Arduino-based microcontrollers to manage communication protocols and control logic.

    A Bluetooth module (HC-12) to connect the communication module with mobile devices via a dedicated app.

    A voice module that allows users to send pre-recorded or real-time voice messages in situations where typing is impractical.

    Internet-based messaging support for hybrid communication when connectivity is available.

    A machine learning model deployed onboard to analyze real-time data and suggest the shortest or safest path for rescue operations.

    Solar-powered rechargeable battery units, ensuring uninterrupted power supply for prolonged field use.

This modular communication unit is not only portable but also scalable to build large, decentralized networks. It supports real-time data exchange, weather-based alerts, and team coordination without reliance on fragile infrastructure.
Core Components:

    XBee S2C Pro

    XBee Explorer Board

    Arduino Microcontroller

    Rechargeable Battery + Solar Panels

    Voice Module

    Bluetooth Module (HC-12)

    Mobile App (Flutter + Android Studio)

    ML Model Integration (for path prediction)

Innovation and Novelty:

Unlike traditional systems that either require working networks or are limited to alerting before disasters, our solution works during and after disasters, when communication is most crucial. It creates a self-healing RF mesh, avoids single-point failures, and includes multiple fallback communication methods (voice, Bluetooth, app-based internet). The sustainability aspect is enhanced using solar-powered units.
Advantages:

    Reliable communication without cellular/internet

    Long-range, non-line-of-sight coverage (up to 20 km)

    Enables faster and coordinated rescue operations

    Reduces the chances of casualties

    Compact, portable, and field-deployable

    Cost-effective and scalable

    Real-time data, voice, and message support

Applications:

    Flood-affected zones

    Earthquake or landslide areas

    Remote village rescue operations

    Temporary military or relief camps

    Wildfire zones and coastal evacuation missions

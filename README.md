# 2.4 GHz Wireless Transceiver for UAV Control

## Overview
This project implements a real-time wireless transceiver system for UAV control using LoRa-based RF communication. The system supports multi-channel PWM generation, SBUS, and PPM outputs for direct integration with flight controllers.

Designed for low-latency, high-reliability UAV communication in real-time environments.

## System Architecture
- STM32 Microcontroller
- LoRa RF Transceiver Module
- SPI-based RF communication
- Multi-channel PWM generator
- SBUS and PPM protocol generation

## Key Features
- Supports 10 independent PWM channels
- SBUS and PPM signal generation
- Low-latency RF communication
- High reliability signal encoding
- Modular firmware architecture

## Communication Flow
Transmitter:
- Input → Channel Encoding → RF Packet → LoRa Transmission

Receiver:
- RF Packet → Decoding → PWM / SBUS / PPM Output → Flight Controller

## Technologies Used
- Embedded C
- STM32 HAL / LL
- SPI, I2C, UART
- LoRa RF protocol
- Real-time timer-based PWM generation

## System Highlights
- Achieved low-latency UAV control link
- High signal integrity across long distances
- Robust RF packet handling
- Precise PWM and SBUS signal timing

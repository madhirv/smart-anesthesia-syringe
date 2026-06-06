# Smart Anesthesia Syringe

This repository contains documentation and presentation files for my undergraduate embedded systems project titled **Smart Anesthesia Syringe**.

## Project Overview

The Smart Anesthesia Syringe is an Arduino UNO-based embedded system designed to assist in anesthesia delivery during long-duration surgical procedures. The system monitors physiological parameters such as heartbeat and temperature and allows keypad-based anesthesia level input. Based on the configured level, the system controls a syringe mechanism using a DC motor and L298N motor driver.

## Objective

- Design an anesthesia syringe system with heartbeat and temperature monitoring.
- Use embedded systems to support accurate drug dosage delivery.
- Enable keypad-based dynamic anesthesia level setting.
- Display patient parameters using an LCD display.
- Reduce manual monitoring errors during long surgical procedures.

## Hardware Components

- Arduino UNO
- Power supply
- Heartbeat sensor
- LM35 temperature sensor
- Keypad
- Limit switch
- L298N motor driver
- DC motor
- LCD display
- Syringe mechanism

## Software Used

- Embedded C
- Arduino IDE
- Express SCH / circuit design tools

## System Working

The Arduino UNO acts as the main controller. It receives input from the heartbeat sensor, temperature sensor, keypad, and limit switch. The monitored values are displayed on the LCD module. Based on the anesthesia level entered through the keypad, the Arduino controls the DC motor through the L298N motor driver to operate the syringe mechanism.

## Block Diagram

The system block diagram includes sensor inputs, Arduino UNO controller, motor driver, DC motor, anesthesia syringe, LCD driver, and LCD display.

## Repository Contents

- Project documentation
- Project presentation
- Block diagram image

## Future Scope

- Add fall detection support.
- Integrate additional health monitoring parameters such as blood pressure and glucose sensors.
- Improve automation and safety monitoring for clinical use.

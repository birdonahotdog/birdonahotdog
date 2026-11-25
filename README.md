# Hi, I'm Anshu Raj

Electronics and Communication Engineering graduate focused on **embedded firmware**. I write C for the ESP32 using ESP-IDF and FreeRTOS, and I like the parts of the job where software meets real hardware: interrupts, concurrency, and debugging from logs.

Open to embedded firmware roles in Bengaluru.

## What I work with

- **Languages:** C, Python
- **Firmware:** ESP-IDF, FreeRTOS (tasks, queues, mutexes, task notifications, core pinning)
- **Peripherals and protocols:** GPIO, interrupts, UART, I2C, SPI, PWM, ADC
- **Tools:** idf.py / CMake, GCC, Git, Linux, VS Code

## Featured project

**[esp32-telemetry-capstone](https://github.com/birdonahotdog/esp32-telemetry-capstone)**: dual-core ESP32 firmware where a UART task on core 0 feeds a lock-free SPSC ring buffer, drained by an LCD task on core 1, with a mutex-protected I2C display and an interrupt-driven, debounced button. Built from custom ring-buffer, I2C LCD and GPIO drivers, each as its own ESP-IDF component.

## Also built

- **Dual-track railway crossing controller:** event-driven ESP32 firmware that runs servo gates for two independent train directions, with IR + vibration sensor validation to suppress false triggers.

## Currently

Going deeper on FreeRTOS and low-level C, and writing up my projects with clear READMEs.

## Contact

- Email: [anshuraj0601@gmail.com](mailto:anshuraj0601@gmail.com)
- LinkedIn: [linkedin.com/in/AnshuRaj16](https://linkedin.com/in/AnshuRaj16)

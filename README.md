# satsHIVE clock
DIY Bitcoin clock for LILYGO® TTGO T-Display ESP32

## The idea for the clock
So we all know a famous clock that everyone wants to have in its hands. I don't need to name it. :)
In the end, I decided to build my clock on the cheap. You see the result below with the T-Display and a few lines of code that I played with while learning.

![satsHIVE-clock](satsHIVE-clock.jpeg)

## Required hardware

* Display/Controller: [LILYGO® TTGO T-Display ESP32](https://www.aliexpress.com/item/33048962331.html)
* Battery: QL902030 3.7v (or other alternative)

## Configuration

- Arduino IDE - You should use TTGO LoRa32-OLED V1 as a board in the IDE. The T-Display don't have it's own record yet.

- Wireless - The board can connect to a wireless network to sync the time and data we need for the clock.

- Screen refresh - Currently, the on-screen data is being refreshed at predefined intervals in "// Loop" part. This means that the time on the screen may be a bit off.

## To-Do
- [ ] Use better display positioning for the text
- [x] Connect and Disconnect Wi-Fi only to update readings to preserve battery life
- [ ] Find a better source for reading data from (currently Binance)
- [ ] Add block height info to the display
- [ ] Switch screens with the buttons (still not sure if possible at all)

**All feedback and suggestions are welcome.** You could either comment here or reach out to me on [Twitter](https://twitter.com/satsHIVE) or [Telegram](https://t.me/satsHIVE).
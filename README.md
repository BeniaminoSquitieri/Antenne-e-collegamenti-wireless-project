# Wi-Fi Network Analysis and Optimization

## Project Overview

This project analyzes and optimizes the Wi-Fi network coverage in a household, focusing on signal strength, interference, and signal-to-interference ratio (SIR) across different areas of the home. The study was conducted using a dual-band router and various tools to measure signal levels and optimize Wi-Fi coverage using a **Powerline extender**.

## Household Layout

- Location: Sarno (SA), near the town center.
- Size: Approx. 70m².
- Rooms: 2 bedrooms, kitchen, living room, bathroom, and a corridor.

The house is in a densely populated area, leading to potential **interference** from neighboring Wi-Fi networks, especially during peak hours in the evening.

## Equipment and Setup

### Internet Connection
- **Connection Type**: FTTH (Fiber to the Home), approx. 100 meters from the cabinet.
- **Router**: TIM Fiber Modem/Router, supporting dual-band Wi-Fi (2.4 GHz and 5 GHz), 1000 Mbps on FTTC technology, and 4 Gigabit Ethernet LAN ports.

### Devices Used
- **Laptop**: Asus TUF Gaming FX505G with an Intel Wireless-AC 9462 network card supporting the following Wi-Fi standards: 802.11b, 802.11g, 802.11n, 802.11a, and 802.11ac.
- **Powerline Adapter**: To extend signal coverage into weak areas, particularly the bedroom and balcony.

## Initial Signal Analysis

### Signal Strength (Signal Level)
The Wi-Fi signal was analyzed for both the 2.4 GHz and 5 GHz bands. Results show that:
- The **5 GHz** band provides good coverage in the kitchen and nearby areas, but weakens significantly towards the bedrooms, with a minimum of **-80 dBm** in the most distant room.
- The **2.4 GHz** band has a wider coverage range but slower data rates. It performed better in areas far from the router, such as the balcony, though signal strength still dropped to **-80 dBm** in some areas.

### Signal-to-Interference Ratio (SIR)
- The **2.4 GHz band** showed significant interference near the bedrooms due to neighboring networks operating on the same channel.
- The **5 GHz band** had less interference and maintained better SIR values, especially in the living room and bathroom.
- The **Discover** feature of the Netspot software helped identify other networks operating on the same channels.

## Problem Identification
- **Weak Signal Areas**: Bedrooms, especially near the balcony.
- **Interference**: High interference in the 2.4 GHz band due to neighboring Wi-Fi networks, especially during peak usage hours in the evening.

## Optimization Strategy

### Proposed Solution
To improve signal strength, especially in the weak areas, a **Powerline extender** was introduced. The extender was positioned near the boundary between the bedroom and the corridor, where signal strength from the main router was low.

## Results After Optimization

### Signal Level
- **2.4 GHz Band**: The Powerline extender significantly improved signal strength in the bedroom and balcony, with signal levels increasing to **-35 dBm** in the critical areas.
- **5 GHz Band**: No significant changes were observed, as the Powerline works only in the 2.4 GHz band. However, the stronger 2.4 GHz signal provided adequate coverage where the 5 GHz signal was weak.

### Signal-to-Interference Ratio (SIR)
- The addition of the Powerline extender had a minimal impact on interference, as the 2.4 GHz band became more utilized. However, the increase in signal strength outweighed the interference.
- **Overlapping Channels**: The interference slightly increased in areas near the extender, but this was mitigated by the overall improvement in signal levels.

### Frequency Band Coverage
- The **dual-band coverage** improved, with mixed frequencies now reaching more areas of the house, especially in the bedrooms.

### PHY Mode Coverage
- The entire apartment is now fully covered with **802.11ax**, providing the latest Wi-Fi standards for both speed and range, especially after the addition of the Powerline.

## Conclusion

The installation of the Powerline extender significantly improved Wi-Fi coverage in previously weak areas, such as the bedrooms and balcony. While there was a slight increase in interference due to the addition of a new device, the overall improvement in signal strength was beneficial. The Wi-Fi network now provides stable coverage throughout the house, allowing for consistent connectivity in all rooms.

### Future Improvements
- **Channel Optimization**: Adjust router and extender channels to reduce interference.
- **5 GHz Extension**: Consider adding a 5 GHz extender to further improve coverage in the distant areas of the house.

---

## Contact Information

- **Author**: Beniamino Squitieri (University of Salerno)
- **Email**: bennibeniamino@gmail.com

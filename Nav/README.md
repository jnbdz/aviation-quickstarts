<img src="assets/nav.webp" alt="Aviation Nav" style="width: 380px;" align="right">

# Nav | Aviation | Quickstarts

## Enroute Charts
- Enroute Charts - High & Low Altitude
- https://products.navcanada.ca/shop-ifr/Enroute-Charts/
- https://products.navcanada.ca/HI56.html

## Documents That Are Needed

> **!IMPORTANT!** These documents change over time. Keep up with the changes on: https://www.navcanada.ca/

- Designated Airspace Handbook (DAH)
  - [Documents](./Documents/dah20240125.pdf)
  - [Operational Guides | Aeronautical Information | Nav Canada](https://www.navcanada.ca/en/aeronautical-information/operational-guides.aspx#093dcf9f312e43df922dec86e7f295d7)
- Canada Flight Supplement (CFS)
  - [Canada Flight Supplement (CFS) | Nav Canada](https://products.navcanada.ca/shop-vfr/Canada-Flight-Supplement/) - Purchase is required (paper or PDF)
- Canadian Airport Charts (CAC)
  - [Documents](./Documents/cac_05jan.pdf)
  - [Operational Guides | Aeronautical Information | Nav Canada](https://www.navcanada.ca/en/aeronautical-information/operational-guides.aspx#093dcf9f312e43df922dec86e7f295d7)

## Tutorials
- [Navigation Planning | Runup.ca](https://www.runup.ca/topic/navigation-log/)

## CX-3
### Rhumb Line
> A **rhumb line** (**loxodrome**) is a path on the Earth's surface that crosses all meridians at the same angle, maintaining a constant compass bearing. It represents a straight line on a Mercator projection map and is used in navigation for its simplicity in following a steady course.

#### Introduction
The Rhumb Line function on the CX-3 Flight Computer allows you to calculate the distance and true course between two geographic points (waypoints) along a path of constant compass bearing. This is useful for navigation when you want to maintain a steady heading without adjusting for the Earth's curvature over short distances.

#### What Is a Rhumb Line?
A **rhumb line** is a path on the Earth's surface that crosses all meridians at the same angle, maintaining a constant compass direction. On a Mercator projection map, a rhumb line appears as a straight line, simplifying navigation by allowing you to follow a consistent heading.

#### How to Use the Rhumb Line Function
1. Go to `FLT`
2. Select the Rhumb Line Function
3. Input Waypoint A (Starting Point)
  - **Enter Latitude**
    - Under `POINT: A`, select `LAT`.
    - Input the latitude in degrees, minutes, and seconds (**DMS**) or decimal degrees (there are two types of input **°** or **DMS**... Choose **DMS**).
      - **Degrees:** Enter the degrees portion of the latitude.
      - **Minutes:** Enter the minutes.
      - **Seconds:** Enter the seconds (if applicable).
  - **Enter Longitude**
    - Select `LONG`.
    - Input the longitude in degrees, minutes, and seconds (DMS) or decimal degrees.
      - **Degrees:** Enter the degrees portion of the longitude.
      - **Minutes:** Enter the minutes.
      - **Seconds:** Enter the seconds (if applicable).
4. Input Waypoint B (Destination Point)
  - Repeat the same process
5. You should have your answer:
```
RHUMB LINE: AB
TCrs   ______ Degrees
DIST  _______ NM (make sure to have the right unit conv)
```

An example would be a question like **What is the distance between these latitudes: N37°25’ and N39°10’?** == 120.83SM (make sure you have the right **unit conv**)

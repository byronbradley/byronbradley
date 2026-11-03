# Byron Bradley

I'm an electrical engineering student at the University at Buffalo, expecting to graduate in May 2028. I'm looking for a Summer 2027 internship in hardware, embedded systems, or test engineering.

Most of my hands-on experience comes from repairing game consoles and controllers. At UB, I'm working on the software for an IEEE maze robot.

[Portfolio](https://byronbradley.me/) · [LinkedIn](https://www.linkedin.com/in/byronpbradley/)

## [Electronics repair: Bytronyx](https://github.com/byronbradley/bytronyx)

I bought, repaired, and resold consoles and controllers through Bytronyx. The log covers 248 items, including 221 repairs, with notes on the faults, checks, work done, and testing.

Two examples: an [Xbox 360 with a shorted MOSFET](https://github.com/byronbradley/bytronyx/blob/main/repairs/records/EX-136.md) and a [PS3 with disc-loading and USB faults](https://github.com/byronbradley/bytronyx/blob/main/repairs/records/EX-092.md).

[Repair log](https://github.com/byronbradley/bytronyx/blob/main/repairs/README.md) · [Bench and stock photos](https://github.com/byronbradley/bytronyx/blob/main/docs/behind-bytronyx.md)

## [Maze robot](https://github.com/byronbradley/maze-robot)

My part of this IEEE project is the Python simulator and C++ firmware for an Arduino Nano 33 BLE Sense Rev2. The planner builds a map from wall readings and uses flood-fill to choose its next move. The simulation runs and the firmware compiles; assembly and calibration are still ahead.

[Simulation replay](https://byronbradley.github.io/maze-robot/) · [Firmware](https://github.com/byronbradley/maze-robot/blob/main/firmware/README.md) · [Design notes](https://github.com/byronbradley/maze-robot/blob/main/docs/design-decisions.md)

## [Inventory camera](https://github.com/byronbradley/inventory-camera)

A Python tool that reads inventory barcodes and logs them to CSV. It uses OpenCV and ZXing-C++; my code handles retries, camera capture, and repeated readings. Testing so far uses generated labels and mocked cameras. Raspberry Pi camera trials are next.

[Barcode experiments](https://github.com/byronbradley/inventory-camera/blob/main/docs/recognition-results.md) · [Pi setup](https://github.com/byronbradley/inventory-camera/blob/main/docs/pi-setup.md)

## [Archive migration proposal](https://github.com/byronbradley/rhinebeck-archive-migration)

I proposed transferring the Rhinebeck Historical Society's catalog and available scans to Internet Archive. The proposal is awaiting review at the November 2026 board meeting; migration has not started.

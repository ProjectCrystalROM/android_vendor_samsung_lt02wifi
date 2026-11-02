# Project Crystal lt02wifi stock-full vendor snapshot

This branch is based on the history of T210-dev/android_vendor_samsung_lt02wifi at f758332907a648915ce898c5f7c2d0e7cef50d5e. The stock-full payload and configuration were assembled from the Samsung SM-T210R T210RUEU0COI1/T210RXAR0COI1 firmware baseline. The files are proprietary and retain their original ownership and notices.

It is intended for checkout at `vendor/samsung/lt02wifi-stockfull` with the companion Crystal device and 8290 kernel branches. The audio policy and codec configuration include bring-up modifications; CM's source-built Bluetooth audio module is selected instead of the stock A2DP binary for compatibility with the CM Bluetooth stack. See the companion device tree's `docs/CRYSTAL_BRINGUP.md` for tested scope and remaining limitations.

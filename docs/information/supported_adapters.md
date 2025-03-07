# Supported adapters

## Overview
Zigbee2MQTT officially supports the following adapters:

<div style="width: 1000px">
<table>
  <tr>
    <td><b>Picture</b></td>
    <td><b>Name</b></td>
    <td><b>Description</b></td>
    <td><b>Firmware</b></td>
    <td><b>Guides</b></td>
    <td><b>Buy</b></td>
  </tr>
  <tr>
    <td><img src="../images/zzh.jpg"></td>
    <td>Electrolama zig-a-zig-ah! (zzh!) <b>(recommended)</b></td>
    <td>USB connected adapter with external antenna</td>
    <td><a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/coordinator/Z-Stack_3.x.0/bin/CC2652R_coordinator_20210120.zip">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/router/Z-Stack_3.x.0/bin/CC2652R_router_20210128.zip">Router</a></td>
    <td><a href="https://electrolama.com/radio-docs/#step-3-flash-the-firmware-on-your-stick">Flashing</a></td>
    <td><a href="https://www.tindie.com/products/electrolama/zzh-cc2652r-multiprotocol-rf-stick/#product-reviews">Tindie</a></td>
  </tr>
  <tr>
    <td><img src="../images/slaeshs_cc2652rb_stick.jpg"></td>
    <td>Slaesh's CC2652RB stick <b>(recommended)</b></td>
    <td>USB connected adapter with external antenna, <a href="https://github.com/Koenkk/zigbee2mqtt/discussions/6702">currently long shipping times</a></td>
    <td><a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/coordinator/Z-Stack_3.x.0/bin/CC2652RB_coordinator_20210120.zip">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/router/Z-Stack_3.x.0/bin/CC2652RB_router_20210128.zip">Router</a></td>
    <td><a href="https://slae.sh/projects/cc2652/#flashing">Flashing</a></td>
    <td><a href="https://slae.sh/projects/cc2652/">Slae.sh</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc2531.jpg"></td>
    <td>Texas Instruments CC2531</td>
    <td>USB connected Zigbee adapter with PCB antenna</td>
    <td>
      <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator/Z-Stack_Home_1.2/bin">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/router/Z-Stack_Home_1.2/bin">Router</a></td>
    <td><a href="/information/flashing_the_cc2531.html">Flashing</a></td>
    <td><a href="https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20191108075039&SearchText=cc2531">AliExpress</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc2530.jpg"></td>
    <td>Texas Instruments CC2530</td>
    <td>Serial connected adapter with external antenna optionally with CC2591 or CC2592 RF frontend</td>
    <td>
      <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator/Z-Stack_Home_1.2/bin">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/router/Z-Stack_Home_1.2/bin">Router</a></td>
    <td><a href="/how_tos/how_to_create_a_cc2530_router.html#2-flashing-the-cc2530">Flashing</a> <a href="/information/connecting_cc2530.html">Connecting</a></td>
    <td><a href="http://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20181213104041&SearchText=cc2530">AliExpress</a> <a href="http://www.gban.cn/en/product_show.asp?id=43">GBAN</a> <a href="https://www.tindie.com/products/GiovanniCas/cc2530-cc2592-zigbee-dongle/">Tindie</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc2538.jpg"></td>
    <td>Texas Instruments CC2538 PCB</td>
    <td>Serial connected adapter with CC2592 RF Amplifier</td>
    <td>
      <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator/Z-Stack_3.0.x/bin">Coordinator</a><br/></td>
    <td><a href="/information/flashing_the_cc2538.html">Flashing</a></td>
    <td><a href="https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20191108075039&SearchText=cc2538">AliExpress</a> <a href="https://www.tindie.com/products/GiovanniCas/cc2538-cc2592-zigbee-dongle-new-zb30/">Tindie</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc2538hat.jpg"></td>
    <td>Texas Instruments CC2538 HAT</td>
    <td>Raspberry pinout compatible HAT with CC2538 and optional external antenna</td>
    <td>
      <a href="https://github.com/Koenkk/Z-Stack-firmware/tree/master/coordinator/Z-Stack_3.0.x/bin">Coordinator</a><br/></td>
    <td><a href="/information/flashing_the_cc2538.html">Flashing</a></td>
    <td><a href="https://www.tindie.com/products/GiovanniCas/zigbee-hat-with-cc2538-for-raspberry/">Tindie</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc26x2r1.jpg"></td>
    <td>Texas Instruments LAUNCHXL-CC26X2R1</td>
    <td>USB connected development kit</td>
    <td><a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/coordinator/Z-Stack_3.x.0/bin/CC2652R_coordinator_20210120.zip">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/router/Z-Stack_3.x.0/bin/CC2652R_router_20210128.zip">Router</a></td>
    <td><a href="/information/flashing_via_uniflash.html">Flashing</a></td>
    <td><a href="http://www.ti.com/tool/LAUNCHXL-CC26X2R1">Texas Instruments</a></td>
  </tr>
  <tr>
    <td><img src="../images/cc1352p2.jpg"></td>
    <td>Texas Instruments LAUNCHXL-CC1352P-2</td>
    <td>USB connected development kit</td>
    <td><a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/coordinator/Z-Stack_3.x.0/bin/CC1352P2_CC2652P_launchpad_coordinator_20210120.zip">Coordinator</a><br/> <a href="https://github.com/Koenkk/Z-Stack-firmware/raw/master/router/Z-Stack_3.x.0/bin/CC1352P2_CC2652P_launchpad_router_20210128.zip">Router</a></td>
    <td><a href="/information/flashing_via_uniflash.html">Flashing</a></td>
    <td><a href="http://www.ti.com/tool/LAUNCHXL-CC1352P">Texas Instruments</a></td>
  </tr>
  <tr>
    <td><img src="../images/conbee.jpg"></td>
    <td>ConBee II <b>(experimental)</b></td>
    <td>USB connected adapter</td>
    <td><a href="https://github.com/dresden-elektronik/deconz-rest-plugin/wiki/Update-deCONZ-manually">Coordinator</a><br/></td>
    <td><a href="https://github.com/dresden-elektronik/deconz-rest-plugin/wiki/Update-deCONZ-manually">Flashing</a></td>
    <td><a href="https://phoscon.de/en/conbee2?buy=1#buy">Phoscon</a></td>
  </tr>
  <tr>
    <td><img src="../images/zigate_usb_ttl.png"></td>
    <td>ZiGate USB-TTL <b>(experimental)</b></td>
    <td>USB connected adapter based on NXP JN516x (JN5168/JN5169), 3.1d firmware or later required</td>
    <td><a href="https://zigate.fr/tag/firmware/">Coordinator</a><br/></td>
    <td></td>
    <td><a href="https://zigate.fr/boutique/?orderby=date_desc">ZiGate</a></td>
  </tr>
</table>
</div>

## Notes
Before buying an adapter, please read the notes below!

- Recommended adapters are the **Electrolama zig-a-zig-ah! (zzh!)** and **Slaesh's CC2652RB stick** because: they are very powerful, have good range (external antenna), are well tested with Zigbee2MQTT, are easy to connect (USB), can be flashed without additional hardware and are small in size.
- The following adapters require additional hardware to flash: adapters based on the **CC2530** and **CC2531** require a CC debugger and downloader cable, adapters based on the **CC2538** require a JTAG flasher.
- The **Electrolama zig-a-zig-ah! (zzh!)** (= based on CC2652R chip), **Slaesh's CC2652RB stick** (= based on CC2652RB chip), **Texas Instruments LAUNCHXL-CC26X2R1** (= based on CC2652R chip) and **Texas Instruments LAUNCHXL-CC1352P-2** (= based on CC1352P chip) are very similar to each other since (almost) the same chip is used. The difference between the CC2652R and the CC1352P is that the CC1352P support sub-1 GHz frequency (which is not relevant for Zigbee since it uses 2.4 GHz) and that the CC1352P has a power amplifier (which support up-to 20dBm output vs 5dBm on CC2652R(B)). The difference between the CC2652R and CC2652RB is that the CC2652RB doesn't require a crystal on the PCB, this only relevant for the manufacturing process. The ones with external antenna provide more range.
- Adapters based on the **CC2530** or **CC2531** chip are not powerful and not recommended for networks larger than 20 devices.
- Adapters that can handle large networks are; adapters using the following chips **CC2652R**, **CC2652RB**, **CC1352P**, **CC2538** and the **Conbee II**.
- Of all adapter the **Texas Instruments CC2531** has the worst range, other adapters with a PCB antenna like the **Texas Instruments LAUNCHXL-CC26X2R1** and **ConBee II** provide better range. Adapters with an external antenna have the best range.
- When migrating to another adapter make sure to modify your `pan_id` in your [configuration](configuration.md), otherwise Zigbee2MQTT won't start. Migrating to a different adapter [may require](./FAQ.md#what-does-and-does-not-require-repairing-of-all-devices) repairing all devices.
- Support for the **Conbee II** ([discussion](https://github.com/Koenkk/zigbee-herdsman/issues/72)) and **ZiGate USB-TTL** ([discussion](https://github.com/Koenkk/zigbee-herdsman/issues/242)) is experimental
- When using a **Conbee II** or **ZiGate USB-TTL** and you get: `Error: Failed to connect to the adapter (Error: SRSP - SYS - ping after 6000ms)` when starting Zigbee2MQTT set the following in your `configuration.yaml`.

```yaml
serial:
  adapter: deconz # deconz for Conbee II OR "zigate" for the ZiGate USB-TTL
```

### Router
Besides serving as a coordinator some adapters can also be used as a Zigbee router (check if there is a router firmware in the firmware column). To factory reset/pair:
- Texas Instruments CC2531: Press the S2 button for 5 seconds.
- Texas Instruments CC2530: Power on/power off the device three times (power on, wait 2 seconds, power off, repeat this cycle three times).
- Adapters based on CC2652R, CC2652RB and CC1352P: single press (one of the) buttons on the device
  - Slaesh's CC2652RB stick has 2 buttons where only the one furthest away from the USB connector can be used to factory reset.

### Texas Instruments LAUNCHXL-CC1352P-2 and LAUNCHXL-CC26X2R1
- These devices have two serial devices built in. Make sure you put the right serial device in the [configuration](configuration.md) or use auto detect (completely remove the `serial` section from `configuration.yaml`) if you only have one Texas Instruments CC device connected to your system.
- An external antenna can be connected which could increase range further:
  - LAUNCHXL-CC26X2R1: Has UF.L connector for external antenna ([requires resoldering a tiny capacitor (moving C14 to C24)](http://e2e.ti.com/support/wireless-connectivity/zigbee-and-thread/f/158/t/880219?LAUNCHXL-CC26X2R1-Antenna-CC26X2R1)).
  - LAUNCHXL-CC1352P-2: Has SMA connector for external antenna ([requires resoldering a tiny capacitor](https://github.com/Koenkk/zigbee2mqtt/issues/2162#issuecomment-570286663)).

# Ryan's SliceMK Ergodox Configuration

## Resources

- [Getting Started](https://www.slicemk.com/pages/ergodox-wireless-guide)
- [Keymap Configurator](https://config.slicemk.com/)
- [Bluetooth Pairing Guide](https://docs.slicemk.com/firmware/zmk/wireless/bluetooth/)

## Example `Custom DeviceTree Code`

```
/ {
ZMK_MACRO(btprofile0, wait-ms = <10>; tap-ms = <10>; bindings = <&macro_tap &bt BT_SEL 0>, <&macro_tap &out OUT_BLE>;)
ZMK_MACRO(btprofile1, wait-ms = <10>; tap-ms = <10>; bindings = <&macro_tap &bt BT_SEL 1>, <&macro_tap &out OUT_BLE>;)
ZMK_MACRO(btprofile2, wait-ms = <10>; tap-ms = <10>; bindings = <&macro_tap &bt BT_SEL 2>, <&macro_tap &out OUT_BLE>;)
ZMK_MACRO(btprofile3, wait-ms = <10>; tap-ms = <10>; bindings = <&macro_tap &bt BT_SEL 3>, <&macro_tap &out OUT_BLE>;)
ZMK_MACRO(btprofile4, wait-ms = <10>; tap-ms = <10>; bindings = <&macro_tap &bt BT_SEL 4>, <&macro_tap &out OUT_BLE>;)
};
```
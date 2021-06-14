### Paranoid Android Ruby Beta 1
- Initial unofficial build
- Optimized CAF to work on MediaTek chipsets
- Everything should work fine out of the box
- Might face some sort of lags, I am working on fixing that. Temporary fix - root your device using Magisk and change your CPU governor to Interactive.
- ROM is a production build without debugging and hence it is a user build with SEPolicy set to enforcing.
- WiFi STA+SAP concurrency does not work as of now.
- Encryption and lockscreen password works as intended
- Mobile Data settings is grayed out, due to a hack to run AOSP RIL service on CAF. Preferably, use a single SIM card since I don't have two to test.
- Rest, everything works. Grab the release off our releases.

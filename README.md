# UICC Chip Packaging

- ETSI [TS 102 671] (M2M UICC)
  - [x] [MFF1] (DFN8, 5×6×1.27 mm)
  - [x] [MFF2] (DFN8, 5×6×1.27 mm)
- [China Mobile][CMCC]
  - [x] [C2x2] (DFN8L, 2×2×0.5 mm)
- [ST]
  - [x] [ST33G1M2] (WLCSP11, 2.549×2.745×0.65 mm)
  - [x] [ST33J2M0] (WLCSP12, 2.328×2.487×0.5 mm)
- [Infineon]
  - [x] [OC1120] (WLCSP25, 2.9×2.5×0.4 mm)

## Notes

- The project was Made with [KiCAD]
- [MFF1], [MFF2] and [CMCC] [C2x2] pinout definitions are compatible
- **WARNING**: If use WLCSP packaging, Please read [ST TN1163] before use.
- **WARNING**: If use DFN packaging, Please read [OnSemi AND8211/D] before use.

## References

- [ST33GTPMISPI] (ST33G series, WLCSP11 package is the same)
- [MFF2 SIM Card Specs][MFF2-Specs]
- [MFF2 to 4FFNano Adapter][MFF2-4FF]
- [恒宝 M2M 智能卡产品规格书][HB-M2M] (Chinese)
- [中国移动 C2x2 eSIM 芯片技术概要 v1.1][C2x2] (Chinese)

## LICENSE

[CERN-OHL-P-2.0](LICENSE.txt)

[KiCAD]: https://www.kicad.org

<!-- ETSI -->

[TS 102 671]: https://standards.globalspec.com/std/14574971/ts-102-671
[MFF1]: https://www.etsi.org/deliver/etsi_ts/102600_102699/102671/18.00.00_60/ts_102671v180000p.pdf#page=14
[MFF2]: https://www.etsi.org/deliver/etsi_ts/102600_102699/102671/18.00.00_60/ts_102671v180000p.pdf#page=16
[MFF2-Specs]: https://iot-developer.thalesgroup.com/documentation/mff2-sim-cards-specs-mim-quad
[MFF2-4FF]: https://github.com/particle-iot/mff2-to-4ffnano

<!-- ST -->

[ST]: https://st.com/esim
[ST33G1M2]: https://www.st.com/resource/en/data_brief/st33g1m2.pdf
[ST33J2M0]: https://www.st.com/resource/en/data_brief/st33j2m0.pdf
[ST33GTPMISPI]: https://www.st.com/resource/en/data_brief/st33gtpmispi.pdf#page=7

<!-- Infineon -->

[Infineon]: https://infineon.com/esim
[OC1120]: https://www.infineon.com/dgdl/Infineon-OPTIGA%20CONNECT%20CONSUMER-DataSheet-v01_00-EN.pdf?fileId=8ac78c8c80027ecd01806fa1689c398e#page=25

<!-- CMCC -->

[CMCC]: https://iot.10086.cn/Chipmodule/read/id/511
[C2x2]: https://web.archive.org/web/20231230094012/https://www.doczj.com/doc/a914982959.html
[HB-M2M]: https://web.archive.org/web/20231230044358if_/https://img.jlc.com/pdf/applyPasteComponent/2021-07-20/08889A/7904557903d64a47b979fd51dfcb02c8/%E6%81%92%E5%AE%9DM2M%E6%99%BA%E8%83%BD%E5%8D%A1%E4%BA%A7%E5%93%81%E8%A7%84%E6%A0%BC%E4%B9%A6.pdf#page=5

<!-- Application Note -->

[ST TN1163]: https://www.st.com/resource/en/technical_note/tn1163-description-of-wlcsp-for-microcontrollers-and-recommendations-for-its-use-stmicroelectronics.pdf
[OnSemi AND8211/D]: https://www.onsemi.com/pub/Collateral/AND8211-D.PDF
